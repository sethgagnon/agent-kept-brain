# agent-kept-brain

A personal knowledge base that AI agents keep and you read. Your captures land in `raw/` and are never changed. Agents turn each one into a cited source page, then into pages about people, projects, decisions and ideas. A weekly retro proposes how the agents should improve, and nothing changes until you tick it.

This repo is one file: [`agent-kept-brain.md`](agent-kept-brain.md), a build spec you paste into Claude Code. It builds the whole vault in one pass: the rules file, the agents, the skills, the scripts, the schedule and a sample to try it on.

## Use it

1. Make an empty folder and open Claude Code in it.
2. Fill in the four fields at the top of `agent-kept-brain.md` (vault name, your name, time zone, scheduler).
3. Paste the whole file as your prompt.
4. Follow the README it writes: add your API key, copy the sample files into `raw/inbox/`, run the nightly job, read `reports/`.

## What you get

- **Files are the truth.** Plain Markdown in Git. Open it in Obsidian or any editor. Git history is the undo button.
- **Every claim is cited.** A line on a wiki page with no source does not go on the page.
- **Raw stays raw.** Agents cannot edit what you captured, enforced by both the rules and the tool permissions.
- **It learns, you decide.** Your own edits are treated as corrections. The weekly retro turns them into proposals you tick on your phone.
- **Caps everywhere.** Each run has limits on pages touched, so one bad night cannot rewrite the vault.

Add-ons (share-with-a-note requests, a playbook that carries lessons between side projects, a to-do feed, a weekly exam) are described at the end of the spec, to build when you want them.

## Tested

The spec was built from scratch by an agent that saw only this file. That build passed the spec's own acceptance checks, and the gaps it found were fixed in the spec.

## License

MIT

# agent-kept-brain

A personal knowledge base that AI agents keep and you read. Your captures land in `raw/` and are never changed. Agents turn each one into a cited source page, then into pages about people, projects, decisions and ideas. A weekly retro proposes how the agents should improve, and nothing changes until you tick it.

This repo is one file: [`agent-kept-brain.md`](agent-kept-brain.md), a build spec you paste into Claude Code. It builds the whole vault in one pass: the rules file, the agents, the skills, the scripts, the schedule and a sample to try it on.

The same spec as two images, for sharing or attaching: [page 1](images/page-01.png), [page 2](images/page-02.png).

## Use it

1. Make an empty folder and open Claude Code in it.
2. Optional: fill in the four fields at the top of `agent-kept-brain.md` (vault name, your name, time zone, scheduler). If you skip them it asks for your name and time zone.
3. Paste the whole file as your prompt, or attach the two page images and say "build this".
4. It builds the vault, runs its own checks, then walks you through a first session: a demo on sample files, adding the people you work with, and the last setup steps for your machine or GitHub.

## What you get

- **Files are the truth.** Plain Markdown in Git. Open it in Obsidian or any editor. Git history is the undo button.
- **Every claim is cited.** A line on a wiki page with no source does not go on the page.
- **Raw stays raw.** Agents cannot edit what you captured, enforced by both the rules and the tool permissions.
- **It learns, you decide.** Your own edits are treated as corrections. The weekly retro turns them into proposals you tick on your phone. Each change you approve records a baseline and a review date, and the retro later writes down whether it was kept or rolled back, with the numbers.
- **Caps everywhere.** Each run has limits on pages touched, so one bad night cannot rewrite the vault.

Add-ons (share-with-a-note requests, a playbook that carries lessons between side projects, a to-do feed, a weekly exam) are described at the end of the spec, to build when you want them.

## Tested

The spec was built from scratch by an agent that saw only this file. That build passed the spec's own acceptance checks, and the gaps it found were fixed in the spec.

## License

MIT

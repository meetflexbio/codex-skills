# codex-skills

This repository stores my Codex skills setup so I can move it to another machine and keep track of what is installed.

## What goes here

- `manifest/installed-skills.json` - current installed skills and where they came from
- `custom-skills/` - my own custom skills that should be copied in full
- `notes/` - setup notes and future ideas

## Current installed skills

- `doc`
- `pdf`
- `playwright`
- `sora`
- `spreadsheet`

System skills such as `skill-installer`, `skill-creator`, `plugin-creator`, `openai-docs`, and `imagegen` are managed by Codex and usually do not need to be backed up here.

## How to restore on another computer

1. Install Codex.
2. Clone this repository.
3. Reinstall official/community skills from `manifest/installed-skills.json`.
4. Copy any folders from `custom-skills/` into `~/.codex/skills`.
5. Restart Codex.

## Next additions

- Add community skills for outreach automation
- Create a custom `make-com-outreach` skill

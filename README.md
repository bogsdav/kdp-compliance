# KDP Compliance

A Claude skill. Review Amazon KDP planners, journals, covers, listings, AI disclosures, Canva licenses, and promotion for compliance. Use when creating, checking, updating, or preparing books for publication.

## What's inside

- `kdp-compliance/SKILL.md`

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download this repo as a ZIP (**Code > Download ZIP**) and unzip it.
2. Zip the `kdp-compliance` folder on its own, so the ZIP contains `kdp-compliance/SKILL.md`.
3. In Claude's settings, open the Skills section, upload that ZIP, and turn the skill on.

### Claude Code

```bash
git clone https://github.com/bogsdav/kdp-compliance.git
mkdir -p ~/.claude/skills
cp -r kdp-compliance/kdp-compliance ~/.claude/skills/
```

Restart Claude Code. The skill loads automatically when a request matches its description.

## Try it

- "Check this planner listing against KDP's content and metadata rules."
- "Do I need to disclose AI use for this cover and interior?"
- "Review my Canva elements for KDP licensing issues."

## License

MIT. See [LICENSE](LICENSE).

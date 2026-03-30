# seo-expert-skill

A refactored, multi-agent SEO skill package centered on practical audits, SEO diagnostics, and implementation guidance.

## Layout

- `skills/seo-expert/SKILL.md` — core skill
- `skills/seo-expert/references/` — deeper topic modules
- `skills/seo-expert/scripts/audit_page.py` — structured page audit helper

## Install locally with skills CLI

```bash
npx skills add . --skill seo-expert -a openclaw -a github-copilot --copy -y
```

## Publish targets

- GitHub repo
- ClawHub (`clawhub publish ...`)
- Skills ecosystem via GitHub repo compatibility (`npx skills add owner/repo`)

# amir-skills

One Claude Code marketplace for all of [Amir's](https://github.com/Amir-Abushanab) skills. Add it once, install any of them:

```
/plugin marketplace add Amir-Abushanab/skills
```

| Skill | Install | What it does |
|---|---|---|
| [understudy](https://github.com/Amir-Abushanab/understudy) | `/plugin install understudy@amir-skills` | Measure a website's brand identity (color, type, spacing, motion) from the live page, then learn its feel. |
| [modern-frontend-architecture](https://github.com/Amir-Abushanab/modern-frontend-architecture) | `/plugin install modern-frontend-architecture@amir-skills` | House standard for architecting modern web frontends — type-safe, agent-first defaults for stack, data, state, styling, security, logging, i18n, and deploy. |

Each skill lives in its own repo; this repo is just the catalog (`.claude-plugin/marketplace.json`) pointing at them. Installs always pull the skill's default branch, so updates ship without touching this repo. Sources are HTTPS `url`s, not `github` shorthands — Claude Code clones `github` sources over SSH only, which fails for anyone without a GitHub SSH key loaded.

MIT.

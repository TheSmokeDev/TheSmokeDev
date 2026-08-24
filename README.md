# SmokeDev

I build open-source systems that make coding agents useful in real work: inspectable
commands, deterministic gates, machine-readable receipts, and explicit boundaries
between local output and public state.

## GEO, AI search, and programmatic SEO

### [geo-skills](https://github.com/TheSmokeDev/geo-skills)

[![Stars](https://img.shields.io/github/stars/TheSmokeDev/geo-skills?style=social)](https://github.com/TheSmokeDev/geo-skills/stargazers)
[![PyPI](https://img.shields.io/pypi/v/geoskills)](https://pypi.org/project/geoskills/)
[![CI](https://github.com/TheSmokeDev/geo-skills/actions/workflows/ci.yml/badge.svg)](https://github.com/TheSmokeDev/geo-skills/actions/workflows/ci.yml)

Twenty-nine free Agent Skills plus the `geoskills` CLI for Generative Engine
Optimization, AI-search visibility, citability, crawler access, live-data prompt
packs, and owner-intent mapping. Works with Claude Code, Codex, and other agents that
read `SKILL.md`.

```bash
python -m pip install geoskills
```

### [token-max-site-factory](https://github.com/TheSmokeDev/token-max-site-factory)

[![PyPI](https://img.shields.io/pypi/v/token-max-site-factory)](https://pypi.org/project/token-max-site-factory/)
[![CI](https://github.com/TheSmokeDev/token-max-site-factory/actions/workflows/ci.yml/badge.svg)](https://github.com/TheSmokeDev/token-max-site-factory/actions/workflows/ci.yml)

An agent-native programmatic SEO/GEO factory. It scans a site, generates
evidence-backed pages, blocks weak or duplicate output, and emits provenance receipts.
It never deploys, changes DNS, or submits URLs.

```bash
python -m pip install token-max-site-factory
```

```text
research + community + AI prompt panels
                  ↓
             geo-skills
                  ↓
        owner-intent-map.json
                  ↓
      token-max-site-factory
                  ↓
       validated pages + receipts
```

## Other open-source work

- [Archon](https://github.com/TheSmokeDev/Archon) — agent workflow orchestration.
- [PIV Loop SDK](https://github.com/TheSmokeDev/piv--loop-sdk) — plan, implement, validate delivery loops.
- [CLUTCH](https://github.com/TheSmokeDev/clutch) — coding-agent execution tooling.
- [Hermes Talk](https://github.com/TheSmokeDev/hermes-talk) — durable operator UX for terminal agents.

I care about proof over hype: tests that exercise installed commands, source-separated
measurement, fail-closed validation, and claims that say exactly whether something is
local, pushed, merged, deployed, indexed, or cited.

# create-auth-plugin

Standalone home for the OpenCode `create-auth-plugin` skill.

## What this repository contains
- `SKILL.md` — canonical skill definition

## Current use
- Auth plugin scaffolding
- Provider login flows
- Credential cache injection
- Token rotation watchers

## Install
```bash
mkdir -p ~/.config/opencode/skills
rm -rf ~/.config/opencode/skills/create-auth-plugin
git clone https://github.com/SIN-Skills/create-auth-plugin ~/.config/opencode/skills/create-auth-plugin
```

## Goal
Make auth plugins predictable and shippable.

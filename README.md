# Zeke's Skills

Agent skills are reusable instructions for AI coding agents like OpenCode, Claude Code, Codex, and [others](https://www.skills.sh/agent).

This repo is a collection of skills I use, skills I maintain, and the tools I use to manage them.

## How skills work

- Skills can be simple Markdown files.
- Skills can also include code, scripts, images, templates, and other assets.
- Skills can be invoked explicitly by a user.
- Skills can be invoked implicitly by the model based on context.
- Skills always include metadata like a name and description.
- Skill metadata is loaded up front so agents know what skills exist.
- Skill content is loaded only when needed to minimize context usage.

## Tools

- [agentskills.io](https://agentskills.io) - Home of the official Agent Skills specification.
- [skills.sh](https://skills.sh) - Registry for finding skills.
- [`npx skills`](https://github.com/vercel-labs/skills) - CLI for installing skills on any agent.

## Skills I maintain

- [replicate/skills](https://github.com/replicate/skills) - Official Replicate skills for building AI-powered apps with Replicate.
- [zeke/faster-chrome-devtools-skill](https://github.com/zeke/faster-chrome-devtools-skill) - A faster Chrome DevTools workflow for coding agents.
- [zeke/faster-gh-cli-skill](https://github.com/zeke/faster-gh-cli-skill) - Reliable GitHub CLI usage patterns for coding agents.
- [zeke/preview-deployments-skill](https://github.com/zeke/preview-deployments-skill) - Add Cloudflare Workers preview deployments to GitHub apps.
- [zeke/swiss-design-skill](https://github.com/zeke/swiss-design-skill) - Swiss International Style design guidance for AI agents.
- [zeke/helicopter-skill](https://github.com/zeke/helicopter-skill) - Novelty: A helicopter flying guidance for AI agents, inspired by The Matrix.

## Skills I use

- [vercel-labs/find-skills](https://github.com/vercel-labs/skills/blob/main/skills/find-skills/SKILL.md) - find other skills.
- [replicate/skills](https://github.com/replicate/skills) - Find, compare, and run generative AI models on Replicate.
- [typefully/agent-skills](https://github.com/typefully/agent-skills) - Draft and schedule social media posts with Typefully.
- [railly/tinte](https://github.com/railly/tinte) - Generate screenshots of code snippets and terminal commands via API.
- [mattpocock/teach](https://github.com/mattpocock/skills/tree/main/skills/productivity/teach) - Learn anything interactively, like how to speak German or solve a rubik's cube.

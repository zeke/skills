# Agent Skills

Agent skills are reusable instructions for AI coding agents like OpenCode, Claude Code, Codex, and [others](https://www.skills.sh/agent).

- Skills can be simple Markdown files.
- Skills can also include code, scripts, images, templates, and other assets.
- Skills can be invoked explicitly by a user.
- Skills can be invoked implicitly by the model based on context.
- Skills always include metadata like a name and description.
- Skill metadata is loaded up front so agents know what skills exist.
- Skill content is loaded only when needed to minimize context usage.

## Tools

- [agentskills.io](https://agentskills.io) - home of the official Agent Skills [spec](https://agentskills.io/specification).
- [skills.sh](https://skills.sh) - registry for finding skills
- [`npx skills`](https://github.com/vercel-labs/skills) - CLI for installing skills on [any agent](https://www.skills.sh/agent)

## Skills I Maintain

- [replicate/skills](https://github.com/replicate/skills) - Official Replicate skills for building AI-powered apps with Replicate.
- [zeke/faster-chrome-devtools-skill](https://github.com/zeke/faster-chrome-devtools-skill) - A faster Chrome DevTools workflow for coding agents.
- [zeke/faster-gh-cli-skill](https://github.com/zeke/faster-gh-cli-skill) - Reliable GitHub CLI usage patterns for coding agents.
- [zeke/preview-deployments-skill](https://github.com/zeke/preview-deployments-skill) - Add Cloudflare Workers preview deployments to GitHub apps.
- [zeke/swiss-design-skill](https://github.com/zeke/swiss-design-skill) - Swiss International Style design guidance for AI agents.
- [zeke/helicopter-skill](https://github.com/zeke/helicopter-skill) - Novelty: A helicopter flying guidance for AI agents, inspired by The Matrix.

## Skills I Use

- [vercel-labs/find-skills](https://github.com/vercel-labs/skills/blob/main/skills/find-skills/SKILL.md) - a skill for finding other skills
- [replicate/skills](https://github.com/replicate/skills) - Official [Replicate](https://replicate.com) skills for finding and running generative AI models
- [typefully/agent-skills](https://github.com/typefully/agent-skills) - Skills for drafting and scheduling social media posts with [Typefully](https://typefully.com) to post to X, BlueSky, LinkedIn, etc in one shot.
- [railly/tinte](https://github.com/railly/tinte) - API for generating screenshots of code snippets and terminal commands.
- [mattpocock/teach](https://github.com/mattpocock/skills/tree/main/skills/productivity/teach) - Get your agent to teach you anything, like how to speak German or solve a rubik's cube.

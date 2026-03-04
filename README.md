# Awesome LLM CLI Apps

> A curated list of CLI and TUI applications designed to be used by or with LLM-powered coding agents like [Claude Code](https://code.claude.com), [OpenClaw](https://openclaw.ai), [Codex CLI](https://github.com/openai/codex), and [Gemini CLI](https://github.com/google-gemini/gemini-cli).

These are **not** the AI agents themselves — they're the tools that give agents hands. CLI apps with structured output (JSON, plain text) that LLMs can invoke to interact with the real world: send messages, manage tasks, automate browsers, control smart homes, and more.

**Why CLI over MCP?** CLI tools follow the Unix philosophy — small, composable, and pipeable. They're more token-efficient than MCP (no large tool schemas in context), work across any agent platform, and are trivially testable by humans. [Read more](https://medium.com/@rentierdigital/why-clis-beat-mcp-for-ai-agents-and-how-to-build-your-own-cli-army-6c27b0aec969).

---

## Contents

- [macOS Native App CLIs](#macos-native-app-clis)
- [Messaging & Communication](#messaging--communication)
- [Browser Automation](#browser-automation)
- [Project Management](#project-management)
- [Developer Tools](#developer-tools)
- [Terminal Productivity](#terminal-productivity)
- [AI Agent Frameworks](#ai-agent-frameworks)
- [Skills & Skill Registries](#skills--skill-registries)
- [Related Awesome Lists](#related-awesome-lists)

---

## macOS Native App CLIs

Tools that expose macOS native apps to the command line, making them accessible to AI agents.

| Tool | Description | Author |
|------|-------------|--------|
| [remindctl](https://github.com/steipete/remindctl) | CLI for Apple Reminders — list, add, edit, complete, delete reminders with JSON output. | [@steipete](https://github.com/steipete) |
| [memo](https://github.com/antoniorodr/memo) | CLI for Apple Notes and Apple Reminders — create, view, edit, delete, search, move, and export notes. Python-based. | [@antoniorodr](https://github.com/antoniorodr) |
| [remind](https://github.com/migueravila/remind) | Apple Reminders for terminal natives. Swift-based. | [@migueravila](https://github.com/migueravila) |

## Messaging & Communication

CLI tools for sending and reading messages across platforms — ideal for AI assistants that need to communicate.

| Tool | Description | Author |
|------|-------------|--------|
| [imsg](https://github.com/steipete/imsg) | macOS iMessage/SMS CLI — send, read, stream messages with attachment metadata. JSON output. 757+ stars. | [@steipete](https://github.com/steipete) |
| [wacli](https://github.com/steipete/wacli) | WhatsApp CLI — sync, search, send messages and files. Cookie-based auth. | [@steipete](https://github.com/steipete) |
| [whatsapp-cli](https://github.com/eddmann/whatsapp-cli) | WhatsApp CLI built as an AI agent skill exploration — chats, messages, contacts, media. Go-based. | [@eddmann](https://github.com/eddmann) |
| [bird](https://clawbot.ai/ecosystem/bird-twitter-cli.html) | X/Twitter CLI — read tweets, search, view timelines and bookmarks. Cookie auth (no API keys needed). | [@steipete](https://github.com/steipete) |
| [slack-cli](https://api.slack.com/automation/cli) | Official Slack CLI for building and managing Slack automations. | Slack |

## Browser Automation

Tools that let AI agents control web browsers from the command line.

| Tool | Description | Author |
|------|-------------|--------|
| [playwright-cli](https://github.com/microsoft/playwright-cli) | Official Playwright CLI for browser automation — navigate, interact, screenshot, extract data. Token-efficient SKILL mode for coding agents. | Microsoft |
| [playwriter](https://github.com/remorses/playwriter) | Control your own Chrome (with existing logins, cookies, extensions) via CLI. Uses your real browser sessions. | [@remorses](https://github.com/remorses) |

## Project Management

CLI access to project management platforms.

| Tool | Description | Author |
|------|-------------|--------|
| [linearis](https://github.com/czottmann/linearis) | CLI for Linear.app with JSON output — issues, cycles, labels, assignments. Designed for AI agent use. | [@czottmann](https://github.com/czottmann) |
| [linear-cli](https://github.com/mixpeek/linear-cli) | TypeScript CLI for Linear using @linear/sdk — list, view, manage issues. | [@mixpeek](https://github.com/mixpeek) |
| [gh](https://cli.github.com/) | Official GitHub CLI — PRs, issues, releases, Actions, repos. Extensively used by Claude Code and other agents. | GitHub |

## Developer Tools

Tools that enhance the development workflow when used alongside AI coding agents.

| Tool | Description | Author |
|------|-------------|--------|
| [lazygit](https://github.com/jesseduffield/lazygit) | Terminal UI for git — review diffs, stage hunks, interactive rebase. Essential for reviewing AI-generated changes. 57k+ stars. | [@jesseduffield](https://github.com/jesseduffield) |
| [aider](https://github.com/Aider-AI/aider) | AI pair programming in your terminal — supports Claude, GPT, Gemini, local models. 39k+ stars. | [@paul-gauthier](https://github.com/paul-gauthier) |
| [mods](https://github.com/charmbracelet/mods) | AI for the command line — pipe any command output to an LLM. Built by Charm. | [Charm](https://github.com/charmbracelet) |
| [llm](https://github.com/simonw/llm) | CLI for interacting with LLMs — supports plugins, templates, embeddings. Python-based. | [@simonw](https://github.com/simonw) |
| [glow](https://github.com/charmbracelet/glow) | Render Markdown in the terminal — great for reading CLAUDE.md, plan files, docs. | [Charm](https://github.com/charmbracelet) |
| [csvlens](https://github.com/YS-L/csvlens) | TUI for inspecting CSVs — useful when AI agents generate CSV reports. | [@YS-L](https://github.com/YS-L) |

## Terminal Productivity

General terminal tools that pair well with AI-assisted workflows.

| Tool | Description | Author |
|------|-------------|--------|
| [eza](https://github.com/eza-community/eza) | Modern `ls` replacement with color coding, icons, and git integration. | [eza-community](https://github.com/eza-community) |
| [zoxide](https://github.com/ajeetdsouza/zoxide) | Smarter `cd` — learns your habits. Stops you typing long paths. | [@ajeetdsouza](https://github.com/ajeetdsouza) |
| [yazi](https://github.com/sxyazi/yazi) | Blazing fast terminal file manager with image preview. | [@sxyazi](https://github.com/sxyazi) |
| [bat](https://github.com/sharkdp/bat) | A `cat` clone with syntax highlighting and git integration. | [@sharkdp](https://github.com/sharkdp) |
| [ripgrep](https://github.com/BurntSushi/ripgrep) | Ultra-fast recursive search — the engine behind many AI agent search tools. | [@BurntSushi](https://github.com/BurntSushi) |
| [fd](https://github.com/sharkdp/fd) | Simple, fast alternative to `find`. | [@sharkdp](https://github.com/sharkdp) |
| [jq](https://github.com/jqlang/jq) | Command-line JSON processor — essential for parsing CLI tool output. | [jqlang](https://github.com/jqlang) |

## AI Agent Frameworks

The LLM-powered coding agents that use the tools above.

| Tool | Description | Author |
|------|-------------|--------|
| [Claude Code](https://code.claude.com) | Anthropic's agentic coding CLI — skills, MCP, hooks, plugins. | Anthropic |
| [OpenClaw](https://github.com/openclaw/openclaw) | Personal AI assistant — runs on your devices, connects to WhatsApp, Telegram, Slack, Discord, iMessage, and more. 50+ integrations. | [@steipete](https://github.com/steipete) |
| [Codex CLI](https://github.com/openai/codex) | OpenAI's coding agent for the terminal. | OpenAI |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Google's AI agent for the terminal. | Google |
| [OpenCode](https://github.com/opencode-ai/opencode) | Open-source coding agent — 75+ LLM providers, LSP integration. 95k+ stars. | [opencode-ai](https://github.com/opencode-ai) |
| [Crush](https://github.com/charmbracelet/crush) | Charm's coding agent TUI — LSP-powered, cross-platform. | [Charm](https://github.com/charmbracelet) |
| [Toad](https://github.com/textualize/toad) | Unified TUI for multiple coding agents via ACP. By the creator of Rich/Textual. | [Textualize](https://github.com/textualize) |
| [Cline](https://github.com/cline/cline) | Autonomous coding agent — 48k+ stars. | [Cline](https://github.com/cline) |
| [Grok CLI](https://github.com/xai-org/grok-cli) | xAI's terminal interface — supports local inference for offline use. | xAI |

## Skills & Skill Registries

Skills teach AI agents *how* to use CLI tools. They're markdown files with instructions that agents follow.

| Resource | Description |
|----------|-------------|
| [ClawHub](https://github.com/openclaw/clawhub) | Official skill registry for OpenClaw — publish, version, and search skills. |
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 5,400+ community-built OpenClaw skills, filtered and categorized. |
| [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | Curated Claude Code skills collection. |
| [Smithery Skills](https://smithery.ai/skills) | Cross-platform skill marketplace. |
| [Claude Code Skills Docs](https://code.claude.com/docs/en/skills) | Official documentation for building Claude Code skills. |
| [Agent Skills Standard](https://github.com/eddmann/whatsapp-cli#agent-skills) | Emerging standard for AI-tool interoperability via SKILL.md files. |

### Example Skills for Tools in This List

| Skill | For Tool | Platform |
|-------|----------|----------|
| `remindctl` | Apple Reminders via remindctl | Claude Code, OpenClaw |
| `memo` / `apple-notes` | Apple Notes via memo | Claude Code, OpenClaw |
| `imsg` | iMessage via imsg | Claude Code, OpenClaw |
| `bird` | X/Twitter via bird | OpenClaw |
| `wacli` | WhatsApp via wacli | OpenClaw |
| `playwright-cli` | Browser automation via Playwright | Claude Code |
| `linearis` | Linear.app via linearis | Claude Code |

## Related Awesome Lists

- [awesome-AI-driven-development](https://github.com/eltociear/awesome-AI-driven-development) — Comprehensive list of AI-driven development tools.
- [awesome-cli-apps-in-a-csv](https://github.com/toolleeo/awesome-cli-apps-in-a-csv) — Massive CLI apps catalog.
- [awesome-openclaw](https://github.com/rohitg00/awesome-openclaw) — Resources for the OpenClaw ecosystem.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

A tool belongs here if it:

1. **Has a CLI interface** with structured output (JSON, plain text)
2. **Is designed for or works well with LLM agents** — not just a general CLI tool
3. **Bridges the gap** between AI agents and real-world systems (messaging, browsers, APIs, native apps)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

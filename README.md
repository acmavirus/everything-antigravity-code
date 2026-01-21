# 🌌 Everything Antigravity Code

A comprehensive collection of specialized agents, expert skills, coding rules, and automated workflows designed to supercharge your experience with **Antigravity**, configured according to the latest official standards.

This repository serves as a **Global Configuration Hub** for Antigravity. By following the installation steps, you can make these tools available in **every project** you open.

## 🚀 Key Features

- **Specialized Agents**: Architect, Planner, Security Reviewer, TDD Guide, and more.
- **Global Skills**: Structured knowledge libraries (Frontend/Backend patterns, ClickHouse, etc.).
- **Unified Global Rules**: All essential coding rules consolidated into `GEMINI.md`.
- **Global Workflows**: Automated slash commands (`/plan`, `/tdd`, `/code-review`) available everywhere.
- **Pre-configured MCP**: A robust set of Model Context Protocol servers for GitHub, Supabase, Cloudflare, and more.

## 📂 Official Directory Structure (Used Here)

According to the latest documentation:
- **Global Rules**: `~/.gemini/GEMINI.md` (Applied across all workspaces).
- **Global Skills**: `~/.gemini/antigravity/global_skills/<skill-name>/SKILL.md`.
- **Global Workflows**: `~/.gemini/antigravity/workflows/`.
- **Custom Agents**: `~/.gemini/antigravity/agents/`.

## 🛠 Installation (Standard & Global)

To install this setup globally on your system:

### 1. Locate your Antigravity Config Directory
- **Windows**: `C:\Users\<YourUser>\.gemini\antigravity\`
- **macOS/Linux**: `~/.gemini/antigravity/`

### 2. Copy components to standard locations:

| Component | Repository Source | Global Destination |
|-----------|-------------------|-------------------|
| **Agents** | `agents/` | `~/.gemini/antigravity/agents/` |
| **Skills** | `global_skills/` | `~/.gemini/antigravity/global_skills/` (Each skill folder must contain a `SKILL.md`) |
| **Workflows** | `workflows/` | `~/.gemini/antigravity/workflows/` |
| **Global Rules**| `GEMINI.md` | `~/.gemini/GEMINI.md` |
| **MCP Config** | `mcp-configs/mcp-servers.json` | Merge into `~/.gemini/antigravity/mcp_config.json` |

### 3. Setup MCP Servers
Copy the contents of `mcp-configs/mcp-servers.json` into your global `mcp_config.json`.
> **Note**: Remember to replace placeholders (like `YOUR_GITHUB_PAT_HERE`) with your actual API keys.

---
## 🤖 Available Commands (Global)

- `/plan` - restate requirements, assess risks, and create implementation plan.
- `/tdd` - enforce test-driven development workflow.
- `/code-review` - comprehensive security and quality review.
- `/e2e` - generate and run end-to-end tests with Playwright.

## 📜 Core Principles
1. **GEMINI.md First**: Global constraints are always checked.
2. **SKILL.md Standards**: Every skill is defined by its standard documentation file.
3. **Task-Specific Agents**: Use the right agent for the right stage (Architect for design, TDD for implementation).

---
Built with ❤️ for the Antigravity community.

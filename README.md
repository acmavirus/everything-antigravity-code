# 🌌 Everything Antigravity Code

A comprehensive collection of specialized agents, expert skills, coding rules, and automated workflows designed to supercharge your experience with **Antigravity**.

This repository serves as a "Global Configuration Hub" that can be integrated directly into your Antigravity installation to provide consistent, high-quality AI assistance across all your coding projects.

## 🚀 Key Features

- **Advanced Agents**: Specialized personas for Architecture, Planning, Security, TDD, and more.
- **Expert Skills**: Domain-specific knowledge libraries (Frontend, Backend, Security, analytics).
- **Strict Coding Rules**: Enforced standards for style, performance, security, and Git workflow.
- **Workflow Commands**: Slash commands (`/plan`, `/tdd`, `/code-review`) to automate complex tasks.
- **Global MCP Config**: A pre-configured set of Model Context Protocol servers (GitHub, Supabase, Cloudflare, etc.).

## 📂 Project Structure

```text
.agent/workflows/   # Slash command definitions (Slash Commands)
agents/             # Specialized AI personas
rules/              # Project-wide coding and security rules
skills/             # Deep domain knowledge and patterns
hooks/              # Tool-use hooks (e.g., auto-formatting, linting)
mcp-configs/        # Global MCP server configurations
contexts/           # Task-specific context definitions
```

## 🛠 Installation (Global Setup)

To make these configurations available for **every project** you open in Antigravity, follow these steps:

### 1. Locate your Antigravity Config Directory
Typically located at:
- **Windows**: `C:\Users\<YourUser>\.gemini\antigravity\`
- **macOS/Linux**: `~/.gemini/antigravity/`

### 2. Copy the contents
Copy all folders (`agents`, `rules`, `skills`, `hooks`, `.agent`, etc.) from this repository into your Antigravity config directory.

### 3. Setup MCP Servers
Copy the content of `mcp-configs/mcp-servers.json` into your global `mcp_config.json`.
> **Note**: Remember to replace placeholders (like `YOUR_GITHUB_PAT_HERE`) with your actual API keys.

### 4. Verify Installation
Open Antigravity and try running:
- `/plan` - To start a new feature planning session.
- `/tdd` - To begin a test-driven development loop.
- `/code-review` - To get a deep audit of your current changes.

## 🤖 Available Agents

- **Architect**: System design and scalability decisions.
- **Planner**: Step-by-step implementation strategies.
- **TDD Guide**: Specialized in Red-Green-Refactor workflows.
- **Security Reviewer**: Deep audit for vulnerabilities.
- **Build Resolver**: Automated fixing of build and lint errors.

---

## 📜 Principles

1. **High Cohesion**: Small, focused files over monolithic ones.
2. **Security First**: No secrets in code, validated inputs.
3. **Test Driven**: If it's not tested, it's broken.
4. **Automated Excellence**: Use hooks to catch errors before they are committed.

---
Built with ❤️ for the Antigravity community.

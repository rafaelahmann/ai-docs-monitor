# Overview - Claude Code Docs

**URL:** https://code.claude.com/docs/en/overview

---

Skip to main content
Claude Code Docs home page
English
Search...
Ctrl K
Ask AI
Claude Developer Platform
Claude Code on the Web
Getting started
Build with Claude Code
Administration
Configuration
Reference
Agent SDK
What's New
Resources
Getting started
Overview
Quickstart
Changelog
Core concepts
How Claude Code works
Extend Claude Code
Explore the .claude directory
Explore the context window
Prompt caching
Use Claude Code
Store instructions and memories
Permission modes
Common workflows
Best practices
Platforms and integrations
Overview
Remote Control
Claude Code on the web
Claude Code on desktop
Chrome extension (beta)
Computer use (preview)
Visual Studio Code
JetBrains IDEs
Code review & CI/CD
Claude Code in Slack
On this page
Get started
What you can do
Use Claude Code everywhere
Next steps
GETTING STARTED
Overview

Claude Code is an agentic coding tool that reads your codebase, edits files, runs commands, and integrates with your development tools. Available in your terminal, IDE, desktop app, and browser.

Copy page
Documentation Index

Fetch the complete documentation index at: https://code.claude.com/docs/llms.txt

Use this file to discover all available pages before exploring further.

Claude Code is an AI-powered coding assistant that helps you build features, fix bugs, and automate development tasks. It understands your entire codebase and can work across multiple files and tools to get things done.
​
Get started
Choose your environment to get started. Most surfaces require a Claude subscription or Anthropic Console account. The Terminal CLI and VS Code also support third-party providers.
Terminal
VS Code
Desktop app
Web
JetBrains
The full-featured CLI for working with Claude Code directly in your terminal. Edit files, run commands, and manage your entire project from the command line.
To install Claude Code, use one of the following methods:
Native Install (Recommended)
Homebrew
WinGet
macOS, Linux, WSL:
curl -fsSL https://claude.ai/install.sh | bash

Windows PowerShell:
irm https://claude.ai/install.ps1 | iex

Windows CMD:
curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd

If you see The token '&&' is not a valid statement separator, you’re in PowerShell, not CMD. If you see 'irm' is not recognized as an internal or external command, you’re in CMD, not PowerShell. Your prompt shows PS C:\ when you’re in PowerShell and C:\ without the PS when you’re in CMD.
Git for Windows is recommended on native Windows so Claude Code can use the Bash tool. If Git for Windows is not installed, Claude Code uses PowerShell as the shell tool instead. WSL setups do not need Git for Windows.
Native installations automatically update in the background to keep you on the latest version.
You can also install with apt, dnf, or apk on Debian, Fedora, RHEL, and Alpine.
Then start Claude Code in any project:
cd your-project
claude

You’ll be prompted to log in on first use. That’s it! Continue with the Quickstart →
See advanced setup for installation options, manual updates, or uninstallation instructions. Visit installation troubleshooting if you hit issues.
​
What you can do
Here are some of the ways you can use Claude Code:

Automate the work you keep putting off

Build features and fix bugs

Create commits and pull requests

Connect your tools with MCP

Customize with instructions, skills, and hooks

Run agent teams and build custom agents

Pipe, script, and automate with the CLI

Schedule recurring tasks

Work from anywhere

​
Use Claude Code everywhere
Each surface connects to the same underlying Claude Code engine, so your CLAUDE.md files, settings, and MCP servers work across all of them.
Beyond the Terminal, VS Code, JetBrains, Desktop, and Web environments above, Claude Code integrates with CI/CD, chat, and browser workflows:
I want to…	Best option
Continue a local session from my phone or another device	Remote Control
Push events from Telegram, Discord, iMessage, or my own webhooks into a session	Channels
Start a task locally, continue on mobile	Web or Claude iOS app
Run Claude on a recurring schedule	Routines or Desktop scheduled tasks
Automate PR reviews and issue triage	GitHub Actions or GitLab CI/CD
Get automatic code review on every PR	GitHub Code Review
Route bug reports from Slack to pull requests	Slack
Debug live web applications	Chrome
Build custom agents for your own workflows	Agent SDK
​
Next steps
Once you’ve installed Claude Code, these guides help you go deeper.
Quickstart: walk through your first real task, from exploring a codebase to committing a fix
Store instructions and memories: give Claude persistent instructions with CLAUDE.md files and auto memory
Common workflows and best practices: patterns for getting the most out of Claude Code
Settings: customize Claude Code for your workflow
Troubleshooting: solutions for common issues
code.claude.com: demos, pricing, and product details

Was this page helpful?

Yes
No
Quickstart
Ctrl+I
Claude Code Docs home page
x
linkedin

Company

Anthropic
Careers
Economic Futures
Research
News
Trust center
Transparency

Help and security

Availability
Status
Support center

Learn

Courses
MCP connectors
Customer stories
Engineering blog
Events
Powered by Claude
Service partners
Startups program

Terms and policies

Privacy choices
Privacy policy
Disclosure policy
Usage policy
Commercial terms
Consumer terms
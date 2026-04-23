# Documentation - Claude API Docs

**URL:** https://platform.claude.com/docs/en/home

---

Messages
Build
Admin
Models & pricing
Client SDKs
API Reference
English
Log in
Search...
⌘K
First steps
Intro to Claude
Quickstart
Building with Claude
Features overview
Using the Messages API
Claude API skill
Handling stop reasons
Model capabilities
Extended thinking
Adaptive thinking
Effort
Task budgets (beta)
Fast mode (beta: research preview)
Structured outputs
Citations
Streaming Messages
Batch processing
Search results
Streaming refusals
Multilingual support
Embeddings
Tools
Overview
How tool use works
Web search tool
Web fetch tool
Code execution tool
Advisor tool
Memory tool
Bash tool
Computer use tool
Text editor tool
Tool infrastructure
Tool reference
Tool search
Programmatic tool calling
Fine-grained tool streaming
Context management
Context windows
Compaction
Context editing
Prompt caching
Token counting
Working with files
Files API
PDF support
Images and vision
Skills
Overview
Quickstart
Best practices
Skills for enterprise
Skills in the API
MCP
Remote MCP servers
MCP connector
Prompt engineering
Overview
Prompting best practices
Console prompting tools
Test and evaluate
Define success and build evaluations
Using the Evaluation Tool in Console
Reducing latency
Strengthen guardrails
Reduce hallucinations
Increase output consistency
Mitigate jailbreaks
Reduce prompt leak
Resources
Glossary
Use cases
Release notes
Claude Platform
Console
Claude Platform
Start building
with Claude

Everything you need to integrate Claude into your applications. From first API call to production.

What do you want to build?
⌘K
Quickstart
Get API key
API reference
Python
TypeScript
Go
Java
Ruby
PHP
C#
cURL
CLI
import anthropic

client = anthropic.Anthropic()

message = client.messages.create(
  model="claude-opus-4-7",
  max_tokens=1024,
  messages=[{
    "role": "user",
    "content": "Hello, Claude"
  }]
)
print(message.content[0].text)
PLATFORM
Choose how you build

Pick the developer surface that matches your approach, and the infrastructure that fits your stack.

Messages

Direct model access. You construct every turn, manage conversation state, and write your own tool loop.

Quickstart
API reference
Client SDKs
Claude Managed Agents

Fully managed agent infrastructure. Deploy and manage autonomous agents in stateful sessions with persistent event history.

Quickstart
API reference
Define your agent
AWS Bedrock
Google Cloud Vertex AI
Microsoft Foundry
DEVELOPER JOURNEY
From idea to production

Follow the lifecycle or jump to what you need.

Messages
Claude Managed Agents
1
Get started
Quickstart
Get API key
Choose a model
Install an SDK
Try the Workbench
2
Build
Messages API
Extended thinking
Vision
Tool use
Web search
Code execution
Structured outputs
Prompt caching
Streaming
3
Evaluate & ship
Prompting best practices
Run evals
Batch testing
Safety & guardrails
Rate limits & errors
Cost optimization
4
Operate
Workspaces & admin
API key management
Usage monitoring
Model migration
MODELS
The Claude model family

Choose the right model for your use case.

MOST CAPABLE
Opus 4.7
claude-opus-4-7

Best for complex analysis, coding, and creative tasks requiring deep reasoning.

BEST BALANCE
Sonnet 4.6
claude-sonnet-4-6

Ideal balance of intelligence and speed for most production workloads.

FASTEST
Haiku 4.5
claude-haiku-4-5

Lightning-fast responses for high-volume, latency-sensitive applications.

RESOURCES
Keep learning
Courses
Interactive courses to master Claude.
Cookbook
Code samples and patterns.
Quickstarts
Deployable starter apps.
What's new
Latest features and updates.
Claude Code
An agentic coding assistant in your terminal.
Solutions
AI agents
Code modernization
Coding
Customer support
Education
Financial services
Government
Life sciences
Partners
Amazon Bedrock
Google Cloud's Vertex AI
Learn
Blog
Courses
Use cases
Connectors
Customer stories
Engineering at Anthropic
Events
Powered by Claude
Service partners
Startups program
Company
Anthropic
Careers
Economic Futures
Research
News
Responsible Scaling Policy
Security and compliance
Transparency
Help and security
Availability
Status
Support
Discord
Terms and policies
Privacy policy
Responsible disclosure policy
Terms of service: Commercial
Terms of service: Consumer
Usage policy
# OpenAI API Platform Documentation

**URL:** https://platform.openai.com/docs

---

Home
API
Codex
ChatGPT
Resources
Start searching
API Dashboard
Get started
Overview
Quickstart
Models
Pricing
SDKs and CLI
Latest: GPT-5.5
Prompt guidance
Core concepts
Text generation
Code generation
Images and vision
Audio and speech
Structured output
Function calling
Responses API
Using tools
Agents SDK
Overview
Quickstart
Agent definitions
Models and providers
Running agents
Sandbox agents
Orchestration
Guardrails
Results and state
Integrations and observability
Evaluate agent workflows
Voice agents
Agent Builder
Tools
Web search
MCP and Connectors
Skills
Shell
Computer use
File search and retrieval
Tool search
More tools
Run and scale
Conversation state
Background mode
Streaming
WebSocket mode
Webhooks
File inputs
Context management
Prompting
Reasoning
Evaluation
Getting started
Working with evals
Prompt optimizer
External models
Best practices
Realtime and audio
Overview
Voice agents
Live translation
Transcription
Speech generation
Realtime prompting guide
Connection methods
Realtime sessions
Model optimization
Optimization cycle
Fine-tuning
Graders
Specialized models
Image generation
Video generation
Deep research
Embeddings
Moderation
Going live
Production best practices
Deployment checklist
Latency optimization
Cost optimization
Accuracy optimization
Safety
Legacy APIs
Assistants API
Resources
Terms and policies
Changelog
Your data
Permissions
Rate limits
Admin APIs
Deprecations
MCP for deep research
Developer mode
ChatGPT Actions
API Platform
Developer quickstart

Make your first API request in minutes. Learn the basics of the OpenAI platform.

Get started
Create API key
javascript
1
2
3
4
5
6
7
8
9

import OpenAI from "openai";
const client = new OpenAI();

const response = await client.responses.create({
  model: "gpt-5.5",
  input: "Write a short bedtime story about a unicorn.",
});

console.log(response.output_text);

Build with the OpenAI API in Codex

The OpenAI Developers plugin enables Codex to connect to the OpenAI Platform, follow OpenAI API setup guidance, and create project API keys when your app needs one.

Install the plugin
Build paths
Responses API

Make direct model requests for text, structured output, tools, and multimodal workflows.

Start with Responses
Agents SDK

Build code-first agents that orchestrate tools, handoffs, approvals, tracing, and container-based execution.

Start with the Agents SDK
Models
Start with gpt-5.5 for complex reasoning and coding, or choose gpt-5.4-mini and gpt-5.4-nano for lower-latency, lower-cost workloads.
View all
GPT-5.5
New
A new class of intelligence for coding and professional work.
GPT-5.4
A more affordable model for coding and professional work.
GPT-5.4 mini
Our strongest mini model yet for coding, computer use, and subagents
Start building
Read and generate text
Use the API to prompt a model and generate text
Use a model's vision capabilities
Allow models to see and analyze images in your application
Generate images as output
Create images with GPT Image 2
Build apps with audio
Analyze, transcribe, and generate audio with API endpoints
Build agentic applications
Use the API to build agents that use tools and computers
Achieve complex tasks with reasoning
Use reasoning models to carry out complex tasks
Get structured data from models
Use Structured Outputs to get model responses that adhere to a JSON schema
Tailor to your use case
Adjust our models to perform specifically for your use case with fine-tuning, evals, and distillation
Help center
Frequently asked account and billing questions
Developer forum
Discuss topics with other developers
Cookbook
Open-source collection of examples and guides
Status
Check the status of OpenAI services
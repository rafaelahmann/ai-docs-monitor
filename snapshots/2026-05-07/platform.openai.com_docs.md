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
Libraries
Latest: GPT-5.4
Prompt guidance
Core concepts
Text generation
Code generation
Images and vision
Audio and speech
Structured output
Function calling
Responses API
Agents
Overview
Build agents
Deploy in your product
Optimize
Voice agents
Tools
Using tools
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
Realtime API
Overview
Connect
Usage
Model optimization
Optimization cycle
Fine-tuning
Graders
Specialized models
Image generation
Video generation
Text to speech
Speech to text
Deep research
Embeddings
Moderation
Going live
Production best practices
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
Deprecations
MCP for deep research
Developer mode
ChatGPT Actions
API Platform
Developer quickstart

Make your first API request in minutes. Learn the basics of the OpenAI platform.

Get started
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
  model: "gpt-5.4",
  input: "Write a short bedtime story about a unicorn.",
});

console.log(response.output_text);
Models
Start with gpt-5.4 for complex reasoning and coding, or choose gpt-5.4-mini and gpt-5.4-nano for lower-latency, lower-cost workloads.
View all
GPT-5.4
New
Best intelligence at scale for agentic, coding, and professional workflows
GPT-5.4 mini
New
Our strongest mini model yet for coding, computer use, and subagents
GPT-5.4 nano
New
Our cheapest GPT-5.4-class model for simple high-volume tasks
Start building
Read and generate text
Use the API to prompt a model and generate text
Use a model's vision capabilities
Allow models to see and analyze images in your application
Generate images as output
Create images with GPT Image 1
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
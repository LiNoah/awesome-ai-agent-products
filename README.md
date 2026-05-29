# Awesome AI Agent Products

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)](LICENSE)

A curated landscape of AI agent products, open-source projects, workflows, benchmarks, and product ideas for real-world use cases.

This list focuses on what agents can actually do for users: write code, operate browsers, research topics, automate workflows, manage personal tasks, and inspire new consumer products.

## Contents

- [Coding Agents](#coding-agents)
- [Browser Agents](#browser-agents)
- [Research Agents](#research-agents)
- [Workflow Automation](#workflow-automation)
- [Personal Productivity](#personal-productivity)
- [Consumer Life Agents](#consumer-life-agents)
- [Entertainment & Social Agents](#entertainment--social-agents)
- [Open-source Frameworks](#open-source-frameworks)
- [Evaluation & Benchmarks](#evaluation--benchmarks)
- [Product Ideas](#product-ideas)
- [Case Studies & Reports](#case-studies--reports)
- [Contributing](#contributing)

## Coding Agents

AI agents for software engineering, code editing, repository understanding, and end-to-end development workflows.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [OpenAI Codex](https://github.com/openai/codex) | Coding agent | Yes | Terminal-based coding workflows | Agentic coding assistant for reading, editing, and testing codebases. |
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) | Coding agent | No | Repository-scale software tasks | Command-line coding agent from Anthropic. |
| [Cursor](https://www.cursor.com/) | AI editor | No | IDE-native coding | Popular AI-first editor for pair programming and codebase Q&A. |
| [Aider](https://github.com/Aider-AI/aider) | Coding agent | Yes | Git-based pair programming | Edits files through chat and commits changes to Git. |
| [opencode](https://github.com/sst/opencode) | Coding agent | Yes | Terminal coding agents | Open-source agentic coding tool for the terminal. |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Coding agent platform | Yes | Autonomous software tasks | Formerly OpenDevin; runs agents in a development environment. |
| [Cline](https://github.com/cline/cline) | VS Code agent | Yes | IDE task automation | Planning, file editing, terminal use, and browser automation inside VS Code. |
| [Roo Code](https://github.com/RooVetGit/Roo-Code) | VS Code agent | Yes | Customizable coding workflows | Agentic coding assistant with multiple modes and tool integrations. |
| [Continue](https://github.com/continuedev/continue) | AI coding assistant | Yes | Custom IDE assistants | Open-source assistant for VS Code and JetBrains. |
| [Tabby](https://github.com/TabbyML/tabby) | Code assistant | Yes | Self-hosted code completion | Local/self-hosted alternative for code completion and chat. |
| [Devin](https://docs.devin.ai/) | AI software engineer | No | Managed software engineering tasks | Commercial autonomous software engineering agent from Cognition. |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) | Research coding agent | Yes | Fixing GitHub issues | Agent framework designed around software engineering benchmarks. |

## Browser Agents

Agents that operate web pages, fill forms, extract information, and complete browser-based tasks.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [Browser Use](https://github.com/browser-use/browser-use) | Browser automation agent | Yes | Web task automation | Lets LLMs control browsers through structured actions. |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Browser workflow agent | Yes | Form filling and repetitive web workflows | Combines browser automation with LLM reasoning. |
| [Stagehand](https://github.com/browserbase/stagehand) | Browser automation SDK | Yes | AI-assisted browser control | Natural-language browser automation built on Playwright. |
| [Browserbase](https://www.browserbase.com/) | Browser infrastructure | No | Hosted browser sessions | Infrastructure for running browser agents reliably. |
| [LaVague](https://github.com/lavague-ai/LaVague) | Web agent framework | Yes | Natural-language web automation | Framework for building agents that navigate websites. |
| [Agent S](https://github.com/simular-ai/Agent-S) | Computer/browser agent | Yes | GUI automation research | Agent for interacting with computers through GUI actions. |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Browser tool server | Yes | Tooling for agent browsers | Gives agents structured access to Playwright browser actions. |

## Research Agents

Products and projects for search, synthesis, report generation, and long-form research.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [Perplexity](https://www.perplexity.ai/) | Answer engine | No | Cited web research | Search-first product with source-backed answers. |
| [Genspark](https://www.genspark.ai/) | Research agent | No | AI-generated research pages | Produces synthesized pages and task-oriented outputs. |
| [Manus](https://manus.im/) | General agent | No | Multi-step digital tasks | General-purpose agent product for research and execution. |
| [Elicit](https://elicit.com/) | Research assistant | No | Literature review | Helps search, summarize, and extract evidence from papers. |
| [Consensus](https://consensus.app/) | Scientific search | No | Evidence-backed answers | Search engine for research papers and scientific claims. |
| [Open Deep Research](https://github.com/langchain-ai/open_deep_research) | Research agent | Yes | Long-form research workflows | Open-source deep research implementation from LangChain. |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | Research agent | Yes | Automated research reports | Generates research reports from web sources. |

## Workflow Automation

Visual builders and automation platforms for connecting agents to apps, APIs, and business processes.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [n8n](https://github.com/n8n-io/n8n) | Workflow automation | Source-available | Self-hosted automations | Visual workflows with code, integrations, and AI nodes. |
| [Zapier Agents](https://zapier.com/agents) | Agent automation | No | Business app automation | Agents connected to Zapier's integration ecosystem. |
| [Gumloop](https://www.gumloop.com/) | AI automation builder | No | No-code AI workflows | Drag-and-drop AI workflows for operations teams. |
| [Relevance AI](https://relevanceai.com/) | Agent workforce platform | No | Business process agents | Build and deploy agents for sales, support, and operations. |
| [Dify](https://github.com/langgenius/dify) | LLM app platform | Yes | Agent apps and RAG workflows | Open-source platform for building AI apps and agents. |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Low-code LLM builder | Yes | Visual LLM workflows | Drag-and-drop builder for LangChain-style apps. |
| [Langflow](https://github.com/langflow-ai/langflow) | Agent workflow builder | Yes | Visual agent prototyping | Python-based visual builder for AI workflows. |
| [Composio](https://github.com/ComposioHQ/composio) | Tool integration platform | Yes | Connecting agents to apps | Tooling layer for auth, actions, and integrations. |
| [Pipedream](https://pipedream.com/) | Workflow automation | No | Developer-friendly workflows | Connects APIs, scripts, triggers, and AI steps. |

## Personal Productivity

Agents and assistants for everyday knowledge work, meetings, notes, and personal workflows.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [ChatGPT Tasks](https://help.openai.com/en/articles/10291617-scheduled-tasks-in-chatgpt) | Assistant feature | No | Scheduled reminders and recurring prompts | Lets users schedule future assistant actions. |
| [Notion AI](https://www.notion.com/product/ai) | Workspace assistant | No | Docs, notes, and knowledge bases | AI built into a flexible workspace. |
| [Granola](https://www.granola.ai/) | Meeting notes | No | Human-readable meeting notes | AI notepad for meetings and follow-ups. |
| [Lindy](https://www.lindy.ai/) | Personal/business agent | No | Email, calendar, and operations | Agent platform for recurring personal and team tasks. |
| [Motion](https://www.usemotion.com/) | Scheduling assistant | No | Calendar and task planning | Uses AI to schedule tasks around meetings. |
| [Mem](https://get.mem.ai/) | AI notes | No | Personal knowledge management | AI-native notes and personal search. |
| [Superhuman AI](https://superhuman.com/ai) | Email assistant | No | Email triage and writing | AI features built into a productivity-focused email client. |

## Consumer Life Agents

Consumer-facing agent concepts and early products for everyday life tasks.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [DoNotPay](https://donotpay.com/) | Consumer rights assistant | No | Disputes and consumer paperwork | Early example of automating consumer advocacy workflows. |
| [Rocket Money](https://www.rocketmoney.com/) | Subscription finance app | No | Subscription cleanup | Not an agent-first product, but a strong reference for savings workflows. |
| [Cleo](https://web.meetcleo.com/) | Personal finance assistant | No | Budgeting and spending insights | Conversational finance assistant for consumers. |
| [Monarch Money](https://www.monarchmoney.com/) | Personal finance app | No | Household financial planning | Useful reference for agent-assisted family finance workflows. |
| [Ada](https://www.ada.cx/) | Customer service agent | No | Automated customer support | Reference for consumer-facing support automation. |
| [Intercom Fin](https://www.intercom.com/fin) | Support agent | No | Customer service resolution | AI support agent with handoff patterns. |

## Entertainment & Social Agents

Agents and AI products for companionship, storytelling, roleplay, creation, and social entertainment.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [Character.AI](https://character.ai/) | Character chat | No | Roleplay and companion chat | Large-scale consumer AI entertainment product. |
| [Replika](https://replika.com/) | AI companion | No | Personal companion experiences | Long-running AI companion product. |
| [Inworld](https://www.inworld.ai/) | Character engine | No | Game NPCs and interactive characters | Tools for building AI characters in games and media. |
| [Convai](https://www.convai.com/) | Game character AI | No | Voice NPCs and virtual worlds | Conversational characters for games and simulations. |
| [SillyTavern](https://github.com/SillyTavern/SillyTavern) | Chat frontend | Yes | Roleplay and character chat | Community-driven interface for character-based LLM chat. |
| [Poe](https://poe.com/) | Bot platform | No | Sharing and discovering bots | Consumer platform for using and creating AI bots. |

## Open-source Frameworks

Frameworks, runtimes, memory layers, and toolkits for building agent products.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [LangGraph](https://github.com/langchain-ai/langgraph) | Agent orchestration | Yes | Stateful multi-step agents | Graph-based framework for controllable agent workflows. |
| [AutoGen](https://github.com/microsoft/autogen) | Multi-agent framework | Yes | Multi-agent conversations | Framework for building agentic AI applications. |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Multi-agent framework | Yes | Role-based agent teams | Popular Python framework for collaborative agents. |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Agent platform | Yes | Autonomous agent experiments | Influential early autonomous agent project. |
| [smolagents](https://github.com/huggingface/smolagents) | Agent framework | Yes | Lightweight code agents | Hugging Face framework for simple powerful agents. |
| [Transformers Agents](https://huggingface.co/docs/transformers/agents) | Agent tooling | Yes | Model/tool experiments | Hugging Face agent tooling in the Transformers ecosystem. |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Data framework | Yes | RAG and knowledge agents | Connects agents to private and structured data. |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | AI orchestration SDK | Yes | Enterprise agent apps | SDK for planners, tools, memory, and connectors. |
| [Haystack](https://github.com/deepset-ai/haystack) | LLM framework | Yes | Search and RAG applications | Framework for production LLM pipelines. |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | Agent framework | Yes | Type-safe Python agents | Agent framework from the Pydantic team. |
| [Letta](https://github.com/letta-ai/letta) | Memory agent framework | Yes | Stateful agents with memory | Framework for agents that maintain long-term state. |
| [E2B](https://github.com/e2b-dev/E2B) | Agent sandbox | Yes | Secure code execution | Cloud sandboxes for AI agents and code interpreters. |
| [Ollama](https://github.com/ollama/ollama) | Local model runner | Yes | Local LLM agent stacks | Runs open models locally for private agent workflows. |

## Evaluation & Benchmarks

Benchmarks and environments for measuring agent performance in software, web, GUI, tool use, and reasoning tasks.

| Name | Type | Open Source | Best For | Notes |
|---|---|---:|---|---|
| [SWE-bench](https://github.com/SWE-bench/SWE-bench) | Software benchmark | Yes | GitHub issue resolution | Measures agents on real software engineering tasks. |
| [SWE-bench Verified](https://openai.com/index/introducing-swe-bench-verified/) | Software benchmark subset | Yes | Higher-quality SWE-bench evaluation | Human-validated subset for more reliable scoring. |
| [WebArena](https://webarena.dev/) | Web benchmark | Yes | Browser agents | Simulated websites for realistic web tasks. |
| [OSWorld](https://os-world.github.io/) | GUI benchmark | Yes | Computer-use agents | Evaluates agents on real desktop environments. |
| [AgentBench](https://github.com/THUDM/AgentBench) | Agent benchmark | Yes | General agent evaluation | Multi-environment benchmark for LLM agents. |
| [GAIA](https://huggingface.co/gaia-benchmark) | General assistant benchmark | Yes | Real-world reasoning tasks | Questions designed to test tool use and multi-step reasoning. |
| [tau-bench](https://github.com/sierra-research/tau-bench) | Tool-use benchmark | Yes | Conversational tool agents | Evaluates agents in dynamic customer-service-like tasks. |
| [MiniWoB++](https://github.com/Farama-Foundation/miniwob-plusplus) | Web interaction benchmark | Yes | Low-level browser control | Classic web interaction tasks for agents. |

## Product Ideas

Original product directions for builders exploring practical AI agent opportunities.

| Idea | Target User | User Pain | MVP | Monetization |
|---|---|---|---|---|
| Consumer dispute agent | Online shoppers and service consumers | Refunds, bad service, and complaint processes are confusing | Upload order screenshots and chat logs; generate evidence timeline and complaint text | Success fee, subscription, or legal-service referral |
| Subscription cleanup agent | Households and young professionals | Hidden recurring charges and unused memberships | Analyze payment screenshots or exported statements; produce cancellation checklist | Savings-based subscription |
| Rental handover tool | Renters and landlords | Deposit disputes caused by weak evidence | Guided move-in/move-out photo checklist with timestamped handover report | Freemium report exports |
| Elderly phone safety assistant | Adult children supporting parents | Scam texts, suspicious apps, and confusing phone prompts | Parent forwards screenshots; assistant flags risk and suggests action | Family safety subscription |
| Repair quote transparency | Home appliance and phone repair customers | Repair pricing is opaque and easy to overpay | Enter device, fault, and quote; compare with expected price ranges and checklist | Lead generation or premium reports |
| Interactive micro-drama agent | Short video fans and creators | Passive viewing has limited participation | Users vote or prompt the next plot turn; generate short script branches | Creator tools, ads, or virtual goods |
| Party game generator | Friend groups, students, and teams | Gathering games get repetitive | Generate room-based quizzes, truth-or-dare prompts, and scoring pages | Paid themed packs |
| Personal evidence box | Workers, renters, and consumers | Evidence is scattered across chats, files, receipts, and photos | Event folders that auto-build timelines and export evidence bundles | Subscription or per-export fee |
| Agent workflow template market | Operators and small businesses | Teams want agent automations but lack patterns | Curated templates for sales, support, research, and admin workflows | Template marketplace take rate |
| Build-your-own-agent learning lab | Developers and students | Agent tutorials are fragmented | Project-based lessons that rebuild memory, tools, browser use, and evals | Course, sponsorship, or hosted labs |

## Case Studies & Reports

Reports and references that help builders understand the agent market, capabilities, and adoption patterns.

| Name | Type | Best For | Notes |
|---|---|---|---|
| [Stanford AI Index](https://aiindex.stanford.edu/report/) | Annual report | AI adoption and market trends | Broad, data-rich report on AI progress and impact. |
| [State of AI Report](https://www.stateof.ai/) | Annual report | Industry and research landscape | Useful for tracking macro AI trends. |
| [Anthropic Economic Index](https://www.anthropic.com/economic-index) | Research index | AI usage patterns | Analysis of how AI is used across work tasks. |
| [OpenAI Research Index](https://openai.com/research/) | Research hub | Model and agent capability updates | Primary source for OpenAI research updates. |
| [LangChain Blog](https://blog.langchain.dev/) | Builder blog | Agent architecture patterns | Practical posts about agent engineering and production patterns. |
| [Sequoia AI Ascent](https://www.sequoiacap.com/article/ai-ascent-2025/) | Market perspective | Startup landscape | Investor perspective on AI-native companies. |

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

This repo values quality over volume. A good entry should help builders understand what the product/project does, who it helps, and why it matters.

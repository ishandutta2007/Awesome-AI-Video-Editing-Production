# Awesome-AI-Video-Editing-Production

## Top AI Tool Integration & Agent Tools Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Model Context Protocol (MCP) Servers & Gateways, OAuth Action Integrations, Function-Calling Toolkits, Agentic Workflow Connectors & Unified APIs*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Tool Integration & Agent Tools**. These tools connect AI agents and LLMs to hundreds of external SaaS apps, REST/GraphQL APIs, databases, browsers, and local developer environments—handling managed OAuth authentication, standardized MCP schemas, sandboxed tool execution, and framework-agnostic function calling.



**Examples** include Composio, Toolhouse, Zapier MCP, Pipedream Connect, LangChain Hub, Smithery, Trigger.dev, Superface, OpenTools, Apideck, and ComposioHQ/composio (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for open-source agent action SDKs (`Composio`, `Arcade`, `ACI.dev`), Model Context Protocol servers & gateways (`MCP Servers`, `FastMCP`, `Docker MCP Gateway`, `OpenAPI-to-MCP`), and self-hosted integration/workflow engines (`Activepieces`, `n8n`, `Trigger.dev`) — ideal for AI agent engineers, platform architects, and builders equipping agents with reliable real-world actions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Composio Cloud](https://composio.dev)**  

  Managed tool-calling and integration platform giving AI agents authenticated access to 250+ apps (GitHub, Slack, Linear, Notion, Gmail) with managed OAuth, SOC2 compliance, and native MCP/LangChain/CrewAI SDKs.



- **[Pipedream Connect](https://pipedream.com)**  

  Developer platform embedding 2,500+ API integrations, managed user OAuth, and pre-built MCP servers directly into AI agents and SaaS applications.



- **[Zapier MCP & AI Actions](https://zapier.com)**  

  Cloud integration platform exposing 7,000+ apps and 30,000+ actions to AI agents via a single hosted Model Context Protocol (MCP) endpoint without manual API plumbing.



- **[Smithery](https://smithery.ai)**  

  Cloud registry and hosted runtime for discovering, deploying, and connecting Model Context Protocol (MCP) servers to Claude, Cursor, Windsurf, and custom agents.



- **[Toolhouse](https://toolhouse.ai)**  

  Cloud function-calling and agent tool infrastructure providing a plug-and-play SDK of pre-hosted tools (web search, code execution, scraping, email, memory) across major LLM providers.



- **[Trigger.dev Cloud](https://trigger.dev)**  

  Managed background-job and durable AI workflow platform allowing agents to execute long-running tasks, API integrations, and human-in-the-loop waits without serverless timeouts.



- **[Apideck](https://apideck.com)**  

  Real-time Unified API platform aggregating CRM, ERP, accounting, HRIS, and file-storage connectors behind normalized schemas ideal for enterprise AI agent tool integration.



- **[Superface](https://superface.ai)**  

  AI-native API integration layer enabling agents and developers to discover, connect, and execute third-party REST/OpenAPI actions dynamically via natural-language intent.



- **[OpenTools](https://opentools.com)**  

  Hosted developer platform and registry for discovering, testing, and invoking standardized API tools and MCP servers inside LLM and agent pipelines.



- **[LangSmith Hub (LangChain)](https://langchain.com)**  

  Cloud registry and playground for sharing, versioning, and pulling community-curated prompt templates, tool schemas, and runnable agent chains.





## Open-Source GitHub Projects



- **[Composio (`ComposioHQ/composio`)](https://github.com)**  

  Flagship open-source (`Apache-2.0`) agent toolset and integration SDK equipping LLMs with 250+ production-ready tools, managed authentication, triggers, and native support for MCP, OpenAI, Anthropic, LangGraph, and CrewAI.



- **[Official Model Context Protocol Servers (`modelcontextprotocol/servers`)](https://github.com)**  

  Foundational open-source (`MIT`) reference collection of MCP servers from Anthropic and the community connecting AI agents to Git, GitHub, PostgreSQL, SQLite, Filesystem, Slack, Puppeteer, and Google Drive.



- **[FastMCP (`jlowin/fastmcp`)](https://github.com)**  

  Leading open-source (`Apache-2.0`) Pythonic framework for rapidly building, testing, proxying, and deploying production Model Context Protocol (MCP) servers and clients with minimal boilerplate.



- **[ACI.dev (`aipotheosis-labs/aci`)](https://github.com)**  

  Open-source (`Apache-2.0`) AI-Computer Interface and agent tool-calling platform providing multi-tenant OAuth authentication, granular permission boundaries, and unified MCP/function-calling access to 600+ tools.



- **[Activepieces (`activepieces/activepieces`)](https://github.com)**  

  Open-source (`MIT`) AI-first workflow automation platform and Zapier alternative featuring 280+ pre-built integration pieces, human-in-the-loop approvals, and native MCP server exposure for every flow.



- **[n8n (`n8n-io/n8n`)](https://github.com)**  

  Fair-code (`Sustainable Use License`) self-hostable workflow automation powerhouse offering 400+ app integrations, native LangChain AI agent nodes, and built-in MCP Server/Client triggers.



- **[Trigger.dev (`triggerdotdev/trigger.dev`)](https://github.com)**  

  Open-source (`Apache-2.0`) TypeScript background jobs and durable AI agent task runner enabling long-running tool integrations, retries, and webhook orchestration self-hosted via Docker.



- **[Docker MCP Gateway & Catalog (`docker/mcp-gateway`)](https://github.com)**  

  Open-source (`Apache-2.0`) containerized MCP server gateway from Docker that isolates, orchestrates, and aggregates multiple MCP tool servers behind a single secure endpoint.



- **[MetaMCP (`metatool-ai/metamcp`)](https://github.com)**  

  Open-source (`AGPL-3.0`) MCP aggregator and middleware proxy uniting multiple STDIO/SSE MCP servers into unified tool namespaces with dynamic tool filtering and GUI management.



- **[OpenAPI-to-MCP / FastAPI-MCP (`tadata-org/fastapi_mcp`)](https://github.com)**  

  Zero-configuration open-source (`MIT`) tool that automatically exposes existing FastAPI and OpenAPI REST endpoints as native Model Context Protocol (MCP) tools preserving schemas and auth.



- **[LangChain Community Tools (`langchain-ai/langchain`)](https://github.com)**  

  Massive open-source (`MIT`) ecosystem of hundreds of pre-built Python/JS agent tools spanning Wikipedia, ArXiv, Tavily, SQL databases, Python REPLs, and cloud APIs.



- **[LlamaHub (`run-llama/llama_index`)](https://github.com)**  

  Open-source (`MIT`) registry of 160+ data loaders and agent tool specs (`ToolSpec`) bridging Notion, Slack, Jira, Gmail, Salesforce, and SQL databases into LlamaIndex agents.



- **[CAMEL-AI Toolkits (`camel-ai/camel`)](https://github.com)**  

  Comprehensive open-source (`Apache-2.0`) suite of modular agent toolkits covering browser automation, code execution, GitHub, Slack, Notion, Google Scholar, and financial APIs.



- **[Phidata / Agno (`agno-agi/agno`)](https://github.com)**  

  High-performance open-source (`MPL-2.0`) multi-agent framework bundled with 80+ pre-built Python toolkits (`YFinance`, `DuckDuckGo`, `Jira`, `Docker`, `SQL`, `MCP`) and structured outputs.



- **[E2B Code Interpreter (`e2b-dev/code-interpreter`)](https://github.com)**  

  Open-source (`Apache-2.0`) sandboxed cloud/self-hosted runtime equipping AI agents with a secure Python, JavaScript, and Bash code-execution tool inside isolated MicroVMs.



- **[Playwright MCP (`microsoft/playwright-mcp`)](https://github.com)**  

  Official open-source (`Apache-2.0`) MCP server from Microsoft giving AI agents deterministic web-browsing, form-filling, and scraping tools via accessibility-tree snapshots.



### Additional Strong Open-Source Options



- **[Context7 MCP (`upstash/context7`)](https://github.com)** and **[Serena (`oraios/serena`)](https://github.com)** for open-source developer-focused MCP servers injecting live library documentation and Language Server Protocol (`LSP`) symbol tools.

- **[mcp-use (`mcp-use/mcp-use`)](https://github.com)** for an open-source (`MIT`) Python and TypeScript client library connecting any LangChain-compatible LLM to multiple MCP servers in a few lines of code.

- **[Gorilla / Berkeley Function Calling Leaderboard (`ShishirPatil/gorilla`)](https://github.com)** for open-source function-calling benchmarks (`BFCL`) and open-weight tool-use models (`Gorilla OpenFunctions`).

- **[Nango (`NangoHQ/nango`)](https://github.com)** for an open-source (`Elastic-2.0`) unified OAuth and API sync infrastructure powering custom agent tool integrations across 250+ APIs.

- **[Windmill (`windmill-labs/windmill`)](https://github.com)** for a high-speed self-hosted developer workflow engine turning Python, TypeScript, Go, and Bash scripts into instant API/MCP agent tools.

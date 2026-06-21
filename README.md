# Its Harness

Open-source visual canvas for production AI agent harnesses. Draw workflows on a canvas, compile to any major AI framework, trace every decision. Apache 2.0.

**Live site:** https://buildaharness.com  
**Repository:** https://github.com/3IVIS/buildaharness

## What ships today (v0.8.0)

- Visual canvas with 14 node types
- FlowSpec v0.2.0 — open, portable JSON format
- 4 framework adapters: LangGraph, CrewAI, Mastra, Microsoft Agent Framework
- Langfuse observability across all 4 runtimes
- HITL pause/resume, REST/MCP/A2A deployment
- 9 services, single `docker compose up`

## Supported runtimes

- LangGraph (Python / JS)
- CrewAI (Python)
- Mastra (TypeScript)
- Microsoft Agent Framework (C# / Python / Java)
- A2A protocol for framework-agnostic invocation

## License

Apache 2.0

## Local preview

This repo is a static site. Open `index.html` in a browser or serve the root with any static server.

```sh
# Python 3
python3 -m http.server 8080
# or Node
npx serve .
```

## Contributing

See the **Get Involved** section on the site, or open a GitHub Discussion at https://github.com/3IVIS/buildaharness/discussions.

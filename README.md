# Its Harness

Open-source visual builder for production AI agent harnesses. One canvas, one runtime-neutral FlowSpec, four runtime adapters plus A2A.

**Live site:** https://itsharness.com

## Status

In design stage (Phase 1 of 5). The FlowSpec v0.1.0 is frozen and a 36-question public design log is open. Public release is targeted for week 20.

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
python -m http.server 8000
# or Node
npx serve .
```

## GitHub Pages

The site publishes from the repository root. `.nojekyll` is present to disable Jekyll processing. Update the `<link rel="canonical">` and `og:url` meta tags in `index.html` once a custom domain is wired up.

## Contributing

See the **Get Involved** section on the site, or open a GitHub Discussion.

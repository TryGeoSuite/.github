<p align="center"><img src="https://trygeosuite.it/logo.svg" alt="GeoSuite" width="96"></p>

<h1 align="center">GeoSuite</h1>

<p align="center">
  <em>Open-source CLIs for Generative Engine Optimization (GEO).</em><br>
  <em>Measure how AI engines see your site — from the terminal.</em>
</p>

<p align="center">
  <a href="https://trygeosuite.it">trygeosuite.it</a> ·
  <a href="https://www.npmjs.com/org/geosuite">npm</a>
</p>

---

## Why GEO

Two thirds of brand "search" traffic is now mediated by an LLM at some point — ChatGPT, Claude, Perplexity, Gemini, Copilot, DuckAssist. The bots that feed those systems are not Googlebot, they don't behave like Googlebot, and the rules you write for them belong in `robots.txt` next to (or instead of) the rules you wrote a decade ago.

We build small, boring-but-correct tools to make AI visibility **measurable**.

## Tools

| Repo | What it does | npm |
|---|---|---|
| [`ai-crawler-bots`](https://github.com/TryGeoSuite/ai-crawler-bots) | Curated AI bot user-agents + `robots.txt` verdict, edge vs origin block detection | [`@geosuite/ai-crawler-bots`](https://www.npmjs.com/package/@geosuite/ai-crawler-bots) |
| [`schema-templates`](https://github.com/TryGeoSuite/schema-templates) | Copy-paste schema.org JSON-LD templates + offline validator | [`@geosuite/schema-templates`](https://www.npmjs.com/package/@geosuite/schema-templates) |
| [`llms-txt-generator`](https://github.com/TryGeoSuite/llms-txt-generator) | `sitemap.xml` → `llms.txt` ([llmstxt.org](https://llmstxt.org/)) | [`@geosuite/llms-txt-generator`](https://www.npmjs.com/package/@geosuite/llms-txt-generator) |
| [`sitemap-builder`](https://github.com/TryGeoSuite/sitemap-builder) | Crawl a site, emit a valid `sitemap.xml` | [`@geosuite/sitemap-builder`](https://www.npmjs.com/package/@geosuite/sitemap-builder) |

All zero-runtime-dependency. Node 20+. MIT.

## Principles

- **Boring-but-correct** — no novelty, no LLM where regex suffices, no headless browser where HTTP+regex suffices.
- **One tool, one job** — composable via stdout/JSON.
- **Privacy by default** — `--ai` modes ship structured payloads only, never raw HTML.
- **Verifiable sources** — every bot UA links to operator docs, not third-party SEO blogs.

## Hosted

Same checks, with history, alerts, and CTAs wired into your content pipeline → [trygeosuite.it](https://trygeosuite.it).

## Maintainer

Founded and maintained by [Matteo Perino](https://github.com/matte97p) — [matte97.p@gmail.com](mailto:matte97.p@gmail.com).

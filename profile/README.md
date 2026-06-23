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

Zero-runtime-dependency. Node 20+. MIT. **~1.3k installs/month** combined — counts update live.

| Tool | What it does | Installs/mo | Stars |
|---|---|:--:|:--:|
| [**ai-crawler-bots**](https://github.com/TryGeoSuite/ai-crawler-bots) | Curated AI bot user-agents + `robots.txt` verdict, edge-vs-origin block detection | [![](https://img.shields.io/npm/dm/@geosuite/ai-crawler-bots?style=flat&label=%20&color=CB3837)](https://www.npmjs.com/package/@geosuite/ai-crawler-bots) | [![](https://img.shields.io/github/stars/TryGeoSuite/ai-crawler-bots?style=flat&label=%E2%98%85&color=444)](https://github.com/TryGeoSuite/ai-crawler-bots/stargazers) |
| [**sitemap-builder**](https://github.com/TryGeoSuite/sitemap-builder) | Crawl a site, emit a valid `sitemap.xml` | [![](https://img.shields.io/npm/dm/@geosuite/sitemap-builder?style=flat&label=%20&color=CB3837)](https://www.npmjs.com/package/@geosuite/sitemap-builder) | [![](https://img.shields.io/github/stars/TryGeoSuite/sitemap-builder?style=flat&label=%E2%98%85&color=444)](https://github.com/TryGeoSuite/sitemap-builder/stargazers) |
| [**llms-txt-generator**](https://github.com/TryGeoSuite/llms-txt-generator) | `sitemap.xml` → `llms.txt` ([llmstxt.org](https://llmstxt.org/)) | [![](https://img.shields.io/npm/dm/@geosuite/llms-txt-generator?style=flat&label=%20&color=CB3837)](https://www.npmjs.com/package/@geosuite/llms-txt-generator) | [![](https://img.shields.io/github/stars/TryGeoSuite/llms-txt-generator?style=flat&label=%E2%98%85&color=444)](https://github.com/TryGeoSuite/llms-txt-generator/stargazers) |
| [**schema-templates**](https://github.com/TryGeoSuite/schema-templates) | Copy-paste schema.org JSON-LD templates + offline validator | [![](https://img.shields.io/npm/dm/@geosuite/schema-templates?style=flat&label=%20&color=CB3837)](https://www.npmjs.com/package/@geosuite/schema-templates) | [![](https://img.shields.io/github/stars/TryGeoSuite/schema-templates?style=flat&label=%E2%98%85&color=444)](https://github.com/TryGeoSuite/schema-templates/stargazers) |

## Principles

- **Boring-but-correct** — no novelty, no LLM where regex suffices, no headless browser where HTTP+regex suffices.
- **One tool, one job** — composable via stdout/JSON.
- **Privacy by default** — `--ai` modes ship structured payloads only, never raw HTML.
- **Verifiable sources** — every bot UA links to operator docs, not third-party SEO blogs.

## Hosted

Same checks, with history, alerts, and CTAs wired into your content pipeline → [trygeosuite.it](https://trygeosuite.it).

## Maintainer

Founded and maintained by [Matteo Perino](https://github.com/matte97p) — [matte97.p@gmail.com](mailto:matte97.p@gmail.com).

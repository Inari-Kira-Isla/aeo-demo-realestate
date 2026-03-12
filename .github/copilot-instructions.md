# aeo-demo-realestate

## Project
AEO (AI Engine Optimization) demo template for realestate industry — HTML with Schema.org, llms.txt, FAQ, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements (`<article>`, `<section>`, `<nav>`, `<aside>`)
- Include JSON-LD Schema.org markup for rich snippets
- Add `llms.txt` endpoint for AI crawler compatibility
- Use `<script type="application/ld+json">` for structured data
- Place FAQ content in `<details>`/`<summary>` or structured list format
- Add `data-ai-friendly` attributes to key content sections
- Keep all markup in a single HTML file for simplicity

## Naming
- Use kebab-case for file names: `realestate-aeo.html`, `llms.txt`
- Schema `@id` values: `https://example.com/property-123`
- Use descriptive class names: `.ai-summary`, `.schema-property`, `.faq-item`

## Architecture
- Single HTML file with embedded CSS/JS
- JSON-LD blocks in `<head>` for SEO/AI crawlers
- Human-readable content in `<body>`
- Include meta tags for AI agents: `<meta name="ai-optimized" content="true">`

## Commands
- No build commands — pure static HTML
- Validate Schema.org markup with Google's Rich Results Test
- Test llms.txt accessibility at `/llms.txt`

## Do Not
- Do not add client-side JavaScript that hides content from AI
- Do not use `<iframe>` or blocking scripts that prevent AI indexing
- Do not omit JSON-LD structured data
- Do not use non-semantic `<div>` tags where semantic elements exist
- Do not create multi-page SPA — keep it simple and crawlable
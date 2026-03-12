# aeo-demo-realestate

## Overview
AEO (AI Engine Optimization) demo template for the realestate industry. Demonstrates AI-friendly web markup using Schema.org structured data, llms.txt for AI crawler compatibility, and FAQ schema implementation to improve visibility in AI-generated search results.

## Tech Stack
- HTML5
- Schema.org (JSON-LD)
- llms.txt

## Architecture
- Static HTML template
- Single-page or multi-page structure focused on realestate content
- Structured data embedded via JSON-LD script tags

## Commands
No build commands required. This is a static HTML project.
- Serve locally: Use any static file server (e.g., `python3 -m http.server`, `npx serve`, or VS Code Live Server)

## Coding Style
- Use semantic HTML5 elements (`<article>`, `<section>`, `<header>`, `<footer>`)
- Include comprehensive Schema.org JSON-LD for rich results
- Implement llms.txt for AI crawler discovery
- Keep FAQ content in structured format

## Important Rules
- Always include valid Schema.org structured data for realestate entities
- Ensure llms.txt is accessible at the root directory
- Avoid blocking AI crawlers in robots.txt
- Maintain clean, well-commented HTML for AI parsing clarity
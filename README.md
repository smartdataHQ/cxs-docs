# ContextSuite Documentation

The official documentation site for **ContextSuite** — an AI-powered eCommerce platform for mid-market and enterprise retailers delivering dynamic pricing, AI sales agents, real-time analytics, and connected intelligence.

## Overview

This site documents the **Semantic Events** system, an advanced event tracking and analytics framework that extends the standard Segment.com event schema with rich context, classification, sentiment analysis, and enriched metadata for operational insights.

### Key Documentation Sections

- **Semantic Events** — Introduction, best practices, and getting started guides
- **Core Functions** — API reference for `page`, `screen`, `identify`, `group`, `alias`, and `track`
- **Event Bible** — Industry-specific event templates covering 12+ verticals (Travel & Hospitality, Automotive, Food & Dining, Real Estate, and more)
- **Event Schema** — Comprehensive schema reference including context, classification, commerce, enrichments, sentiment, and more

## Tech Stack

- [Next.js](https://nextjs.org/) — React framework
- [Markdoc](https://markdoc.dev/) — Markdown-based documentation authoring
- [TypeScript](https://www.typescriptlang.org/)
- [PrismJS](https://prismjs.com/) — Syntax highlighting

## Getting Started

```bash
# Install dependencies
npm install

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the docs locally.

## Project Structure

```
pages/              # Markdoc documentation pages
  docs/
    semantic-events/
      bible/        # Industry-specific event templates
      schema/       # Detailed schema reference
components/         # React components (navigation, code blocks, callouts, tabs)
markdoc/            # Custom Markdoc tags, nodes, and functions
public/             # Static assets and JSON schema
```

## License

Proprietary — ContextSuite / SmartData HQ

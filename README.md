# How AI Search Chooses Its Sources: The Scrolling Story

A scroll-driven visual story about AI search. Every dot on screen is a web page. As you scroll, you watch thousands of pages move through the eight stages AI search runs before it cites anything: decide, fan-out, retrieve, fetch, rerank, pack, generate and cite. Most of them drop out long before the end.

**Live demo:** https://jourdanrombough.github.io/ai-search-scroll-story/
**Companion explainer:** https://optimizationtheory.com/ai-citation-trace/

## What it shows

- **Decide:** whether the model searches the web at all or answers from memory
- **Fan-out:** how one prompt becomes several sub-queries, each searched on its own
- **Retrieve and fetch:** why pages that never get read fall out (JS-only pages, blocked bots, slow servers)
- **Rerank and pack:** how passages, not pages, compete for a small context budget
- **Generate and cite:** which few sources make it into the final answer
- An "SEO move" at every stage: the practical action that keeps a page in the running

## Built with

Single-file HTML, CSS and vanilla JavaScript with a canvas particle system driven by scroll position. No frameworks and no build step. Open `index.html` in a browser to run it locally.

## Author

Built by **Jourdan Rombough**, SEO and AI search strategist at [Optimization Theory](https://optimizationtheory.com).
[LinkedIn](https://www.linkedin.com/in/jourdanrombough) · [optimizationtheory.com](https://optimizationtheory.com)

© Jourdan Rombough / Optimization Theory. All rights reserved.

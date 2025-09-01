
# Africa Digital Protocol — One-Hub Stack (Option B)

This repository powers one main site (AfricaDigitalProtocol.com) with two built-in sections:
- /edge-monitor → Africa Edge Monitor (IXPs, DCs, cables, outages)
- /knowledge-graph → Africa Knowledge Graph (datasets)

The other domains should redirect:
- AfricaEdgeMonitor.com  → https://AfricaDigitalProtocol.com/edge-monitor
- AfricaKnowledgeGraph.com → https://AfricaDigitalProtocol.com/knowledge-graph

## Structure
- content/briefs        → newsletter posts
- content/changelogs    → infra updates
- content/datasets      → published CSV summaries
- data/                 → CSV sources (sponsors, facilities, cables, outages, languages, institutions)
- automation/prompts    → AI prompts + sources.txt
- site/                 → static site (index + sections)
- exports/              → paid PDFs + media kits

## Publish
- GitHub Pages: set Pages to build from branch `main` and root `/site`
- WordPress: copy `site/` content into WP pages

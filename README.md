# CasperHire — Wireframe Assets

Low-fidelity wireframes and user flow diagrams for **CasperHire**, an AI-powered internal recruiting platform concept. These assets were produced as part of a product management assessment, demonstrating AI-first rapid prototyping.

## What's Here

```
├── assets/
│   └── wireframes/          # 7 user flow diagrams (HTML/SVG)
│       ├── flowchart-1-role-configuration.html
│       ├── flowchart-2-resume-ingestion.html
│       ├── flowchart-3-structural-parsing.html
│       ├── flowchart-4-llm-scoring.html
│       ├── flowchart-5-shortlist-review.html
│       ├── flowchart-6-screening-analytics.html
│       └── flowchart-7-crm-handoff.html
└── wireframe-prototype.html  # Interactive clickable prototype
```

### Flow Diagrams

Seven vertical flowcharts covering the resume screening feature pipeline — one per work breakdown section. Built with standard flowchart conventions (terminators, process blocks, decision diamonds, input parallelograms) and color-coded by node type.

### Interactive Prototype

A single self-contained HTML file with 5 navigable views:

- **Dashboard** — KPI cards, pipeline funnel, activity feed
- **Shortlist Review** — Ranked candidate table with score overrides, AI rationale, status management
- **Candidate Profile** — Parsed resume data, scoring breakdown, activity log, manual edit history
- **Roles List** — Active/draft/paused roles with screening stats
- **Role Detail** — Requirements, rubric weight visualization, deal-breaker rules

**How to navigate:**

1. Open `wireframe-prototype.html` in any browser — you'll land on the **Dashboard**.
2. Click **Shortlist** in the sidebar → candidate table. Click the **View** button on **Maria Chen** (top row) to open her profile card.
3. Click **Roles** in the sidebar → roles table. Click the **View** button on **Sr. Backend Engineer** to see the full role configuration with rubric weights and deal-breakers.
4. Each detail view has a **← Back** button in the top bar to return to its parent list.

## How These Were Built

All artifacts were collaboratively built using Claude as a coding partner, going from user stories to working prototypes in a single session. The flow diagrams and prototype are intentionally lo-fi (grayscale, wireframe aesthetic) — the focus is on user flows, states, and data relationships, not visual polish.

## License

MIT — see [LICENSE](LICENSE).

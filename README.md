## Product leader and AI-native builder

AI, data, and UX work as one system. Trust starts with meeting users in their workflow and giving them real value. It holds when measured by evals for its use case, and the underlying services, data contracts, and permissions are designed in from the start.


## Currently building: Project Meridian

Finding local events means searching across a multitude of disconnected sources, city and venue sites, tourism boards, social media, and ticketing platforms. Project Meridian pulls thousands of events a month into one feed for discovery and planning, filterable and searchable down to your area. It personalizes to the categories you follow and grows over time. A consumer iOS app launching July 2026, starting in the Utah market. Calling it Project Meridian until launch.

I architected and built two systems end to end through agentic engineering, one feeding the other:

- **A headless data product:** Python ingestion across APIs, feeds, and structured scraping, enriched by an AI layer and normalized into a canonical Postgres schema. Built to power both the app and a B2B API.
- **The app:** a React Native and TypeScript iOS client, built on a design system of tokens and atomic components, with auth flows and accessibility built in.

Aggregating this many sources and events is a data-quality and AI-evals problem before it becomes a product. I built a five-stage deterministic dedup pass that collapses the same event arriving from different sources, then I enrich and classify all records with AI using a Claude API.

Before launch I hand-labeled a ground-truth set of [157] event pairs and tuned for precision over recall, because a duplicate that reaches a user costs more than an event we miss. On that set it holds 100% precision at roughly 68% recall, an F1 of 0.81. I brought the same discovery and spec discipline I use on enterprise products, and built it myself orchestrating 14+ AI agent personas as multi-disciplinary review and development pods.

Coming the week of June 22, 2026: The Project Meridian architecture guide. It walks the full design and the evals behind the build.

## About

I've led portfolios of revenue-generating AI and data products in regulated B2B SaaS. Most recently at MasterControl I launched the company's first GA AI product, a predictive scoring model in a human-in-the-loop workflow surfaced through admin dashboards and in-app notifications. Before Gen AI, my work has spanned ML and data-science products fueling personalization, risk scoring, and forecasting.

## How I work

I work persona-first and outcome-first. My work runs from product strategy through commercialization. I bring the same product craft to AI-native building, across cross-functional teams.

## Contact

[camilo@cccollective.dev](mailto:camilo@cccollective.dev) · [LinkedIn](https://www.linkedin.com/in/camiloforero1/)

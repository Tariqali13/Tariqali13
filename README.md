# Hi, I'm Tariq Ali

Senior Full-Stack Software Engineer, 8+ years building SaaS, ticketing, e-commerce and
AI-enabled products for international teams. Most recently on a large event-ticketing
platform: checkout and payment flows, GraphQL migration, observability and production
rollouts across 20+ repositories.

Based in Lahore, Pakistan · open to remote roles and relocation.

## Featured projects

My employer and client work lives in private repositories, so these projects rebuild the
kinds of problems I work on, in the open, with tests, CI and the trade-offs written down.

### [Onsale](https://github.com/Tariqali13/onsale) — ticket onsale engine under a thundering herd · [live demo](https://onsalerender.netlify.app)
A virtual waiting room, all-or-nothing seat holds and idempotent checkout, with a database
constraint as the final guarantee against double-selling. Load-tested with k6: 2,000
simulated buyers, 696 seats sold in ~20 s, **0 double-sold seats** (audited in Postgres),
0 unexpected errors. CI re-runs the audit on every push.
`TypeScript` `Fastify` `Redis + Lua` `PostgreSQL` `React` `k6` `Prometheus` `Grafana`

### [VoiceBrief](https://github.com/Tariqali13/voicebrief) — meeting notes you can verify · [live demo](https://voicebrief.onrender.com)
Record a meeting and get decisions, action items and open questions, each linked to the
exact transcript line it came from. Ask questions across all meetings and get cited
answers. Grounding checks drop unsupported items, transcripts are fenced against prompt
injection, and an evaluation harness scores the pipeline against hand-labelled meetings.
`Next.js 16` `TypeScript` `Whisper` `LLM structured output` `Embeddings / RAG` `Postgres`

### [MediaVault](https://github.com/Tariqali13/MediaVault) — multi-tenant media library · [live demo](https://media-vault-tariqali.netlify.app)
Team asset library with tenant isolation enforced by Postgres row-level security, direct-to-storage
signed uploads with atomic quota reservation, a background worker that verifies file types
and renders thumbnails, and one role/permission matrix shared by API and UI.
`TypeScript` `Node.js` `PostgreSQL RLS` `S3 / MinIO` `Background jobs` `React`

### Also
- [3D Geospatial & CAD Viewer](https://github.com/Tariqali13/3d-project-demo) — browser rendering of DXF/LandXML-style geometry with Three.js, measurements and elevation profiles.
- [ShelfSync](https://github.com/Tariqali13/ShelfSync) — offline-aware inventory and operations workspace.

## Toolkit

- **Frontend:** React, Next.js, TypeScript, React Query, Zustand, Redux, accessibility (WCAG)
- **Backend:** Node.js, Fastify, NestJS, Express, GraphQL / Apollo, REST, Stripe
- **Data & cloud:** PostgreSQL, MongoDB, Redis, AWS (S3, Lambda, Rekognition, CloudFront), Docker
- **Quality & delivery:** Vitest, Jest, React Testing Library, Nightwatch, k6, GitHub Actions, Prometheus, Grafana
- **AI:** LLM APIs, structured output, retrieval-augmented generation, evaluation harnesses

## Connect

- Portfolio: [tariqali.dev](https://tariqali.dev)
- LinkedIn: [Tariq Ali](https://www.linkedin.com/in/tariq-ali-116678156/)
- Email: tariqali99.ta@gmail.com

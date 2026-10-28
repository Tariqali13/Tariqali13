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

### [Groundwork](https://github.com/Tariqali13/3d-groundwork) — survey and CAD data in the browser · [live demo](https://groundwork-3d.onrender.com)
Open LandXML terrain and DXF site plans, then measure distances, areas, long sections,
stockpile volumes and cut/fill against a design, all client-side. Float64 world coordinates
with a local GPU origin keep millimetre precision; plane volumes are exact by triangle
clipping; a grid TIN index answers a million elevation lookups in 0.2 s; analysis runs in
a Web Worker. 40 tests check results against answers known in advance.
`TypeScript` `three.js` `Web Workers` `React` `LandXML` `DXF` `Vitest`

### [ShelfSync](https://github.com/Tariqali13/ShelfSync) — offline-first point of sale · [live demo](https://shelf-sync.netlify.app)
Tills keep selling with no connection and sync safely when it returns, even when two offline
tills both sold the last item. Sales go to an IndexedDB outbox first and sync as deltas; sync is
idempotent and gap-free (per-store advisory lock); oversells that already happened are kept and
flagged for a recount. A chaos test with lost, duplicated and dropped requests converges on 200 seeds.
`React` `TypeScript` `IndexedDB` `Express` `PostgreSQL` `Netlify Functions` `Vitest`

## Toolkit

- **Frontend:** React, Next.js, TypeScript, React Query, Zustand, Redux, accessibility (WCAG)
- **Backend:** Node.js, Fastify, NestJS, Express, GraphQL / Apollo, REST, Stripe
- **Data & cloud:** PostgreSQL, MongoDB, Redis, AWS (S3, Lambda, Rekognition, CloudFront), Docker
- **Quality & delivery:** Vitest, Jest, React Testing Library, Nightwatch, k6, GitHub Actions, Prometheus, Grafana
- **AI:** LLM APIs, structured output, retrieval-augmented generation, evaluation harnesses

## Connect

- Portfolio: [tariqali.dev](https://tariqali.dev)
- LinkedIn: [Tariq Ali](https://www.linkedin.com/in/tariq-ali-116678156/)
- Email: Tariqali.edu.dev@gmail.com
- Email2: tariqali99.ta@gmail.com

# Arc & Anchor

We build small, focused tools for engineers — code review, manufacturing, and the kind of automation that earns trust by being correct, not by being loud.

**Web:** [arcanchor.com](https://arcanchor.com) · [`arc-and-anchor-website`](https://github.com/Arc-and-Anchor/arc-and-anchor-website)

## Products

### [Sigilix](https://sigilix.ai) — `sigilix.ai`

A multi-agent AI code review GitHub App. Four domain specialists (architecture, security, performance, semantics) plus a synthesizer that produces one authoritative review per pull request.

- **Marketing:** [sigilix.ai](https://sigilix.ai)
- **Docs:** [docs.sigilix.ai](https://docs.sigilix.ai)
- **App:** [app.sigilix.ai](https://app.sigilix.ai)
- **Public repos:** [`sigilix-marketing`](https://github.com/Arc-and-Anchor/sigilix-marketing) · [`sigilix-docs`](https://github.com/Arc-and-Anchor/sigilix-docs)

### [Rubberfit](https://get.rubberfit.app) — `rubberfit.app`

A manufacturing operations platform for rubber-roll fabricators — Rust-powered nesting engine ([jagua-rs](https://github.com/JeroenGar/jagua-rs) polygon bin packing + a sparrow-style guided local search), full inventory + jobs + audit trail + barcode workflow. One product replaces the typical CAD-plugin + MRP + CRM stack.

- **Marketing:** [get.rubberfit.app](https://get.rubberfit.app)
- **App:** [rubberfit.app](https://rubberfit.app)
- **Docs:** [docs.rubberfit.app](https://docs.rubberfit.app)
- **Public repos:** [`rubberfit-marketing`](https://github.com/Arc-and-Anchor/rubberfit-marketing) · [`rubberfit-docs`](https://github.com/Arc-and-Anchor/rubberfit-docs)

### Predict Market Bot

A research-grade automation for prediction-market signals. Currently in private development.

- **Repo:** [`predict-market-bot`](https://github.com/Arc-and-Anchor/predict-market-bot) (private)

## Engineering principles

- **Specialized over general.** A single generalist model can write any review; only an ensemble of specialists writes the right one. Same idea applies to the rest of our stack.
- **Honest scoreboards.** No 97%-accuracy banners with asterisks. We publish methodology before numbers, and audits before claims.
- **Small surface, deep correctness.** We'd rather ship one feature with a formal specification than five with hand-waved guarantees.
- **Customer code never trains a model.** Zero-retention inference, scoped permissions, no embedding stores. Read the [Sigilix security architecture](https://sigilix.ai/security) and the [Rubberfit security posture](https://docs.rubberfit.app/security/posture) for the full picture.

## Open-source dependencies we build on

We try to be explicit about the open-source work that makes our products possible. The big ones:

| Project | License | What we use it for |
|---|---|---|
| [jagua-rs](https://github.com/JeroenGar/jagua-rs) | MIT | Polygon bin packing in the Rubberfit nesting engine |
| [sparrow](https://github.com/JeroenGar/sparrow) | MIT | Guided-local-search metaheuristic that drives the cut layouts |
| [Next.js](https://github.com/vercel/next.js) | MIT | Web framework for every Arc & Anchor site |
| [Supabase](https://github.com/supabase/supabase) | Apache-2.0 | Postgres, Auth, Storage backbone for our applications |
| [Nextra](https://github.com/shuding/nextra) | MIT | Documentation framework for `docs.sigilix.ai` and `docs.rubberfit.app` |

## Contact

- **Support:** [hello@arcanchor.com](mailto:hello@arcanchor.com)
- **Security disclosures:** [security@arcanchor.com](mailto:security@arcanchor.com) · [security@rubberfit.app](mailto:security@rubberfit.app)
- **Sales / Enterprise:** [sales@arcanchor.com](mailto:sales@arcanchor.com) · [sales@rubberfit.app](mailto:sales@rubberfit.app)

---

> Arc & Anchor LLC · est. 2026 · Las Vegas, NV

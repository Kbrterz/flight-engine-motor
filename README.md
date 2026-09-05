# Flight Engine — landing site

Single-file static site for **flight-engine-motor.vercel.app**.

- `index.html` — the whole site. Three sections:
  1. `#engine` — The engine
  2. `#demo` — Live takeoff calculation (deterministic, runs client-side)
  3. `#overview` — What you get (client-facing value, two-layer architecture, governance facts)
- `vercel.json` — static hosting config (clean URLs).

No build step. Deploy = serve `index.html`.

Calculation model is illustrative, not certified performance data.

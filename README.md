# Michael Gauci

I'm a full-stack developer. I build React and TypeScript interfaces, analytics dashboards, and the APIs and admin tools behind them. I've also migrated WordPress sites to Next.js and built custom CMS tools so editors can manage content themselves.

## Featured project · iGaming Canvas Lab

Five playable browser games built with PixiJS and TypeScript. I separated game logic from rendering so outcomes can be tested independently. The scratch card tracks coverage on the CPU while PixiJS renders the effect, avoiding GPU readback.

[Play the scratch card](https://igaming-canvas-lab.vercel.app/scratch/) · [Browse the code and tests](https://github.com/mikegauci/igaming-canvas-lab/tree/main/apps/scratch)

<a href="https://igaming-canvas-lab.vercel.app/">
  <img src="assets/canvas-lab.jpg" width="640" alt="iGaming Canvas Lab cover art with a neon sunset and arcade lettering">
</a>

## Selected work

- **Market Pilot** · A Next.js trading analytics dashboard with Recharts for equity and daily profit and loss, candlestick charts, and a Python integration with Interactive Brokers. [Dashboard code](https://github.com/mikegauci/market-pilot/blob/main/dashboard/components/analytics-dashboard.tsx)
- **QTM Detailing** · A Next.js site with Tailwind and shadcn/ui, a custom CMS and CRM for bookings and leads, and a Google Drive integration for importing gallery photos. [Repository](https://github.com/mikegauci/qtm-detailing)
- **Pantrila** · A meal planner with Next.js and Expo clients, a shared TypeScript API client, and a Python backend with retrieval-augmented generation and LLM evaluations. [Repository](https://github.com/mikegauci/pantrila) · [Try the guest demo](https://app.pantrila.com)

<a href="https://github.com/mikegauci/pantrila">
  <img src="assets/pantrila-meal-plan.png" width="240" alt="Pantrila mobile meal plan showing daily meals and nutrition targets">
</a>

## How I use coding agents

I write project-specific instructions and reusable skills for recurring work. In Market Pilot, a preflight skill specifies which tests, lint checks, and builds to run based on what changed. In Pantrila, the mobile agent guide calls for checking the installed Expo version against its documentation and running lint and type checks. [Preflight skill](https://github.com/mikegauci/market-pilot/blob/main/.agents/skills/preflight-checks/SKILL.md) · [Mobile agent guide](https://github.com/mikegauci/pantrila/blob/main/mobile/AGENTS.md)

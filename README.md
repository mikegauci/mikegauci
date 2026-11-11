# Michael Gauci

I'm a full-stack developer. I build React and TypeScript interfaces, analytics dashboards, and the APIs and admin tools behind them. I've also migrated WordPress sites to Next.js and built custom CMS tools so editors can manage content themselves.

## Featured project · iGaming Canvas Lab

Five playable browser games built with PixiJS and TypeScript. I separated game logic from rendering so outcomes can be tested independently. Mini Slot animates the reels toward a predetermined result, and Crash uses a mock server clock to determine whether a cash-out arrives in time.

[Play Mini Slot](https://igaming-canvas-lab.vercel.app/slot/) · [Play Crash](https://igaming-canvas-lab.vercel.app/crash/) · [Browse the code and tests](https://github.com/mikegauci/igaming-canvas-lab/tree/main/apps)

<a href="https://igaming-canvas-lab.vercel.app/">
  <img src="assets/canvas-lab.jpg" width="640" alt="iGaming Canvas Lab cover art with a neon sunset and arcade lettering">
</a>

## Selected work

- **Market Pilot** · A Next.js trading analytics dashboard with Recharts for equity and daily profit and loss, candlestick charts, and a Python integration with Interactive Brokers. The strategy page walks through how a breakout moves from a signal to a trade or a skip. [Strategy page](https://market-pilot-dashboard.vercel.app/strategy) · [Dashboard code](https://github.com/mikegauci/market-pilot/blob/main/dashboard/components/analytics-dashboard.tsx)

<a href="https://market-pilot-dashboard.vercel.app/strategy">
  <img src="assets/market-pilot-strategy.gif" width="640" alt="Market Pilot strategy page stepping through a breakout example, with a card showing the AI's BUY decision passing the entry filters">
</a>

- **MaltaGuns** · I built the platform end to end in Next.js and TypeScript, from the public marketplace to a custom CMS and admin CRM for managing listings, articles, events, and users. [Public site](https://www.maltaguns.com/) · [Frontend code](https://github.com/mikegauci/maltaguns-app/blob/main/app/page.tsx) · [Admin dashboard code](https://github.com/mikegauci/maltaguns-app/blob/main/app/admin/page.tsx)

<a href="https://www.maltaguns.com/">
  <img src="assets/maltaguns-tour.gif" width="640" alt="MaltaGuns homepage, admin dashboard and listing moderation, with cards showing a listing going live, an identity review and approvals">
</a>

- **QTM Detailing** · A Next.js site with Tailwind and shadcn/ui, a custom CMS and CRM for bookings and leads, and a Google Drive integration for importing gallery photos. [Public site](https://www.qtmdetailing.mt/) · [Repository](https://github.com/mikegauci/qtm-detailing)

<a href="https://www.qtmdetailing.mt/">
  <img src="assets/qtm-tour.gif" width="640" alt="QTM Detailing homepage, CRM dashboard and booking Kanban board, with cards showing a quote request becoming a lead and a booking moving to in progress">
</a>

<sub>Admin screens show sample data.</sub>

- **Pantrila** · A meal planner with Next.js and Expo clients, a shared TypeScript API client, and a Python backend with retrieval-augmented generation and LLM evaluations. [Repository](https://github.com/mikegauci/pantrila) · [Try the guest demo](https://app.pantrila.com)

<a href="https://github.com/mikegauci/pantrila">
  <img src="assets/pantrila-meal-plan.png" width="43%" alt="Pantrila mobile meal plan showing daily meals and nutrition targets">&nbsp;
  <img src="assets/pantrila-grocery-list.png" width="43%" alt="Pantrila mobile grocery list showing ingredients and quantities for planned meals">
</a>

## How I use coding agents

I write project-specific instructions and reusable skills for recurring work. In Market Pilot, a preflight skill specifies which tests, lint checks, and builds to run based on what changed. In Pantrila, the mobile agent guide calls for checking the installed Expo version against its documentation and running lint and type checks. [Preflight skill](https://github.com/mikegauci/market-pilot/blob/main/.agents/skills/preflight-checks/SKILL.md) · [Mobile agent guide](https://github.com/mikegauci/pantrila/blob/main/mobile/AGENTS.md)

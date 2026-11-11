<h1 align="center">Michael Gauci</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=2600&pause=900&color=2EA043&center=true&vCenter=true&width=560&lines=Full-stack+developer;TypeScript+%2B+Python;LLM+integrations+that+ship+with+evals;WordPress+and+Astro+%E2%86%92+Next.js+migrations" alt="Full-stack developer · TypeScript and Python · LLM integrations · Framework migrations">
</p>

<p align="center">
  📍 Based in Malta<br>
  <a href="mailto:mikegauci@gmail.com">Email</a> · <a href="https://www.linkedin.com/in/michael-gauci-422180104">LinkedIn</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/currently-online-44cc11" alt="Currently online">
  <a href="https://github.com/mikegauci/onyx"><img src="https://img.shields.io/badge/coding-Onyx-0a84ff?logo=claude&logoColor=white" alt="Coding Onyx"></a>
  <img src="https://img.shields.io/badge/listening%20to-Daft%20Punk-1db954?logo=spotify&logoColor=white" alt="Listening to Daft Punk">
  <img src="https://img.shields.io/badge/watching-Formula%201-e10600?logo=f1&logoColor=white" alt="Watching Formula 1">
</p>

I'm a full-stack developer working across TypeScript and Python. On the front end I build React and Next.js interfaces, analytics dashboards and admin tools. On the back end I write the APIs, Supabase data models and Python services behind them, such as a FastAPI meal-planning backend and a trading engine connected to Interactive Brokers.

I integrate LLMs into products, not just chat boxes. That includes retrieval-augmented generation over a recipe catalogue, structured buy, hold or sell decisions gated by hard risk filters, and evaluation suites that check model output before it ships.

I also migrate sites between frameworks. I've moved several WordPress sites and an Astro site to Next.js on Vercel and Supabase, with page-by-page parity checks, managed redirects, a custom SEO layer and CMS tools so editors can manage content themselves.

<details>
<summary><b>More about me</b></summary>
<br>

- **What I'm building now:** Onyx, which is two products in one monorepo. Onyx Studio is a public website, and Onyx Platform is a multi-tenant SaaS for business operations and AI automation. Both have Next.js front ends sharing shadcn/ui components, on top of a FastAPI backend and Postgres.
- **Client work:** mostly for businesses in Malta. I move e-commerce and content sites off WordPress onto Next.js and Supabase, with Stripe payments, transactional email and admin panels the owners run themselves. One was a bilingual English and Arabic site with full right-to-left layouts.
- **Design as well as code:** I go from Figma layouts and Photoshop and Illustrator assets to the design systems the components are built on, so a project doesn't need a separate hand-off.
- **What I care about:** the unglamorous parts that keep a product healthy, such as typed APIs, migrations committed to the repo, error tracking with Sentry and agents that follow the same rules as the rest of the team.
- **Away from the keyboard:** I follow Formula 1, and Daft Punk is usually playing while I code.

</details>

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,gatsby,astro,wordpress,php,tailwind,threejs,nodejs,python,fastapi,supabase,postgres,mysql,docker,cloudflare,vercel,git,figma,ps,ai&perline=11" alt="TypeScript, React, Next.js, Gatsby, Astro, WordPress, PHP, Tailwind CSS, Three.js, Node.js, Python, FastAPI, Supabase, PostgreSQL, MySQL, Docker, Cloudflare, Vercel, Git, Figma, Photoshop and Illustrator">
</p>

<p align="center"><sub>Also: OpenAI API · pgvector · Expo · PixiJS · Recharts · shadcn/ui · Interactive Brokers API</sub></p>

## Projects

### 🎰 iGaming Canvas Lab

`TypeScript` `PixiJS` `Vite` `Vitest` `pnpm workspaces`

Five playable browser games built with PixiJS and TypeScript. I separated game logic from rendering so outcomes can be tested independently. Mini Slot animates the reels toward a predetermined result, and Crash uses a mock server clock to determine whether a cash-out arrives in time.

**[Casino Floor](https://igaming-canvas-lab.vercel.app/)** · **[Browse Codebase](https://github.com/mikegauci/igaming-canvas-lab)**

<a href="https://igaming-canvas-lab.vercel.app/">
  <img src="assets/canvas-lab.jpg" width="640" alt="iGaming Canvas Lab cover art with a neon sunset and arcade lettering">
</a>

### 🎯 MaltaGuns

`Next.js` `React` `TypeScript` `Supabase` `Tailwind CSS` `Radix UI` `TanStack Table` `Tiptap` `Resend`

I built the platform end to end in Next.js and TypeScript, from the public marketplace to a custom CMS and admin CRM for managing listings, articles, events, and users.

**[Public Site](https://www.maltaguns.com/)** · **[Browse Codebase](https://github.com/mikegauci/maltaguns-app)**

<a href="https://www.maltaguns.com/">
  <img src="assets/maltaguns-tour.gif" width="640" alt="MaltaGuns homepage, admin dashboard and listing moderation, with cards showing a listing going live, an identity review and approvals">
</a>

### 🚗 QTM Detailing

`Next.js` `TypeScript` `Supabase` `Tailwind CSS` `shadcn/ui` `Google APIs` `OpenAI` `FullCalendar` `dnd kit`

A Next.js site with Tailwind and shadcn/ui, a custom CMS and CRM for bookings and leads, and a Google Drive integration for importing gallery photos.

**[Public Site](https://qtmdetailing.mt/)** · **[Browse Codebase](https://github.com/mikegauci/qtm-detailing)**

<a href="https://qtmdetailing.mt/">
  <img src="assets/qtm-tour.gif" width="640" alt="QTM Detailing homepage, CRM dashboard and booking Kanban board, with cards showing a quote request becoming a lead and a booking moving to in progress">
</a>

<sub>Admin screens show sample data.</sub>

### 🥗 Pantrila

`Next.js` `Expo` `TypeScript` `Python` `FastAPI` `OpenAI` `pgvector` `Supabase`

A meal planner with Next.js and Expo clients, a shared TypeScript API client, and a Python backend with retrieval-augmented generation and LLM evaluations.

**[Public Site](https://pantrila.com/)** · **[Public App (Try it as Guest)](https://app.pantrila.com/)**

<a href="https://app.pantrila.com/">
  <img src="assets/pantrila-tour.gif" width="640" alt="Pantrila homepage, weekly meal plan and grocery list, with cards showing an allergen-checked recipe answer, a day landing on its energy target and a list of only what is missing">
</a>

### 📈 Market Pilot

`Next.js` `TypeScript` `Recharts` `Python` `OpenAI` `Supabase` `Interactive Brokers API`

A Next.js trading analytics dashboard with Recharts for equity and daily profit and loss, candlestick charts, and a Python trading engine connected to Interactive Brokers. An LLM scores each watched stock as buy, hold or sell, and hard entry filters and risk caps decide whether a strong BUY becomes a trade. The strategy page walks through that path step by step.

**[Browse Codebase](https://github.com/mikegauci/market-pilot)**

<a href="https://market-pilot-dashboard.vercel.app/strategy">
  <img src="assets/market-pilot-strategy.gif" width="640" alt="Market Pilot strategy page stepping through a breakout example, with a card showing the AI's BUY decision passing the entry filters">
</a>

## How I use coding agents

I work with **Claude Code**, **Codex** and **Cursor** every day, and I set each repository up so all three follow the same rules. `CLAUDE.md` and `AGENTS.md` hold the project instructions, and Cursor rules and skills cover the conventions that are easy to get wrong. In MaltaGuns, skills describe the design system and the firearms domain. In QTM Detailing, a rule keeps every quote button pointing at the same WhatsApp link.

<details>
<summary><b>Skills, MCP servers and how I test LLM features</b></summary>
<br>

I turn recurring work into skills, so it runs the same way every time. Market Pilot has skills for preflight checks, adding a strategy filter, diagnosing the trader and reviewing a trading session. The preflight skill picks which tests, lint checks and builds to run based on what changed. In Pantrila, the mobile agent guide calls for checking the installed Expo version against its documentation before writing code. [Preflight skill](https://github.com/mikegauci/market-pilot/blob/main/.agents/skills/preflight-checks/SKILL.md) · [Mobile agent guide](https://github.com/mikegauci/pantrila/blob/main/mobile/AGENTS.md)

I connect agents to the services the apps run on through MCP servers. In Market Pilot, schema changes go through the Supabase MCP server and are saved as migration files in the same step, so the database and the repository stay in sync.

On the product side, I treat LLM features like any other code that has to be tested. Model calls return structured output against a JSON schema instead of free text, Pantrila's retrieval runs on OpenAI embeddings stored in pgvector, and its eval suites score retrieval, chat and meal-plan quality and save reports, so a prompt or model change that makes results worse shows up before it ships.

</details>

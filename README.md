# Nikita Gritsenko

Master's student in Kemerovo. I build web apps and the automation behind them: Nuxt and TypeScript on the front, Node and PostgreSQL on the back, LLM agents and n8n when a process should run without me.

## Projects

**[idea-factory](https://github.com/nikgritenok/idea-factory)**  
Turns a raw idea, typed or dictated, into a report with an effect estimate and a go/no-go. Seven stages, five of them LLM roles in sequence; the effect calculation and the report assembly are deterministic code, so the numbers don't depend on a model's mood. The stage list lives in config, not in the UI, so the pipeline changes without a deploy. Nuxt, PostgreSQL, typed contracts on every model call.

**[atom-case-2](https://github.com/nikgritenok/atom-case-2)**  
Service for equipment maintenance requests. Eleven Sequelize migrations, nginx in front, Prometheus and Grafana inside, a request id that follows a call through logs and metrics, tests and CI on every pull request.

**[express-app](https://github.com/nikgritenok/express-app)**  
Backend starter I built for a hackathon: Express 5, strict TypeScript, Prisma, Zod schemas that generate the OpenAPI spec, Scalar docs, Vitest. The README takes a person who has never used Docker from a clean laptop to a running database.

## Awards

**1st place, IT-KOR 5.0 hackathon (Rosatom), October 2026.** Web development track (JS), team «Отцы дедлайнов». Case: maintenance requests for wind turbines. Four-person team; my eight merged pull requests cover the request workflow, the turbine monitoring hooks, the dashboard for the site manager and the one-command startup.

[Diploma](assets/it-kor-5-diploma.jpg) · [Code](https://github.com/HACKATHON-ROSATOM/hack)

## Stack

TypeScript, JavaScript, Vue and Nuxt, Node, Express, PostgreSQL, Prisma, Sequelize, Docker, GitHub Actions. Python when the task calls for it.

## How I work

I build with AI agents and review every line before it lands. Most of the 2026 work here came out of that loop, which is why the commit history is short and the diffs are large. Happy to walk through any file: the retry and fallback logic in the idea-factory pipeline, or the PDF cache versioning in atom-case-2.

READMEs here are in English; some repos keep their longer Russian notes below the fold.

## Contact

Telegram [@nikgritenok](https://t.me/nikgritenok) · [nik.gretsenko1@gmail.com](mailto:nik.gretsenko1@gmail.com)

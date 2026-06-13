<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a1f35&height=120&section=header&text=Irfan%20Javed&fontColor=ffffff&fontSize=40&fontAlign=50&fontAlignY=65&desc=Senior%20Full%20Stack%20Engineer&descAlign=50&descAlignY=85&descSize=16" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=700&lines=Laravel+%7C+Vue+3+%7C+React+%7C+Next.js+%7C+TypeScript+%7C+Node.js;7%2B+Years+Building+Production+SaaS+Platforms;Multi-tenant+Architecture+%7C+REST+API+%7C+Real-time+Systems;Open+to+Remote+Opportunities" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/irfan-javed-6795281b5">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:irfanjavedofficial@gmail.com">
    <img src="https://img.shields.io/badge/irfanjavedofficial%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Lahore%2C_Pakistan-555?style=flat-square&logo=google-maps&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/Open_to_Work-22c55e?style=flat-square" />
</p>

<br/>

---

## About Me

Full Stack Engineer with **7+ years** of experience designing, building, and shipping production SaaS platforms from scratch. I specialize in:

- **Multi-tenant B2B SaaS** — per-tenant database isolation, role-based access control, subscription billing
- **eCommerce integrations** — Shopify, WooCommerce, BigCommerce cart sync; multi-vendor order management
- **Real-time systems** — RTMP → HLS live streaming, WebSockets, Pusher, Laravel Echo
- **Payment engineering** — Stripe (PaymentIntent, webhooks, subscriptions, credit notes), PayPal, CCBill
- **Frontend complexity** — Web Components, 3D product visualization (Three.js + Fabric.js), AI-powered tools

I take **end-to-end ownership**: database schema → REST API → frontend → CI/CD → production deployment.

---

## Tech Stack

**Backend**
<p>
  <img src="https://skillicons.dev/icons?i=laravel,php,nodejs,express" />
</p>

**Frontend**
<p>
  <img src="https://skillicons.dev/icons?i=vue,react,nextjs,angular,ts,tailwind" />
</p>

**Database, Cloud & DevOps**
<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,aws,docker,kubernetes,git,github" />
</p>

---

## Production SaaS

<table>
<tr>
<td width="50%" valign="top">

### [Custimoo](https://custimoo.com)
**Product Customization Platform**

Multi-tenant SaaS for selling customized apparel and sportswear. Merchants embed a fully white-labeled 2D/3D product builder into their Shopify, WooCommerce, or BigCommerce stores.

**Key engineering:**
- Laravel 12 backend · 95+ Eloquent models
- Dual Stripe accounts (DKK + CAD currencies)
- Shopify / WooCommerce / BigCommerce API cart sync
- Vue 3 Web Component `<v-customizer>` (Shadow DOM, `dist/widget.js`)
- 9-step customization workflow: product → designs → styles → colors → patterns → logos → texts → roster → summary
- Fabric.js 2D canvas + Three.js GLTF/DRACO/HDR 3D preview
- AI logo generation (generate / refine / redesign)
- Paraglide i18n — 11 languages (EN/FR/DA/ES/DE/IT/NL/NO/PL/SV/PT)
- Pantone Coated + TCX full color palettes

</td>
<td width="50%" valign="top">

### [StaffViz](https://www.staffviz.com)
**Workforce Management SaaS**

B2B platform for time tracking, activity monitoring, productivity analytics, and HR workflows — serving multiple companies under one platform.

**Key engineering:**
- Laravel 10 · 9 nwidart/laravel-modules
- Spatie RBAC with portal-prefixed roles
- Per-tenant DB provisioning at signup
- Dynamic database switching at runtime per company
- Stripe subscriptions + credit notes + webhook handling
- Zapier custom OAuth2 provider integration
- AES-256-CBC end-to-end payload encryption (Angular admin)
- Angular 18 admin panel
- Bitbucket Pipelines → Docker → Kubernetes deployment
- 200+ routes · 200+ database migrations

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Stream-It](https://github.com/irfanf16/stream-it)
**Live Streaming & Creator Monetization**

Live streaming platform with a virtual token economy for creator monetization and private paid 1-on-1 sessions.

**Key engineering:**
- Laravel 9 + Inertia.js + React 18
- RTMP → HLS broadcast pipeline
- Pusher real-time events (viewer count, tips, chat)
- Token economy: 75/25 creator/platform split
- Private paid 1-on-1 streaming sessions
- 4 payment gateways: Stripe · PayPal · CCBill · Bank Transfer
- 18+ age gate enforcement
- 25+ database tables

</td>
<td width="50%" valign="top">

### [clipfetch](https://github.com/irfanf16/clipfetch)
**Multi-Platform Video Downloader**

Next.js 15 SaaS with no SDK bloat — raw HTTP calls to Supabase PostgREST and Upstash Redis.

**Key engineering:**
- Next.js 15.5 App Router · React 19 · TypeScript
- Provider registry: RapidAPI → oEmbed → Mock (priority-based)
- SSRF allowlist (8 CDN hosts) for URL proxy protection
- Rate limiting: 40 req/hour per SHA-256 salted IP hash
- 6 feature flags (DB-override + env vars)
- HMAC session-based admin panel
- Vercel cron cleanup daily at 03:00 UTC
- 8 Supabase tables · 16 tool slugs

</td>
</tr>
</table>

---

## Other Projects

| Repo | Stack | What it does |
|---|---|---|
| [toolifyhub-website](https://github.com/irfanf16/toolifyhub-website) | Next.js 15 · Groq · MongoDB | 39-tool AI SaaS — Llama 3.3 70B + Whisper, edge runtime, Stripe + PayPal |
| [cloudTeleService](https://github.com/irfanf16/cloudTeleService) | Laravel 9 · Google Calendar API | Telehealth scheduling — full/incremental calendar sync, Google Meet auto-generation |
| [ecommerence-api](https://github.com/irfanf16/ecommerence-api) | Laravel 8 · JWT · Pusher | Multi-vendor marketplace — 115+ tables, vendor KYC pipeline, commission system |
| [BrightChef](https://github.com/irfanf16/BrightChef) | Laravel 9 · OpenAI · Horizon | AI recipe & meal planning — few-shot GPT-3, laravel-actions, Redis queue |
| [translation-service](https://github.com/irfanf16/translation-service) | Laravel 12 · Sanctum · Docker | i18n microservice — locale export cache, tag taxonomy, OpenAPI spec |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=irfanf16&show_icons=true&theme=github_dark&hide_border=true&count_private=true&rank_icon=github&include_all_commits=true" height="165" />
  &nbsp;
  <img src="https://streak-stats.demolab.com?user=irfanf16&theme=github-dark-blue&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=irfanf16&theme=github-compact&hide_border=true&area=true" width="95%" />
</p>

---

<p align="center">
  <img src="https://raw.githubusercontent.com/irfanf16/irfanf16/output/github-snake-dark.svg" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1f35,100:0d1117&height=90&section=footer" width="100%" />

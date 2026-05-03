# Moiz Haroon Khan

Full-stack developer and builder based in Michigan.

I build AI phone agents, websites, automation systems, and e-commerce brands
for local businesses. I work end-to-end — from the first conversation with a
client to deployment and ongoing operations.

---

## Projects

| Project | What It Is | Stack | Status |
|---------|-----------|-------|--------|
| [Got Burger](#got-burger) | Restaurant website — 3D hero, online ordering, AI caller | React, Three.js, Next.js, VAPI, Stripe | In progress |
| [AI Receptionist Service](#ai-receptionist-service) | 24/7 AI phone agent for local businesses | Retell AI, ElevenLabs, Square API | Active |
| [Hasmora](#hasmora) | Premium home lighting e-commerce brand | Shopify | Live |
| [MZ Solutions LLC](#mz-solutions-llc) | US payment bridge for international businesses | LLC, Netevia, BofA | Live |
| [Finance Automation System](#finance-automation-system) | Gmail-monitoring finance tracker with phone alerts | Python, Gmail API, Pushover | Running |
| [Lead Scraper + DM Bot](#lead-scraper--dm-bot) | Google Places scraper + Instagram outreach automation | Python, Selenium | Built |
| [Website Audit Tool](#website-audit-tool) | AI-powered site audit + landing page generator | Anthropic API, Python | Built |
| [Lockfit](#lockfit) | Magnetic gym bag DTC brand | Shopify | Built |
| [Job Matching Automation](#job-matching-automation) | Multi-board job scraper + auto-apply + phone alerts | Python, Pushover | Built |

---

## Got Burger

**Halal burger restaurant in Ypsilanti, MI — full website and AI phone caller.**

A complete restaurant digital presence built from scratch:

- **3D hero section** — spinning burger model built with React Three Fiber. GLB model Draco-compressed from 7.9MB → 715KB (91% reduction) for fast mobile load.
- **Menu system** — 10 categories, sticky tab bar, per-item customizer with ingredient chips, add-to-cart flow.
- **Online ordering** — Stripe-powered checkout via `/api/create-payment-intent`, cart with Zustand state, order summary, post-payment success screen.
- **Location page** — Google Maps embed, hours grid, Halal badge, social links.
- **In-store display** — `/menu/display` full-screen menu board that auto-rotates categories every 12 seconds.
- **Print menu** — `/menu/pdf` print-optimized layout for the print shop.
- **SEO** — Per-page metadata, OG tags, `sitemap.xml`, `robots.txt`. Targets "halal burger Ypsilanti" and "halal fast food Ann Arbor".
- **CI** — GitHub Actions workflow that auto-runs Draco compression on any new GLB pushed to the repo.
- **AI Phone Caller** (in progress) — VAPI assistant with full menu knowledge → Square Orders API → kitchen display system.

**Stack**: Next.js, React Three Fiber, Tailwind CSS, Zustand, Stripe, VAPI, Square API, Vercel

---

## AI Receptionist Service

**Productized AI phone answering for restaurants, salons, barbershops, clinics, and auto shops.**

The AI answers every inbound call within 2 seconds, handles the full interaction
(food orders, appointment bookings, FAQ), reads the order/booking back to confirm,
and escalates to a human when outside its scope.

- Restaurant version pushes orders directly to Square POS — no manual entry
- Calendar integration version checks real-time availability and confirms bookings
- Built and tested a working demo that is used as the core sales asset in all proposals
- Also built an AI cold caller variant using Retell AI for automated outreach

**Stack**: Retell AI, ElevenLabs, Make, Zapier, Square API, Google Calendar API, Claude API

---

## Hasmora

**Premium home lighting e-commerce brand — built and launched entirely solo.**

- Curated and named 30+ SKUs: chandeliers, pendant lights, wall sconces, table lamps
- Full storefront theming, UX, and copywriting from scratch
- Multilingual support (English and Spanish)
- Custom order tracking, supplier coordination, product pages
- Managed end-to-end operations

**Stack**: Shopify, Liquid, custom theme

---

## MZ Solutions LLC

**Registered US LLC operating as a payment bridge for international businesses.**

Cross-border payment problem: businesses outside the US often cannot receive US card
payments directly. MZ Solutions receives the payment from the US customer and forwards
the funds minus a service fee.

- Went through the full merchant services application process
- Verified and approved by Expedio Payments (a division of Netevia)
- Business banking set up at Bank of America
- Operational since April 2026

---

## Finance Automation System

**Fully automated finance tracker for MZ Solutions LLC. Runs without any manual input.**

- Monitors Gmail for Bank of America transaction alert emails via Gmail API (OAuth)
- Parses and logs every deposit, withdrawal, and alert to a weekly Excel file
- Calculates service fees on all deposits
- Sets aside a fixed percentage for tax reserves (federal + self-employment)
- Generates weekly summaries with withdrawal instructions
- Sends daily digest phone notification at 10am via Pushover
- Sends immediate urgent alerts for anything flagged as fraud, IRS-related, or account issues
- Also scans for any email mentioning the business name regardless of sender

**Stack**: Python, Gmail API (OAuth), openpyxl, Pushover API

---

## Lead Scraper + DM Bot

**Automated lead generation and outreach system for local business targeting.**

- Uses Google Places API to search for salons, barbershops, and restaurants by area
- Filters out national chains — only local independent businesses
- Pulls: business name, address, phone, website, rating, Instagram handle
- Saves leads to Excel with separate sheet for "phone only / no Instagram" contacts
- Selenium-based Instagram DM automation with rate limiting to avoid flagging

**Stack**: Python, Google Places API, Selenium, openpyxl

---

## Website Audit Tool

**AI-powered web app: input any URL, get a full audit report + a generated landing page.**

- Scrapes any business website
- Identifies SEO problems, loading issues, and conversion weaknesses
- Generates a PDF audit report in plain English with specific fixes
- Simultaneously builds a full custom landing page for that business
- Uses Anthropic Claude API with web search enabled
- Built as a standalone web app

**Stack**: Python, Anthropic Claude API, web scraping, PDF generation

---

## Lockfit

**Magnetic gym bag DTC brand — built from concept to storefront.**

- Product concept: magnetic closure gym bag targeting fitness enthusiasts
- Brand identity, product positioning, and go-to-market strategy
- Landing page development
- Supplier coordination
- Online storefront for DTC sales

**Stack**: Shopify

---

## Job Matching Automation

**Automated job search, scoring, and application system.**

- Scrapes LinkedIn, Indeed, Glassdoor, and one additional board for developer roles
- Scores each listing against resume and skills using AI matching
- Attempts auto-apply to best matches
- Flags listings with custom application portals as "needs manual apply"
- Sends Pushover phone notification on run completion with full summary

**Stack**: Python, Pushover API, web scraping

---

## Skills

**Languages**: JavaScript, TypeScript, Python, HTML, CSS

**Frameworks & Libraries**: React, Next.js, Node.js, Tailwind CSS, React Three Fiber, Zustand

**Platforms**: Shopify, Vercel, Netlify, GitHub

**AI & Automation**: Retell AI, VAPI, ElevenLabs, Anthropic Claude API, Make, Zapier, Selenium

**APIs**: Google Places API, Gmail API, Stripe, Square API, Pushover API

**Tools**: Git, Figma, Adobe Creative Suite, VS Code, Cursor, Claude Code

---

## Education

**Bachelor's Degree** — Eastern Michigan University

**A-Levels, Computer Science** — Future World School & College

---

## Contact

Open to client projects and full-time opportunities.

- **Instagram**: @[handle]
- **Email**: [email]
- **Upwork**: [link]

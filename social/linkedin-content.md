# LinkedIn Content — Agency + Professional Angle

LinkedIn is a different game than TikTok/Instagram.
Same work. Different framing. Longer text. More professional.
Audience: business owners, startup founders, other agencies, recruiters.

---

## LinkedIn vs TikTok Differences

| | TikTok/Instagram | LinkedIn |
|---|---|---|
| Tone | "Look what we built" | "Here's what we shipped and why it worked" |
| Length | 15–30 sec video | Long-form text post or 60-sec video |
| Hook | Visual first | Strong opening line |
| Audience | Business owners (local) | Founders, agencies, recruiters, B2B |
| CTA | "DM KEYWORD" | "Comment below" or "Connect with me" |

---

## LinkedIn Post Formula

```
[Strong opening line — scroll stopper]

[2–3 sentence context]

[List or breakdown — what was built, how it works, what it cost]

[One key insight or takeaway]

[CTA]

#hashtag1 #hashtag2 #hashtag3
```

Keep the first line punchy. LinkedIn truncates at line 3 — the "See more" cut.
Everything above that cut has to make them want to click.

---

## LinkedIn Posts

### POST L1 — Got Burger Full Project Breakdown

```
I built a restaurant website with a 3D model, online ordering, and an AI phone caller.
Total deal: $1,625 upfront + $400/month retainer.

Here's everything that's in it:

HOMEPAGE
→ 3D spinning burger model (React Three Fiber, Draco-compressed 91% — 7.9MB → 715KB)
→ Online menu with 10 categories and a customize modal
→ Stripe-powered checkout (no DoorDash commission)
→ Full SEO targeting "halal burger Ypsilanti"

MENU SYSTEM
→ Sticky category tab bar
→ Per-item customizer with ingredient chips
→ Add to cart, quantity controls, order summary

BONUS PAGES INCLUDED
→ /menu/display — full-screen auto-rotating in-store menu board
→ /menu/pdf — print-ready layout for the print shop
→ /location — Google Maps, hours, Halal badge, phone

AI PHONE CALLER (in progress)
→ VAPI assistant with full menu knowledge
→ Customer calls → AI takes order → pushes to Square KDS
→ Kitchen gets the ticket automatically

The client: Got Burger, Ypsilanti MI.
Halal burger restaurant, currently undergoing a remodel.

The remaining blockers: final menu, logo, domain access, POS decision, deposit.

When it launches, I'll document the full reveal here.

If you're building for restaurant clients or interested in the VAPI → Square integration,
drop a comment or connect with me.

#webdevelopment #aiagent #restauranttech #nextjs #threejs #reactthreefiber #vapi
```

---

### POST L2 — The Finance Automation System

```
I automated my entire business finances with a Python script.
Here's what it does.

MZ Solutions LLC is a payment bridge business — I process US payments for Pakistani businesses.
Every transaction needs to be logged, fees calculated, and taxes reserved.

I didn't want to do this manually. So I built a system.

THE SYSTEM:

1. Monitors Gmail for Bank of America transaction alert emails
2. Parses every deposit, withdrawal, and alert
3. Logs to a weekly Excel file with full transaction detail
4. Calculates my 10% business fee on every deposit automatically
5. Sets aside 30% for taxes (25% federal + 5% self-employment)
6. Generates weekly summaries with withdrawal instructions
7. Sends Pushover phone notifications:
   → Daily digest at 10am
   → Immediate urgent alerts for fraud, IRS, or account flags

FOLDER STRUCTURE: ~/Desktop/MZ Solutions LLC/
→ Weekly transaction files
→ Master log (all-time)
→ Weekly summary
→ Tax tracker
→ Alerts log
→ Run history

Libraries used: Gmail API (OAuth), openpyxl, Pushover API, Python 3.

I now check my Pushover notification every morning. I haven't touched a spreadsheet since.

Building your own? Happy to answer questions below.

#python #automation #businessautomation #gmailapi #financeautomation #solopreneur
```

---

### POST L3 — How I Built an AI Receptionist Service

```
I built a productized AI receptionist service for local businesses.
$300 setup + $150/month.
Here's how I built it and what it does.

TARGET MARKET: Restaurants, salons, barbershops, clinics, auto shops, med spas.
PROBLEM: These businesses miss calls constantly. Staff are too busy. Calls = money.

WHAT THE AI DOES:
→ Answers every inbound call within 2 seconds
→ Handles the full interaction (order, booking, FAQ)
→ Reads orders/confirmations back to the caller
→ Escalates to a human when outside its scope
→ (Restaurant version) pushes orders directly to Square POS

TECH STACK:
→ Retell AI (voice AI orchestration)
→ ElevenLabs (voice synthesis)
→ Make/Zapier (webhook integrations)
→ Square API (POS integration)
→ Claude / ChatGPT (prompt engineering)

SALES ASSET:
Built a working demo specific to a restaurant client. Recorded it.
That demo video is in every proposal, cold DM, and Upwork application.
The demo does the selling — I don't have to explain AI. I just show it.

PRICING ITERATED:
→ First pricing: $300 setup + $150/month
→ Lower-friction version: $150 setup + first month free + $99/month
Current: back to $300/$150 — clients who want free trials aren't serious.

Currently applied to Upwork jobs at $25–35/hr and getting responses.

The demo video is the differentiator.
If you're building AI voice products and want to compare notes — comment or connect.

#voiceai #aiagent #retellai #elevenlabs #productizedservice #localai #receptionistai
```

---

### POST L4 — The Lead Scraper

```
I built a Python scraper that finds my own clients.

TARGET: Salons, barbershops, and restaurants in Ann Arbor, MI.
SOURCE: Google Places API.

WHAT IT PULLS:
→ Business name
→ Address
→ Phone number
→ Website URL (or "none")
→ Google rating
→ Instagram handle (if available)

FILTERS OUT:
→ National chains (Walmart, McDonald's, etc.)
→ Businesses outside the target area

OUTPUTS:
→ leads.xlsx — all valid leads with full contact info
→ "Text Outreach" sheet — businesses with phone but no Instagram

OUTREACH LAYER:
→ Selenium logs into Instagram, sends DM with a 45-second delay between each
→ Delay keeps the account from being flagged

RESULT: 300+ local leads pulled in one run. 

Not for sale. Built specifically for my outreach operation.

But if you need something similar built for your business or service, drop a comment.

#python #webscraping #googleplacesapi #selenium #leadgeneration #outreachautomation
```

---

### POST L5 — MZ Solutions LLC Origin Story

```
I identified a gap in the market and started a business to fill it.

THE GAP:
Pakistan has hundreds of businesses selling to US customers — software agencies,
freelancers, product companies. Most can't receive US card payments directly
because they don't have a US banking or merchant account.

THE SOLUTION:
I registered MZ Solutions LLC in the US.
Got a merchant account through Expedio Payments (a division of Netevia).
Opened a Bank of America business checking account.

HOW IT WORKS:
→ A Pakistani business has a US customer who wants to pay by card
→ The customer pays MZ Solutions
→ MZ Solutions keeps 10% as the service fee
→ 90% is forwarded to the Pakistani business

NO TECH PRODUCT. Just a business solving a real cross-border payment problem.

Started: April 10, 2026.
Revenue model: 10% on every deposit.

The hardest part wasn't the legal setup — it was the merchant services application.
US payment processors are heavily KYC/AML regulated. Getting approved as a payment
facilitator required proper documentation of the business model.

It passed. We're live.

Building cross-border payment infrastructure? Connect with me.

#fintech #payments #crossborder #paymentprocessing #llc #entrepreneurship
```

---

## LinkedIn Hashtag Strategy

**Use 3–5 hashtags max** (unlike Instagram).
LinkedIn punishes posts that look spammy.

Good LinkedIn hashtags for your work:
#webdevelopment #aiautomation #voiceai #restauranttech #pythondeveloper
#solopreneur #buildinpublic #freelancing #localai #shopify #nextjs

---

## LinkedIn Profile Optimization

**Headline**: Full-Stack Developer | AI Receptionists + Web + Automation for Local Businesses
**About**: 3–4 sentences. What you build. Who you build for. Link to Instagram or email.
**Featured section**: Pin Got Burger video, AI demo video, and a post about MZ Solutions.
**Experience**: Add Hasmora, MZ Solutions, Got Burger as separate entries with descriptions.

# GitHub Setup Instructions

Steps to complete your GitHub presence. Do these once.

---

## Step 1 — Create the Private Repo (for sensitive work)

1. Go to github.com and sign in
2. Click the **+** top right → **New repository**
3. Name it: `private-ops`
4. Set to **Private**
5. Check "Add a README file"
6. Click **Create repository**

Then run this in your terminal to push the sensitive content there:

```bash
cd /home/user/Portfolio

# Add private-ops as a second remote
git remote add private git@github.com:moizharoonkhanwork-commits/private-ops.git

# Initialize a separate branch for private content
git checkout -b private-main

# Stage the social folder (it's gitignored on main but we want it here)
git add -f social/

git commit -m "Add private social media strategy and content playbooks"

git push private private-main:main
```

Then switch back to the main branch:
```bash
git checkout claude/portfolio-website-setup-pWv0J
```

---

## Step 2 — Create Your GitHub Profile README

GitHub shows a special README on your profile page if you create a repo
with the same name as your username.

1. Go to github.com → **New repository**
2. Name it: `moizharoonkhanwork-commits` (exactly your username)
3. Set to **Public**
4. Check "Add a README file"
5. Click **Create repository**
6. Edit the README to match the template below

**Profile README Template** (paste this into the README.md of that repo):

```markdown
# Moiz Haroon Khan

Full-stack developer and builder based in Michigan.
I build AI phone agents, websites, and automation for local businesses.

---

**What I build:**
- AI Receptionists — 24/7 AI that answers calls for restaurants and salons
- Websites — Local businesses, restaurants, e-commerce
- Automation — Scrapers, finance trackers, notification systems
- E-Commerce — Full Shopify brands from scratch

---

**Current projects:**
- Got Burger (Ypsilanti, MI) — Restaurant website + AI phone caller
- MZ Solutions LLC — US payment bridge for international businesses

---

**Stack:**
`JavaScript` `TypeScript` `Python` `React` `Next.js` `Shopify` `Tailwind CSS`
`Retell AI` `VAPI` `ElevenLabs` `Claude API` `Stripe` `Square API` `Selenium`

---

📩 [your email] | 📸 @[your handle]
```

---

## Step 3 — Pin Your Best Repos

1. Go to your GitHub profile: github.com/moizharoonkhanwork-commits
2. Click **Customize your pins**
3. Pin these repos (as you create them):
   - `portfolio` (this repo — your main showcase)
   - `got-burger` (when you separate it into its own repo)
   - Any other builds you publish

---

## Step 4 — Rules for Every New Project Going Forward

Every project gets its own repo. Here's the standard:

```
project-name/
├── README.md          ← What it is, what it does, how to run it
├── .gitignore
└── [your code files]
```

**README.md minimum**:
- What the project does (2–3 sentences)
- Tech stack
- How to run it locally (if applicable)
- Screenshot or demo link (if applicable)

---

## Step 5 — What Goes Where

| Content | Repo | Visibility |
|---------|------|-----------|
| Got Burger code | `got-burger` | Public |
| AI Receptionist config | `private-ops` | Private |
| Finance automation scripts | `private-ops` | Private |
| Lead scraper code | `private-ops` | Private |
| Social media strategy | `private-ops` | Private |
| Hasmora theme code | `hasmora` | Public or Private |
| Job scraper | `job-automation` | Public |
| Website audit tool | `website-audit-tool` | Public |
| Portfolio / profile | `portfolio` | Public |
| Pricing, scripts, DMs | `private-ops` | Private |

---

## How This Account Should Look in 30 Days

- Profile README live with bio and stack
- 5–8 pinned repos
- Regular commits showing active work
- Each repo has a proper README
- Private repo holds all sensitive business content
- Commit history tells the story of every build

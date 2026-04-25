<div align="center">

<br/>

# Project Levi

### Your AI-powered career co-pilot.

**[🌐 projectlevi.co.uk](https://projectlevi.co.uk)** &nbsp;·&nbsp; **[💼 LinkedIn](https://www.linkedin.com/company/project-levi)**

<br/>

![Status](https://img.shields.io/badge/Status-Live%20in%20Production-6c47ff?style=for-the-badge&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Web-6c47ff?style=for-the-badge)
![AI](https://img.shields.io/badge/Powered%20by-Gemini%20AI-6c47ff?style=for-the-badge)

<br/>

</div>

---

## What is Project Levi?

Most people don't know what the market demands. Cut through the noise. We'll show you the skills employers actually want. <br/>

Upload your CV, tell us your target role, and Levi's AI engine analyses your existing skills against real-world employer expectations. In seconds, you receive a personalised, phase-by-phase learning roadmap with curated resources. So you know **exactly** what to learn and in what order.

No noise. No generic advice. Just a precise path from where you are to where you want to be.

---

## How it Works

```
📄 Upload your CV  →  🔒 Google DLP sanitises personal info  →  🧠 Levi extracts skills
      ↓
🎯 Select your target role  →  📊 Gap Analysis  →  🗺️ Personalised Roadmap Generated
      ↓
📚 Curated Learning Resources  →  ✅ Progress Tracking  →  🚀 Career Ready
```

---

## Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Vue 3 + Vite, deployed on Netlify |
| **Backend** | Python FastAPI, deployed on Google Cloud Run |
| **AI Engine** | Google Gemini API + LangGraph agent pipeline |
| **Data Privacy** | Google Cloud DLP (PII redaction before AI processing) |
| **Authentication** | Supabase Auth (Google OAuth & GitHub OAuth) |
| **Database** | PostgreSQL via Supabase + pgvector for semantic search |
| **Security** | Cloudflare Turnstile (bot protection), JWT auth, CORS hardening |
| **Payments** | Stripe (premium tier — coming soon!) |
| **Job Market Data** | Adzuna API |
| **Learning Resources** | YouTube Data API + Google Custom Search API |

---

## Current Status

> 🟢 **Live in Production** — [projectlevi.co.uk](https://projectlevi.co.uk)

Levi is currently in **open beta**. Core features are fully functional and production-ready.

---

## Changelog

### `v1.2.0` — April 2026
- ✅ **Cloudflare Turnstile** bot protection added to all AI endpoints
- ✅ **Guest-to-account conversion prompt** — users are prompted to save their roadmap after generation
- ✅ **Dedicated Privacy Policy page** at `/privacy-policy` with full GDPR/UK GDPR compliance
- ✅ **Trailer modal** added to the site footer
- ✅ **Google OAuth branding** updated for the consent screen

### `v1.1.0` — April 2026
- ✅ **GitHub OAuth** added as a login option
- ✅ **Cookie Policy** embedded into the Privacy Policy
- ✅ **PDF Syllabus export** — download your full roadmap as a formatted PDF
- ✅ **Progress tracker** — mark skills as In Progress, Completed, or Skipped
- ✅ **Dashboard** for authenticated users to manage and revisit saved roadmaps

### `v1.0.0` — March 2026
- 🚀 Initial production launch
- CV upload with automated PII redaction
- AI skill extraction and gap analysis
- Personalised roadmap generation with curated YouTube/article resources
- Google OAuth authentication via Supabase

---

## Roadmap

| Feature | Status |
|---|---|
| Premium roadmaps (full unlock, more phases) | 🔜 Coming Soon |
| Email notifications for roadmap milestones | 🔜 Coming Soon |
| Mobile-responsive enhancements | 🔜 Coming Soon |
| Team / cohort roadmaps for universities | 💡 Exploring |

---

## Privacy & Security

Levi is built with privacy as a first principle:

- **CVs are never stored.** All uploaded files are processed in memory and discarded immediately after skill extraction.
- **PII is redacted** by Google Cloud DLP before any CV content reaches the AI model.
- **No tracking cookies.** Levi uses strictly necessary session tokens only — no marketing pixels, no analytics fingerprinting.
- **Bot protection** on all AI endpoints via Cloudflare Turnstile.

Full details: [Privacy Policy](https://projectlevi.co.uk/privacy-policy)

---

## Get in Touch

| | |
|---|---|
| 📧 General enquiries | [meetprojectlevi@gmail.com](mailto:meetprojectlevi@gmail.com) |
| 🌐 Platform | [projectlevi.co.uk](https://projectlevi.co.uk) |
| 💼 LinkedIn | [linkedin.com/company/project-levi](https://www.linkedin.com/company/project-levi) |

---

<div align="center">

*Stop guessing.Start building.*

<br/>

**© 2026 Project Levi**

</div>

# VERSPA V1.0 — Site Build Project

**Live domain:** verspa.co.uk
**Repo:** ol-s-cloud/VERSPA-V1.O
**Deployed via:** Netlify (connect this repo → auto-deploy on push)
**Design system:** v4 — Libre Baskerville + Plus Jakarta Sans + Space Mono · Ink #0B0C0E · Teal #0A6648 · Off-white #F7F6F2
**Logo:** Direction 04 — angled monogram V with teal serif cuts
**CRM:** HubSpot — all forms connect via HubSpot embed code
**Status:** 🔴 Building

---

## Repo structure

```
VERSPA-V1.O/
├── index.html                        ✅ Done (v4 + How It Works + FAQ)
├── launchpad.html                    🔴 To build
├── for-project-owners.html           🔴 To build
├── for-funding-partners.html         🔴 To build
├── book-a-call.html                  🔴 To build
├── apply.html                        🔴 To build
├── about.html                        🔴 To build
├── regulatory-status.html            🔴 To build
├── faq.html                          🔴 To build
├── contact.html                      🔴 To build
├── privacy-policy.html               🔴 To build
├── terms-of-use.html                 🔴 To build
├── cookie-policy.html                🔴 To build
├── disclaimer.html                   🔴 To build
├── thank-you-discovery-call.html     🔴 To build
├── thank-you-application.html        🔴 To build
├── thank-you-interest.html           🔴 To build
├── thank-you-contact.html            🔴 To build
├── assets/
│   └── brand/
│       ├── logomark-dark.svg         🔴 To add
│       ├── logomark-light.svg        🔴 To add
│       ├── logomark-teal.svg         🔴 To add
│       ├── favicon-16.svg            🔴 To add
│       ├── favicon-32.svg            🔴 To add
│       └── favicon-64.svg            🔴 To add
└── README.md                         ✅ This file
```

---

## Full page registry

### GROUP A — Core public pages (revenue + visa critical)

| # | File | URL | Priority | Status | Notes |
|---|------|-----|----------|--------|-------|
| 1 | `index.html` | verspa.co.uk/ | 🔴 Must | ✅ Done | v4 design, How It Works, FAQ, waitlist form |
| 2 | `launchpad.html` | verspa.co.uk/launchpad | 🔴 Must | 🔴 Build | Live revenue product. 12-week programme, pricing, apply CTA |
| 3 | `for-project-owners.html` | verspa.co.uk/for-project-owners | 🔴 Must | 🔴 Build | Developer journey, grant advisory, Launchpad entry |
| 4 | `for-funding-partners.html` | verspa.co.uk/for-funding-partners | 🔴 Must | 🔴 Build | Investor journey, diaspora rails, institutional detail |
| 5 | `book-a-call.html` | verspa.co.uk/book-a-call | 🔴 Must | 🔴 Build | HubSpot meeting embed (Calendly-style). Primary conversion page |
| 6 | `apply.html` | verspa.co.uk/apply | 🔴 Must | 🔴 Build | Combined application — Project Owner or Funding Partner |
| 7 | `about.html` | verspa.co.uk/about | 🔴 Must | 🔴 Build | Founder story, credentials, Cambridge Judge, Smart Metering, W3-Energy |
| 8 | `regulatory-status.html` | verspa.co.uk/regulatory-status | 🔴 Must | 🔴 Build | FCA pathway, what we can/cannot do now, transparency page |
| 9 | `faq.html` | verspa.co.uk/faq | 🟡 High | 🔴 Build | Full expanded FAQ (index.html has summary only) |
| 10 | `contact.html` | verspa.co.uk/contact | 🔴 Must | 🔴 Build | HubSpot general enquiry form, London address, LinkedIn |

### GROUP B — Thank-you / confirmation pages

| # | File | URL | Priority | Status | Notes |
|---|------|-----|----------|--------|-------|
| 11 | `thank-you-discovery-call.html` | verspa.co.uk/thank-you-discovery-call | 🔴 Must | 🔴 Build | Post book-a-call. Confirm, next steps, follow on LinkedIn |
| 12 | `thank-you-application.html` | verspa.co.uk/thank-you-application | 🔴 Must | 🔴 Build | Post apply. Confirm receipt, timeline, what happens next |
| 13 | `thank-you-interest.html` | verspa.co.uk/thank-you-interest | 🔴 Must | 🔴 Build | Post funding partner interest form |
| 14 | `thank-you-contact.html` | verspa.co.uk/thank-you-contact | 🔴 Must | 🔴 Build | Post general contact form |

### GROUP C — Legal / trust pages

| # | File | URL | Priority | Status | Notes |
|---|------|-----|----------|--------|-------|
| 15 | `privacy-policy.html` | verspa.co.uk/privacy-policy | 🔴 Must | 🔴 Build | UK GDPR compliant. Required before collecting any data |
| 16 | `terms-of-use.html` | verspa.co.uk/terms-of-use | 🔴 Must | 🔴 Build | Site terms, no investment advice disclaimer |
| 17 | `cookie-policy.html` | verspa.co.uk/cookie-policy | 🔴 Must | 🔴 Build | Cookie types, HubSpot cookies, consent |
| 18 | `disclaimer.html` | verspa.co.uk/disclaimer | 🔴 Must | 🔴 Build | Risk notice, capital at risk, not FCA authorised yet |

---

## Build order

Work page by page in this sequence. Each page is a GitHub Issue.

```
Issue #1  → index.html          ✅ Complete
Issue #2  → launchpad.html
Issue #3  → for-project-owners.html
Issue #4  → for-funding-partners.html
Issue #5  → about.html
Issue #6  → book-a-call.html
Issue #7  → apply.html
Issue #8  → regulatory-status.html
Issue #9  → contact.html
Issue #10 → faq.html
Issue #11 → thank-you-discovery-call.html
Issue #12 → thank-you-application.html
Issue #13 → thank-you-interest.html
Issue #14 → thank-you-contact.html
Issue #15 → privacy-policy.html
Issue #16 → terms-of-use.html
Issue #17 → cookie-policy.html
Issue #18 → disclaimer.html
Issue #19 → Logo assets → /assets/brand/
Issue #20 → HubSpot CRM integration across all forms
Issue #21 → Corrections pass — all pages reviewed and updated
Issue #22 → Deploy to verspa.co.uk via Netlify
```

---

## Design system reference

All pages inherit from `index.html` (v4). Copy the `<head>` font links, CSS variables and nav/footer exactly. Never change fonts, colours or spacing — correct content only.

**Fonts:** Libre Baskerville (headlines) · Plus Jakarta Sans (body/UI) · Space Mono (data)
**Palette:** Ink `#0B0C0E` · Off-white `#F7F6F2` · White `#FFFFFF` · Teal `#0A6648` · Border `#E3E1DA`
**Logo:** Direction 04 V mark (thick left arm, thin right arm, teal serif cuts at cap line)
**Nav:** Fixed, transparent → solid on scroll. Links: Launchpad · For Developers · For Investors · About · Book a Call (CTA button)
**Footer:** 4-column. FCA disclaimer on every page.

---

## HubSpot integration

**Portal ID:** [ADD YOUR PORTAL ID]
**Forms needed:**
- Discovery Call booking (or Calendly embed)
- Project Owner Application
- Funding Partner Interest
- General Contact / Enquiry
- Partner / Advisor Interest

Each form embed goes inside `<div id="hubspot-form"></div>` + HubSpot script. HubSpot handles redirect to thank-you page URLs.

---

## GitHub repos in use

| Repo | Purpose |
|------|---------|
| `ol-s-cloud/VERSPA-V1.O` | ✅ **This repo** — live site files for verspa.co.uk |
| `ol-s-cloud/FIV` | Innovator Founder visa tracker, business plan docs |
| `ol-s-cloud/VERSPA` | Older private repo — archive only |
| `ol-s-cloud/verspav1` | Older private repo — archive only |

**All new work goes into `VERSPA-V1.O` only.**

---

*Last updated: 25 March 2026*

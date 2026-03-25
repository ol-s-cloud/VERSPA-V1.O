# VERSPA V1.0 — Confirmed Page Map with Field Specs

All confirmed. Ready to build when instructed.
Repo: ol-s-cloud/VERSPA-V1.O
Design: v4 (Libre Baskerville + Plus Jakarta Sans)
Logo: Direction 04 — angled monogram V, teal serif cuts
CRM: HubSpot

---

## GROUP A — Core public pages

### 01 — index.html (Home)
- Status: ✅ Built (v4 + How It Works + FAQ)
- Form: Waitlist — 2 tabs (see specs/forms/06-waitlist-home.md)
- Pending: HubSpot embed + logo + corrections pass

### 02 — launchpad.html
- Status: 🔴 To build
- Purpose: 12-week investment readiness programme — live revenue product
- Form: Launchpad Application (see specs/forms/01-launchpad-application.md)
- Sections: Hero / What it is / What you get / Phases / Pricing / Who it's for / Apply CTA
- Pricing: £5,000–£15,000 + 2% success fee
- Redirect: /thank-you-application

### 03 — for-project-owners.html
- Status: 🔴 To build
- Purpose: Developer journey page — from raw project to financial close
- Form: Light enquiry (Name / Email / Project type / Country / Stage) → redirects to launchpad.html
- Sections: Hero / The journey / Services now / Services post-FCA / Launchpad CTA / Book a call CTA

### 04 — for-funding-partners.html
- Status: 🔴 To build
- Purpose: Investor page — retail, diaspora, institutional
- Form: Funding Partner Interest (see specs/forms/02-funding-partner-interest.md)
- Sections: Hero / Two tracks (retail vs institutional) / Diaspora rails / Returns framework / Risk disclosure / CTA
- Redirect: /thank-you-interest

### 05 — about.html
- Status: 🔴 To build
- Purpose: Founder story + credentials — critical for Envestors endorsing body
- Form: None. Single CTA → book-a-call.html
- Sections: Hero / Mission / Founder bio / Credentials / W3-Energy pivot story / Why VERSPA exists
- Key credentials: MSc Finance & Data Analytics / Smart Metering PLC (Metis.co.uk) / Cambridge Judge Cohort 17 / W3-Energy.org MVP / UK FLR Section C

### 06 — book-a-call.html
- Status: 🔴 To build
- Purpose: Primary conversion page — all CTAs across site lead here
- Form: Discovery Call Booking (see specs/forms/03-discovery-call-booking.md)
- Note: Use HubSpot Meetings embed if available; otherwise form + manual booking
- Redirect: /thank-you-discovery-call

### 07 — apply.html
- Status: 🔴 To build
- Purpose: Combined application — 3 tabs
- Tab 1: Project Owner (full Launchpad form)
- Tab 2: Funding Partner (full investor form)
- Tab 3: Partner / Advisor Interest
- Redirects: Tab 1 → /thank-you-application / Tab 2 → /thank-you-interest / Tab 3 → /thank-you-partner

### 08 — regulatory-status.html
- Status: 🔴 To build
- Purpose: Full transparency on FCA status — trust page
- Form: None. CTA → book-a-call.html
- Sections: Current status / What we DO now / What we CANNOT do yet / FCA pathway / ECSP ambition

### 09 — faq.html
- Status: 🔴 To build
- Purpose: Full expanded FAQ (20–30 questions, 8 categories)
- Form: None. CTA → contact.html
- Categories: About VERSPA / Regulatory / Investors-retail / Investors-diaspora / Investors-institutional / Developers / Launchpad / Technology

### 10 — contact.html
- Status: 🔴 To build
- Form: General Contact (see specs/forms/04-general-contact.md)
- Redirect: /thank-you-contact

---

## GROUP B — Thank-you pages (no forms)

### 11 — thank-you-discovery-call.html
- Confirmed: Call booked / What to expect / LinkedIn CTA / links to Launchpad + About

### 12 — thank-you-application.html
- Confirmed: Received / 3 business day review / What happens next / LinkedIn CTA

### 13 — thank-you-interest.html
- Confirmed: Registered / First to know at launch / Regulatory status link / LinkedIn CTA

### 14 — thank-you-contact.html
- Confirmed: Message received / 2 business days / LinkedIn CTA

### 15 — thank-you-partner.html
- Confirmed: We'll be in touch / LinkedIn CTA / links to About

---

## GROUP C — Legal pages (no forms)

### 16 — privacy-policy.html
- UK GDPR compliant / Who we are / Data collected / Legal basis / Retention / Rights / HubSpot as processor / Cookies link

### 17 — terms-of-use.html
- Informational only / Not financial advice / Not FCA authorised / No investment facilitation / IP / Liability / England & Wales

### 18 — cookie-policy.html
- Essential cookies / HubSpot cookies / Analytics / How to manage / Privacy policy link

### 19 — disclaimer.html
- Capital at risk / Not FCA authorised / Not financial advice / Past performance / Seek independent advice

---

## HubSpot — 6 forms summary

| Form | File | Spec |
|------|------|------|
| Waitlist (Investor) | index.html | specs/forms/06-waitlist-home.md |
| Waitlist (Developer) | index.html | specs/forms/06-waitlist-home.md |
| Launchpad Application | launchpad.html, apply.html tab 1 | specs/forms/01-launchpad-application.md |
| Funding Partner Interest | for-funding-partners.html, apply.html tab 2 | specs/forms/02-funding-partner-interest.md |
| Discovery Call Booking | book-a-call.html | specs/forms/03-discovery-call-booking.md |
| General Contact | contact.html | specs/forms/04-general-contact.md |
| Partner / Advisor Interest | apply.html tab 3 | specs/forms/05-partner-advisor-interest.md |

---

## Build order when ready

1. index.html — ✅ Done (add logo + HubSpot on corrections pass)
2. launchpad.html — first to build (live revenue)
3. for-project-owners.html
4. for-funding-partners.html
5. about.html
6. book-a-call.html
7. apply.html
8. regulatory-status.html
9. contact.html
10. faq.html
11–15. All thank-you pages
16–19. All legal pages
20. HubSpot integration pass
21. Corrections pass
22. Deploy → verspa.co.uk

---

Last updated: 25 March 2026
Status: Planning complete. Awaiting build instruction.

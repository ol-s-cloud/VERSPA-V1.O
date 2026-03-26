# VERSPA V1.0 — Master Data Matrix & Field Intelligence Map

Final agreed version. Locked before build.
Last updated: 26 March 2026

---

## CORE PRINCIPLE
Every field on every form must justify its existence with three things:
1. What it captures immediately
2. What intelligence it generates over time
3. What HubSpot action it triggers

If a field cannot answer all three — it does not belong on the form.

---

## FORM 0 — HOME (index.html)
Goal: minimum friction email capture + type identification
HubSpot form: VERSPA — Waitlist

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Identity | Name quality signals seriousness | Creates contact. Personalises all emails |
| Email address | Yes | CRM anchor | Domain = investor type signal. @gmail retail, institutional domain = upgrade | Creates contact. Triggers welcome sequence by type |
| I am a (Project Owner / Funding Partner / Other) | Yes | Role self-identification | Developer:Investor ratio = marketplace health metric. Target 1:5. Off ratio = one side needs more marketing | Tags contact type. Routes to correct sequence |

---

## FORM 1 — LAUNCHPAD APPLICATION
Goal: full qualification of project developer for 12-week programme
HubSpot forms: VERSPA — Launchpad Application
Used on: launchpad.html, apply.html tab 1
Redirect: /thank-you-application

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Developer identity | Cross-reference LinkedIn | Contact + Deal created |
| Email address | Yes | CRM anchor | Company email = registered entity signal | Creates contact. Triggers received sequence |
| Company / Project name | Yes | Entity name | Searchable. Verify Companies House | Becomes Deal name in pipeline |
| Website or LinkedIn | Optional | Online presence | Presence = credibility signal. Track % with/without over time | Saved to contact. Used for pre-call research |
| Project type | Yes | Solar/Wind/Hydro/Bioenergy/Storage/Other | Which types dominate pipeline. Shapes grant radar priorities. Tells you which verticals need more marketing | Tags deal. Triggers grant matching. Investor matching |
| Project country / region | Yes | Physical project location | Actual vs target geography. UK 90% = EMEA messaging not working. Nigeria dominant before EMEA launch = accelerate EMEA | Tags geography. Country-specific grant radar. Routes advisory track |
| Project stage | Yes | Early concept/Development/Ready to structure/Construction | Pipeline maturity metric. % ready to structure = immediate revenue. % early concept = pre-Launchpad product needed | Stage-based routing. Ready to structure = 48hr call. Early concept = 6-month nurture |
| Indicative funding need | Yes | Under £500k / £500k–£2M / £2M–£10M / £10M+ | Revenue intelligence. 2% success fee calculation. Average deal size × cohort size = revenue forecast | Calculates indicative fee. Tags deal size. £10M+ → institutional track |
| Funding purpose | Yes | Development/Construction/Equipment/Working capital/Refinance/Mixed | Determines product to sell. Development = deal structuring. Equipment = asset-backed. Refinance = different advisory. Shapes post-FCA product roadmap | Determines Launchpad scope and pricing. Triggers relevant content |
| Current funding status | Yes | Self-funded/Seeking first capital/Partially funded/In discussions/Grant-funded/Other | Most powerful qualifier. In discussions = hot lead, call within 24hrs. Self-funded = education needed. Grant-funded = compliance track | In discussions = priority flag 24hr follow-up. Self-funded = education sequence |
| Preferred funding type | Yes | Debt/Equity/Grant/Blended finance/Not sure | Not sure = Launchpad product exactly. Shapes instrument demand. Grant dominant = advisory entry point. Blended = sophisticated developer segment | Not sure = Launchpad education sequence. Grant = grant advisory track |
| CFR done? | Optional | Yes/No/In progress | No = immediate advisory revenue. Track % without CFR = size of standalone advisory market | No = CFR advisory pitch email. Yes = request document |
| Project description | Optional | Free text 2-3 sentences | Qualitative credibility signal. Language sophistication = developer experience. Anonymised descriptions form endorsing body pipeline evidence | Saved as Deal note. Reviewed manually within 48hrs |
| How did you hear about VERSPA? | Optional | LinkedIn/Google/Referral/Event/Press/Other | Marketing attribution before paid ads. Which organic channels to double down on. Referral % = build referral programme | Tags lead source. Feeds attribution report |

---

## FORM 2 — FOR PROJECT OWNERS light form
Goal: entry-level capture with CTA to full Launchpad application
HubSpot form: VERSPA — Project Owner Interest
Used on: for-project-owners.html
Redirect: inline success + CTA to launchpad.html

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Identity | — | Contact created |
| Email address | Yes | CRM anchor | Capture vs full application conversion rate. Target 40%+ proceed to Launchpad form | Contact. 24hr follow-up if no full application submitted |
| Project type | Yes | First type signal | Pipeline tagging begins before full application | Tags type. Pre-populates Launchpad form |
| Project country / region | Yes | First geography signal | Geographic pipeline intelligence from first touch | Tags geography. Country-relevant follow-up content |
| Project stage | Yes | Maturity signal | First-pass qualification | Ready to structure = immediate Launchpad CTA email |
| Indicative funding need | Yes | Capital scale signal | Revenue signal at entry. Large deals flagged early | Deal size tag. £10M+ flagged for founder review |

---

## FORM 3 — FUNDING PARTNER INTEREST
Goal: investor qualification and segmentation
HubSpot form: VERSPA — Funding Partner Interest
Used on: for-funding-partners.html, apply.html tab 2
Redirect: /thank-you-interest

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Identity | — | Contact created |
| Email address | Yes | CRM anchor | Domain intelligence. Institutional domain = upgrade automatically | HubSpot enrichment runs. Routes to correct sequence |
| Investor type | Yes | Retail/Family office/Institutional/DFI/Impact fund/Other | Marketplace capital stack composition. Institutional vs retail ratio. DFI interest = endorsing body evidence. Shows VERSPA is serious cross-border infrastructure not just crowdfunding | Routes to completely separate sequences. DFI/Institutional = founder personal outreach 24hrs. Retail = automated nurture |
| Investment range | Yes | £10–£1k through £250k+ / Institutional | Indicative capital pipeline. 200 investors × £5k avg = £1M indicative. Critical for endorsing body evidence and investor marketing | £250k+ = priority flag. Feeds indicative capital dashboard. Revenue tier routing |
| Primary geography of interest | Yes | UK/West Africa/East Africa/MENA/EU/All | Most powerful thesis validation metric. UK investors interested in West Africa = diaspora corridor confirmed commercially. MENA investors in UK wind = cross-border demand real | Investor-project matching. Cross-border flow report. Match list prepared for platform launch |
| Interested in geography-linked opportunities? | Yes | Yes/No | Replaces diaspora label cleanly. Yes = investor with personal geographic motivation. Captures same data without identity categorisation friction | Yes = routes to country-specific opportunity sequence. Geographic motivation report |
| Country of residence | Yes | Physical location | Combined with type + geography interest = full customer profile. UK + Yes + West Africa = core customer. German + Institutional + EU = ECSP priority | Geo-tags contact. Regulatory routing. UK = UK risk disclosures. Non-UK = jurisdiction review flag |
| Specific sectors or countries? | Optional | Free-text investment focus | Qualitative product demand intelligence. Aggregate = product roadmap the market is asking for | Saved to contact. Investment appetite signals |
| Prior alternative investment experience | Yes | Yes/No/Looking to start | Looking to start = first-time alternative investor = largest and most important segment. Determines education vs product-forward sequence. Without this field you cannot differentiate | Looking to start = education-first nurture. Yes = product sequence. Feeds investor sophistication report |

---

## FORM 4 — DISCOVERY CALL BOOKING
Goal: qualify call before it happens. Minimum friction.
HubSpot form: VERSPA — Book a Discovery Call
Used on: book-a-call.html
Redirect: /thank-you-discovery-call
Priority: All bookings = 24-hour follow-up maximum

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Identity | — | Contact created or updated |
| Email address | Yes | CRM anchor | — | Contact. Call confirmation sequence |
| I am a | Yes | Project developer/Investor/Institution/Advisor/Press/Other | Who is booking calls and at what volume. Press = narrative spreading. Advisor = ecosystem forming. Determines call agenda before it starts | Routes to correct pipeline. Press = founder-only. All = 24hr max follow-up |
| What would you like to discuss? | Optional | Specific question or agenda | If same question appears repeatedly = website not answering it. Content gap detector. Aggregate = market concerns map | Saved as meeting note. Reviewed before every call. Feeds content gap report |
| Preferred time zone | Optional | GMT/WAT/EAT/GST/EST | Geographic distribution of call-bookers. WAT frequent = West African engagement before EMEA launch | Used for scheduling. Geographic engagement report |

---

## FORM 5 — GENERAL CONTACT
Goal: catch-all for enquiries not covered by specific forms
HubSpot form: VERSPA — General Contact
Used on: contact.html
Redirect: /thank-you-contact
Response SLA: 2 business days

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Identity | — | Contact created |
| Email address | Yes | CRM anchor | — | Contact. Acknowledgement email |
| Organisation | Optional | Company or institution | Institutional contacts self-identify. DFI or bank via contact form = found you non-standard route | Company record. HubSpot enrichment |
| Enquiry type | Yes | Developer/Investor/Partnership/Press/Advisory/B2B/General | B2B before API built = Pillar 6 validated early. Press = narrative spreading. Partnership = ecosystem forming. Early indicator dashboard for which pillars generating interest | Routes to correct pipeline. Press = founder-only. B2B = B2B API pipeline |
| Subject | Yes | One-line description | Searchable. Pattern analysis reveals common themes | Routing and prioritisation |
| Message | Yes | Full enquiry | Qualitative intelligence. What is unclear, compelling, missing | Saved. Reviewed manually |
| How did you hear about VERSPA? | Optional | Attribution | Organic channel tracking | Tags lead source. Attribution report |

---

## FORM 6 — PARTNER / ADVISOR INTEREST
Goal: ecosystem evaluation, not lead capture
HubSpot form: VERSPA — Partner / Advisor Interest
Used on: apply.html tab 3
Redirect: /thank-you-partner

| Field | Required | What it captures | Intelligence over time | HubSpot action |
|-------|----------|-----------------|----------------------|----------------|
| Full name | Yes | Identity | — | Contact created. Partner pipeline |
| Email address | Yes | CRM anchor | — | Contact. Partner pipeline created |
| Organisation | Yes | Company or firm | Which firms approaching VERSPA. Types = which parts of ecosystem watching you | Company record. HubSpot enrichment |
| Role | Yes | Position | Seniority signal. Managing Partner vs Associate = institutional intent level | Saved. Informs outreach tone and priority |
| Country | Yes | Location | Geographic partner distribution. Lagos legal firms approaching = accelerate EMEA. Frankfurt compliance = EU pull | Tags geography. Regional partnership track |
| Partner type | Yes | Legal/Compliance/Carbon/Grants/EPC/Developer/Advisory/Payments/KYC/Other | Ecosystem composition. KYC approaching = market knows you need compliance. Carbon = VERSPA seen as carbon economy infrastructure. Shapes B2B API integration priorities | Tags partner type. Ecosystem composition report |
| What do you offer? | Yes | Specific capability | Qualitative capability mapping. Aggregate = partner marketplace in embryo | Saved to partner record. Fit assessment |
| Regions covered | Yes | Geographies covered | Coverage depth mapping. Multi-region partner > single region. Aggregate = where ecosystem has depth vs gaps | Tags coverage. Partner coverage map |
| Relevant experience | Yes | Renewable energy track record | Qualification criterion. Deep RE experience = immediate Launchpad client value | Saved for qualification. Partner tier assignment |
| Website or LinkedIn | Yes | Online presence for due diligence | Required for all partner relationships | Saved. Due diligence review before any partnership |
| Why partner with VERSPA? | Yes | Motivation | Transactional vs mission-aligned. Quality of motivation = partnership tier signal | Saved. High quality = founder review flag. Informs partnership strategy |

---

## WEEKLY REPORTING DASHBOARD — 10 metrics

| Metric | Source | Target | Decision it drives |
|--------|--------|--------|-------------------|
| Marketplace ratio (Developer:Investor) | I am a + all form types | 1:5 | Which side needs more marketing |
| Pipeline maturity | Project stage | 40%+ Development or Ready | Pre-Launchpad product decision |
| Indicative capital pool | Investment range | Growing weekly | Project fundability. Endorsing body narrative |
| Geographic coverage | Project country + Investor geography | UK + 2 EMEA active | EMEA expansion timing |
| Revenue pipeline | Funding need + stage | £X indicative fees | Cash flow. Hiring. Runway |
| Acquisition channels | How did you hear | LinkedIn dominant pre-ads | Ad spend allocation |
| Geography-linked interest | Interested in geography-linked? | 30%+ Yes | Country product prioritisation |
| First-time investor rate | Prior alternative experience | Track weekly | Educational content volume |
| Partner ecosystem health | Partner type distribution | All key types represented | B2B API integration priorities |
| Call conversion rate | Book a call submissions | 60%+ | Page redesign decision |

---

Status: LOCKED AND AGREED
Next step: Build pages in order starting with launchpad.html

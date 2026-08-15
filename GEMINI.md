# Dr. Chandrashekar P Portfolio Website — Project Context & Plan

## Client Context
* **Client:** Dr. Chandrashekar P (Orthopaedic & Robotic Joint Replacement Surgeon, Bengaluru)
* **Agency:** Octmark Technologies, Hyderabad, India
* **Role/Affiliation:** Founder of International Knee & Orthopaedic Centre (IKOC), Head of Orthopaedics at Sakra World Hospital
* **Target Audience:** Patients seeking joint replacements, robotic knee surgeries, sports injuries care, and meniscus procedures.
* **Goal:** A premium, trust-evoking, high-performance, single-scroll portfolio website that acts as a conversion engine for appointments (via Practo/WhatsApp/Phone).

---

## 1. Design System & Brand Identity

### Design Language
* **Aesthetics:** Minimal, editorial medical. Meticulous clean grids, thin rules, generous whitespace, warm reassuring tones combined with surgical precision cues.
* **Typography:** 
  * Headings: `Poppins` (clean, modern sans-serif headings — aligned with ikoc.in)
  * Body & Controls: `Open Sans` (highly legible sans-serif body — aligned with ikoc.in)
* **Colors:**
  * Primary: Deep Brand Blue (`#073d5b`) — Anchors brand (aligned with IKOC)
  * Secondary: Royal Brand Blue (`#0068ae`) — Surface highlights, secondary buttons
  * Accent: IKOC Gold (`#f2b301`) — CTAs, links, highlights (from official logo)
  * Accent (Deep): Deep Gold (`#d9a000`) — Hover/pressed states, high contrast WCAG compliance
  * Backgrounds: Softer Warm Background (`#faf8f5`) and Blue Tint (`#f4f7f9`) — Clean and premium
  * Text: Ink (`#1e2e39`) (body) and Slate Grey (`#5e7180`) (muted/captions)
  * Borders/Dividers: Line (`#d2dbe1`)

### Spacing & Shapes
* Grid: 12-column, max width `1200px`
* Border Radius: Cards `14px`, Buttons pill (`999px`), Inputs `10px`
* Elevation: Low and soft shadows

---

## 2. Information Architecture (Single Scroll Layout)

The website is structured as a single-page scroll with 17 sections.

1. **Header / Nav:** Sticky navigation with Book CTA.
2. **Hero:** Split desktop layout (headline & subhead left, portrait right) + trust strip.
3. **Trust Strip:** Small band displaying core credential chips.
4. **About:** 2-column detailed bio.
5. **Areas of Expertise:** 3x2 card grid detailing the doctor's focus areas.
6. **Robotic & Computer-Assisted Joint Replacement:** Highlighting precision, benefits, and the imageless AI TKR.
7. **Innovations & Milestones:** Timeline showcasing pioneer achievements (MISSO, AI-guided knee replacement).
8. **Experience in Numbers:** Stat band with large numbers.
9. **Education, Training & Positions:** 2-column credential listing.
10. **Publications & Research:** Scholarly citations emphasizing E-E-A-T.
11. **In the Media:** Cards linking to press coverage.
12. **Videos & Conversations:** Embed grid featuring *IKOC Diaries* and Sakra explainers.
13. **Patient Experiences:** Testimonials with compliance disclaimers.
14. **Conditions & Procedures:** Two tag lists for SEO optimization.
15. **Frequently Asked Questions:** Accordion-based FAQs.
16. **Locations & Booking:** Direct access to clinics (IKOC & Sakra World Hospital) and Practo booking.
17. **Footer:** Quick links, credentials, and legal medical disclaimers.

---

## 3. SEO & Compliance Guardrails

### SEO Best Practices
* **Primary Keyword:** `robotic knee replacement surgeon Bangalore`
* **Heading Structure:** Exact H1 for hero, H2s for sections, H3s for cards and FAQs.
* **Structured Data:** Physician & FAQ JSON-LD schemas embedded in `<head>`.
* **Semantics:** HTML5 landmarks (`<header>`, `<main>`, `<section>`, `<footer>`).

### Compliance Rules (NMC / ASCI)
* **No guarantees:** Avoid outcome-guarantee language (use "can/may help").
* **No unverified superlatives:** Do not use self-declared "best orthopaedic surgeon".
* **Surgical Figures:** Must keep one canonical set:
  * 50,000+ orthopaedic surgeries
  * 10,000+ joint replacements
  * 3,000+ robotic knee replacements
  * 10,000+ meniscus repairs
* **Disclaimers:** Mandatory disclaimers on Patient Experiences and Footer.

---

## 4. Build Plan & Stack

* **Stack:** Static HTML, Tailwind CSS, Alpine.js for interactive elements (FAQ accordions, mobile navigation drawer).
* **Dependencies:** Tailwind CSS, Alpine.js, Lucide Icons.
* **Responsiveness:** Mobile-first layout with a sticky bottom CTA bar (Book / Call) on screens `< 640px`.
* **Git flow:** Strictly request confirmation before commit or push, showing full diff first.

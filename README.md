# CARS24 AI Assistant — Prototype

An interactive prototype demonstrating an AI-powered conversational assistant embedded across the CARS24 Australia car buying journey — from discovery through to home delivery.

Built as a PM initiative to expand on a proven AI test drive booking bot (+34% conversion uplift) across the full purchase funnel.

---

## Live Demo

👉 **[View live prototype](#)** *(replace with your Netlify URL after deploying)*

---

## The Problem

CARS24 AU launched an AI bot for test drive bookings and saw a **+34% uplift in conversion**. The opportunity was clear — but the bot only covered one moment in the journey.

Customers still had unanswered questions and drop-off at every other stage:

- **Before booking** — "What car suits my budget? Can I get finance?"
- **Booking → Reservation** — "How do I hold this car? What documents do I need?"
- **Reservation → Delivery** — "Where's my car? What happens next?"

---

## The Solution

A contextual AI assistant that activates at the right moment on every page — with stage-aware conversations, smart quick replies, and handoffs to real actions (finance pre-approval, document upload, delivery scheduling).

---

## Journey Coverage

| Stage | Entry Point | Bot Behaviour |
|---|---|---|
| Pre-booking | Home page, Listing page, Car detail page | Helps with discovery, finance estimates, test drive booking |
| Booking → Reservation | Checkout page | Guides deposit, documents, pre-approval redirect |
| Reservation → Delivery | My Order page | Tracks progress, schedules delivery, answers status questions |

---

## Features

- **5 navigable pages** — Home, Browse, Car Detail, Checkout, My Order
- **Stage-aware bot** — conversation context changes automatically based on which page the user is on
- **Contextual entry points** — "Book test drive" on the car detail page opens the bot and fires the flow directly
- **Finance pre-approval redirect** — links to the real [CARS24 pre-approval page](https://www.cars24.com.au/financing/get-pre-approval/)
- **Delivery tracker** — visual step-by-step progress post-reservation
- **Quick reply chips** — full journey walkable without typing
- **CARS24 brand colours** — purple `#3D1F8F` and green `#1FAD6B`

---

## How to Run

No build step needed. Single HTML file.

```bash
# Option 1 — open directly in browser
open cars24_website_bot.html

# Option 2 — serve locally
npx serve .
```

Or deploy instantly via [Netlify Drop](https://app.netlify.com/drop) — drag and drop the HTML file.

---

## Files

```
├── cars24_website_bot.html   # Full prototype (single file, no dependencies)
└── README.md
```

---

## Context

This prototype was built to present an AI expansion roadmap to leadership — showing how a proven bot use case (test drive booking) could extend across the full customer lifecycle to drive conversion at every stage.

**PM:** Exploring product-led AI integration across the CARS24 AU buying funnel  
**Stack:** Vanilla HTML/CSS/JS — intentionally dependency-free for easy sharing and deployment

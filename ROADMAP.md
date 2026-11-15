# AI and Technology Roadmap for a Real Estate Brokerage in Chiriquí

**The first 90 days of a Chief Information Officer**

Alain Guerra, Boquete, Chiriquí. November 2026.

## Summary

A brokerage with thousands of listings and a mostly foreign clientele wins or loses on three things technology can move: how fast a buyer gets a useful answer, how much of an agent's day goes to selling instead of paperwork, and whether client money and data stay safe through closing.

This plan spends the first 30 days measuring and securing, the next 30 running two small pilots against those measurements, and the last 30 scaling what worked and putting rules around it. It commits to no large purchase before day 60.

The working demo in this repository is pilot 1 in miniature: a bilingual assistant that qualifies a buyer, answers process questions from attorney-reviewed content, and hands the agent a scored lead file.

## What this plan assumes

I wrote this from public information only. I have not seen the company's systems, contracts or numbers, so every target below is stated as "baseline first, then target." The first job is to find out which of these assumptions are wrong.

- Buyers are largely foreign, write in English or Spanish, and often inquire from another time zone.
- Leads arrive through several channels (website, portals, WhatsApp, email, walk-ins) and are not all captured in one place.
- Listing data lives in more than one system and is re-typed between them.
- Closings involve large wire transfers coordinated by email, which is the pattern payment fraud targets.

## Principles

1. **Measure before buying.** No tool is adopted without a baseline number it is supposed to improve.
2. **Start next to revenue.** The first projects shorten the path from inquiry to showing.
3. **AI drafts, people decide.** Anything a client reads about price, law or availability is either reviewed by a person or drawn from reviewed content.
4. **Client data is an asset the company is liable for.** Panama's Law 81 of 2019 applies to every lead form and every chat.
5. **Agents are the customer.** If the sales team does not use it, it failed.

## Days 1 to 30: listen, measure, secure

**Understand the business**

- Sit with agents, listing coordinators, administration and the owners. Ask each: what do you re-type, what do you wait for, what do you lose?
- Follow one lead from first message to closing and write down every handoff and every system it touches.

**Inventory**

- Systems, vendors, contracts, renewal dates and monthly cost.
- Where client data lives, who can reach it, and how long it is kept.
- Accounts and access for current and former staff.

**Baselines**

| Metric | Why it matters |
|---|---|
| Time to first response on a new inquiry, by channel and hour | Speed of reply is the cheapest conversion lever |
| Share of inquiries that reach a showing | The funnel number everything else serves |
| Share of leads with complete data in the CRM | Tells us how much is being lost between channels |
| Hours per week agents spend on listing descriptions, translations and data entry | Sizes the automation opportunity |
| Days from signed listing agreement to published listing | Inventory speed |

**Security quick wins (low cost, done in weeks)**

- Multi-factor authentication on email, CRM and banking.
- A password manager for the whole team.
- Tested backups of listings, contracts and client records.
- A written procedure for closings: payment instructions are never changed by email, and any account is confirmed by phone to a known number.
- Access removed the day someone leaves.

**Deliverable at day 30:** a ten-page findings report with the baselines, a risk register, and the two pilots proposed with their cost.

## Days 31 to 60: two pilots

Each pilot runs with a small group of volunteer agents, has one metric, and has a date on which it is kept, changed or dropped.

**Pilot 1: bilingual lead assistant**

- What it does: answers website and WhatsApp inquiries in English or Spanish at any hour, asks the qualifying questions, answers process questions from an attorney-reviewed knowledge base, and writes a scored lead into the CRM.
- What it does not do: quote prices that are not in the inventory, give legal advice, or negotiate.
- Metric: time to first response, and share of leads arriving in the CRM with complete data.
- The demo in this repository shows the flow, the scoring and the consent step.

**Pilot 2: listing content with human review**

- What it does: drafts listing descriptions in English and Spanish from the agent's notes and photos, in the house style, with a fact checklist the agent confirms before publishing.
- Metric: hours per listing and days from agreement to published.

**In parallel**

- An AI use policy of one page: which tools are approved, what client data may never be pasted into them, and who reviews what.
- A privacy review of every lead form and chat: consent text, purpose, retention, and how a client asks for deletion.

**Deliverable at day 60:** pilot results against baseline, with a recommendation for each.

## Days 61 to 90: scale and govern

- Roll out the pilots that met their metric to the full team, with short hands-on training by office.
- A one-page dashboard for the owners with the five baseline metrics, updated weekly.
- Vendor review: consolidate overlapping tools, and check every contract for data ownership and exit terms.
- An incident response plan: who decides, who calls the bank, who tells clients, in the first hour of a breach or a fraudulent transfer.
- A 12-month roadmap with budget, based on what the 90 days showed. Candidates: a single source of truth for listings, document automation for closings, market reports by area generated from the company's own data.

**Deliverable at day 90:** the 12-month roadmap and budget, presented to ownership.

## Risks and how they are handled

| Risk | What it looks like here | Control |
|---|---|---|
| Payment fraud at closing | A spoofed email changes wire instructions | Call-back verification, written procedure, bank promise letters or escrow, staff drills |
| Wrong answer to a client | The assistant states a price or legal point that is false | Answers restricted to inventory and reviewed content, handoff to a person outside that scope, logged conversations |
| Personal data exposure | Lead data pasted into unapproved tools or kept without consent | AI use policy, consent records, data minimization, access by role |
| Low adoption | Agents keep their own spreadsheets | Volunteers first, tools that save them time on day one, owners using the dashboard |
| Vendor dependence | Listings or leads trapped in one platform | Export tested before signing, data ownership in the contract |

## Governance

Controls follow ISO/IEC 27001:2022, sized for a company of this scale: an asset inventory, access control, backups, supplier management, incident response and awareness training. Decisions and accountability follow COBIT 2019: each system has a named business owner, and technology spending is tied to a business metric. I designed a plan on these two frameworks for IPACOOP in 2026, which adopted it as policy.

## What I would need from ownership

- Access to systems and vendor contracts in the first week.
- Two hours with each team in the first month.
- Three to five volunteer agents for the pilots.
- A modest pilot budget, approved at day 30 against the findings report.
- One decision-maker for technology questions.

## About the author

I am an attorney licensed in Panama with a technical degree in cybersecurity from Universidad del Istmo (2026), and I live in Boquete. I have handled property matters as a lawyer, including the separation of property, the sale of co-ownership shares and mortgage cancellations. I worked one year in fraud and consumer protection for Capital One through Foundever, and I designed an ISO 27001:2022 and COBIT 2019 security plan that IPACOOP adopted as policy. I spoke on artificial intelligence at the Chamber of Commerce in March 2026. I work in Spanish and English (C1).

Contact: alain.abogado507@gmail.com, +507 6103-2102, [github.com/Alain507](https://github.com/Alain507)

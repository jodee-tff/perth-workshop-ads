# Perth AI Mastery Workshop — Meta Ads Campaign

## Project Overview

A Meta (Facebook & Instagram) advertising campaign to drive registrations for the Perth AI Mastery workshop. This project contains all ad creative, copy variations, audience targeting strategies, campaign structure, and performance tracking for the workshop promotion.

## Workshop Details

- **Event:** AI Mastery Workshop
- **Location:** Perth, Western Australia
- **Target audience:** Business professionals, leaders, and entrepreneurs in Perth who want to understand and leverage AI in their work
- **Key value proposition:** Hands-on, practical AI training delivered by an experienced keynote speaker and AI trainer

## Campaign Goals

- Drive workshop registrations at a target cost-per-registration
- Build awareness of the AI Mastery brand in the Perth market
- Test and iterate on ad creative, copy, and audiences to find winning combinations
- Retarget engaged users who didn't convert on first touch

## Campaign Structure

### Funnel Stages

```
1. AWARENESS (Top of Funnel)
   └── Broad reach ads introducing the workshop concept
       - Video ads (short-form, 15–30 sec)
       - Image carousel ads (key takeaways / what you'll learn)

2. CONSIDERATION (Middle of Funnel)
   └── Retarget engaged users with social proof and detail
       - Testimonial / credibility ads
       - "What you'll learn" breakdown ads
       - Speaker authority positioning

3. CONVERSION (Bottom of Funnel)
   └── Direct registration push
       - Urgency / scarcity ads (limited seats, early bird pricing)
       - Retarget video viewers, page visitors, engaged users
       - Clear CTA → registration landing page
```

### Audience Targeting

| Audience | Description |
|---|---|
| Geo-targeted | Perth metro area + surrounding suburbs |
| Interest-based | AI, machine learning, business technology, professional development, entrepreneurship |
| Lookalike | Based on past workshop attendees or email list (when available) |
| Retargeting | Website visitors, video viewers (25/50/75%), engaged with page/ads |
| Custom | Business owners, C-suite, managers (job title targeting) |

## Project Structure

```
/creative/
  /images/          — Ad image assets and designs
  /videos/          — Video ad assets (raw + edited)
  /thumbnails/      — Video thumbnail options

/copy/
  /awareness/       — Top-of-funnel ad copy variations
  /consideration/   — Mid-funnel ad copy variations
  /conversion/      — Bottom-of-funnel ad copy variations
  /headlines/       — Headline variations for testing

/audiences/
  audience-definitions.md   — Detailed audience targeting specs
  exclusions.md             — Audience exclusion rules

/campaigns/
  campaign-structure.md     — Full campaign/ad set/ad hierarchy
  budget-allocation.md      — Budget split across funnel stages
  schedule.md               — Flight dates and pacing

/performance/
  /weekly-reports/          — Weekly performance summaries
  tracking-setup.md         — Pixel, conversions API, UTM conventions

/landing-page/
  copy-brief.md             — Landing page messaging and structure
  cta-variations.md         — CTA text and button options
```

## Ad Copy Guidelines

- **Tone:** Confident, approachable, practical — not hype-driven
- **Core message:** AI is a practical skill, not a buzzword. This workshop gives you hands-on mastery.
- **Pain points to address:**
  - Feeling left behind by AI advancements
  - Not knowing where to start with AI for business
  - Wanting practical skills, not theory
  - Perth-specific: limited local AI training options
- **Avoid:**
  - Fear-mongering about AI replacing jobs
  - Overly technical language
  - Generic "learn AI" messaging without specificity
  - Clickbait or misleading claims
- **Always include:**
  - Perth / local relevance
  - Specific outcomes or takeaways
  - Clear CTA (Register Now, Save Your Seat, etc.)

## Key Conventions

- Ad copy files use markdown with clear variant labelling (V1, V2, V3…)
- Each copy variant includes: headline, primary text, description, CTA
- Performance data stored as markdown tables in `/performance/weekly-reports/`
- All dates in YYYY-MM-DD format
- File names use kebab-case

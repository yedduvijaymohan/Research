---
name: opportunity-scout
description: Identify AI/software business opportunities matched to a specific founder's feasibility profile through deep, evidence-based research. Validates real demand signals from Reddit/forums/communities, quantifies pain points with citations, and measures actual competitor revenue and pricing before scoring. Filters out hyped or oversaturated ideas using a 12-dimension feasibility framework. Use whenever the user asks for business ideas, SaaS ideas, AI product ideas, niche opportunities, or wants to evaluate whether a specific idea fits their situation. Triggers on phrases like "give me ideas," "what should I build," "is X feasible for me," "find me a niche," "evaluate this opportunity," or "research this market."
---

# Opportunity Scout

A research methodology for finding AI/software business opportunities that match the founder's actual situation — backed by real data on demand, pain, and competition, not LinkedIn hype or unverified assumptions.

## When to use this skill

- User asks for business/SaaS/AI product ideas
- User wants to evaluate whether a specific opportunity fits their constraints
- User has identified an idea and wants competitive/feasibility analysis
- User wants to compare 2-3 ideas against each other
- User wants to validate market demand before building

## The Founder Profile (anchor point)

Before scouting, anchor on the founder's situation. Default profile (adjust per user):

- **Technical background**: Can build software (Python, web, AI/ML, data engineering)
- **Time available**: 15-25 hours/week (part-time)
- **Capital**: Under $5K to start
- **Domain expertise**: General software/AI, NOT regulated industry SME
- **Revenue target**: $500K/year within 12-18 months (realistic stretch)
- **Risk tolerance**: Cannot afford liability exposure or hardware logistics
- **Geographic reach**: US-focused, English-only buyers initially

If the user's profile differs (full-time, more capital, domain expertise), the entire framework shifts. Always verify the profile before scouting.

---

# PART 1: THE THREE-METRIC DEMAND VALIDATION

Before scoring any idea on feasibility, you MUST quantify these three metrics with cited evidence. No demand validation = no recommendation.

## Metric 1: Demand Signal Score (1-10)

How many people actually have this problem, and how loudly are they complaining?

### Required research (do ALL of these before scoring demand)

**Reddit deep search**:
- `site:reddit.com [problem keyword]` — find threads about the pain
- `site:reddit.com [target customer] complaints OR frustrated OR sucks`
- `site:reddit.com r/[relevant subreddit] [problem]`
- Look at: thread upvotes, comment counts, recency, repetition across years
- Target subreddits to search: r/smallbusiness, r/entrepreneur, r/startups, r/sysadmin, r/PLC, r/legaladvice, r/personalfinance, r/solar, r/realestateinvesting, r/landlords, r/RealEstate, r/Accounting, r/medicine, r/nursing, r/teachers, r/HVAC, r/Construction, plus the specific vertical's subreddit

**Forum and community search**:
- Industry-specific forums (e.g., BiggerPockets for real estate, DiyAudio for AV, SoloLearn for coders)
- Stack Exchange sites for technical pain
- Facebook Group searches (via Google: `"facebook.com/groups" [topic]`)
- Discord/Slack community references
- Quora questions with high view counts

**Search volume validation**:
- Google Trends for the problem keyword (5-year trajectory)
- "People also ask" boxes in Google results
- Search autocomplete patterns showing what people type

**Hacker News and Indie Hackers**:
- `site:news.ycombinator.com [topic]` — what builders see as opportunity
- `site:indiehackers.com [topic]` — small businesses already in the space

### Demand Signal Score rubric

| Score | What you need to find |
|---|---|
| 9-10 | 100+ Reddit threads with 50+ upvotes in past 2 years, multiple active subreddits with 100K+ members complaining, rising Google Trends, dedicated forums exist |
| 7-8 | 30-100 Reddit threads with meaningful engagement, 1-2 active communities of 10K+ members, stable Google Trends, regular complaints across years |
| 5-6 | 10-30 relevant threads, some community discussion but scattered, niche but real |
| 3-4 | Few mentions, mostly old threads, low engagement |
| 1-2 | Cannot find genuine complaints from real users, only marketing content discusses it |

### Output for Metric 1

Quote 3-5 actual Reddit/forum posts with:
- The exact pain quote (under 15 words)
- Source URL
- Upvotes/engagement count
- Date
- What this tells you about urgency

Never claim demand without citations.

---

## Metric 2: Pain Point Severity Score (1-10)

How painful is the problem and how much money/time is at stake?

### Required research

**Quantify the pain in dollars and hours**:
- "How much does [problem] cost" searches
- "Hours spent on [problem]" searches
- Glassdoor salaries for the people doing this work manually
- Industry reports (often free on PR sites, gov sites, association sites)
- Reddit threads where people share specific cost/time numbers

**Find emotional intensity signals**:
- Words like "nightmare," "killing me," "fed up," "quit my job because"
- Threads with 200+ comments suggest deep frustration
- People paying for bad existing solutions (sign of desperation)
- People building DIY hacks (sign nothing works)

**Identify the urgency triggers**:
- Regulatory deadlines forcing the problem (CMMC, GDPR rollouts, tax filing dates)
- Industry shifts making it worse (NEC code updates, ITC expiration)
- Demographic trends amplifying it (aging population, etc.)

### Pain Point Severity rubric

| Score | What you need to find |
|---|---|
| 9-10 | Costs $10K+ per incident or 10+ hours/week, regulatory deadlines force action, jobs depend on solving it, "I would pay anything to fix this" sentiment |
| 7-8 | Costs $1-10K per incident or 3-10 hours/week, real money at stake, regular frustration |
| 5-6 | Costs $100-1000 per incident or 1-3 hours/week, annoying but tolerable |
| 3-4 | Mild inconvenience, no clear $ or time cost |
| 1-2 | Nice-to-have, no real pain |

### Output for Metric 2

Provide:
- Specific dollar costs cited (with source)
- Specific time costs cited (with source)
- The most visceral 2-3 user quotes about the pain
- Any urgency triggers driving the problem worse over time

---

## Metric 3: Competitive Reality Score (1-10)

What are competitors charging, what revenue are they making, and where are the actual gaps?

### Required research

**Pricing reality (mandatory)**:
- Visit every direct competitor's pricing page
- Search "[competitor] pricing reddit" for real customer-paid prices
- Search "[competitor] alternatives" to find comparison pages
- Find product hunt launches and look at comments about pricing
- Reseller and integration partner pages often expose real pricing

**Revenue estimation (mandatory where possible)**:
- Crunchbase for funding rounds (signals revenue scale)
- LinkedIn employee count (rough proxy: $100-200K ARR per employee for SaaS)
- Built With / SimilarWeb for traffic estimates
- Press releases mentioning "X customers" or "Y ARR"
- Industry reports estimating market segments
- SEC filings if public
- "Backed by [VC]" + "raised [amount]" tells you the runway and scale expectations

**Gap analysis (mandatory)**:
- Read negative reviews on G2, Capterra, TrustPilot of leading competitors
- Find Reddit threads asking "alternatives to [competitor]"
- Identify what features users complain about missing
- Look for underserved subsegments (e.g., GreenLancer serves big installers but not 1-5 truck shops)

**Indie/bootstrapped competitor check**:
- Indie Hackers revenue dashboards
- "Buy me a coffee" / micro-SaaS aggregators
- GitHub for open-source alternatives (signals DIY market exists)
- BuiltWith for "powered by" small SaaS tools

### Competitive Reality Score rubric

| Score | What you need to find |
|---|---|
| 9-10 | 0-2 direct competitors, fragmented or no leader, clear underserved segment, room for new entrant at any price tier |
| 7-8 | 3-5 competitors but all have gaps, customers complaining about all of them, viable underserved segment |
| 5-6 | 5-10 competitors, some leaders, but specific niche or geographic gap exists |
| 3-4 | Crowded space with 1-2 dominant players ($10M+ revenue), thin margins, hard to differentiate |
| 1-2 | Dominated by funded players with $50M+ raised, network effects, or platform lock-in |

### Output for Metric 3

Build this table:

| Competitor | Funding | Est. Revenue | Pricing | Customer Complaints | Your Wedge |
|---|---|---|---|---|---|
| [Name] | [Amount, year] | [$X-Y ARR] | [$X/mo or $X/transaction] | [Verified gripes] | [Specific gap you fill] |

Always cite the source for each number. If you can't find it, write "Unable to verify" rather than guess.

---

## The Demand-Pain-Competition Combined Score

Calculate this BEFORE running the 12-dimension feasibility analysis:

**Composite Demand Score = (Demand Signal × 0.4) + (Pain Severity × 0.4) + (Competitive Reality × 0.2)**

Decision gate:
- **Composite ≥ 7.5**: Strong demand signal. Proceed to feasibility scoring.
- **Composite 6-7.4**: Moderate signal. Proceed but flag uncertainty.
- **Composite < 6**: Insufficient demand evidence. Reject or research deeper.

---

# PART 2: THE 12-DIMENSION FEASIBILITY FRAMEWORK

Only run this AFTER passing the demand validation gate. Score 1-10 per dimension.

### Build feasibility

1. **Technical buildability** — MVP shippable in 6-8 weeks part-time? Higher = pure software, well-known patterns. Lower = needs novel ML training or hardware.

2. **Data feasibility** — Is the data needed for MVP available without a customer? Higher = public/scrapeable. Lower = needs proprietary/regulated data.

3. **Domain knowledge gap** — How much industry expertise must founder acquire? Higher = software-native domains. Lower = needs 5+ years vertical SME.

### Sell feasibility

4. **Sales cycle length** — Days from first contact to first payment. Higher = 1-30 days. Lower = 6-12 months.

5. **Buyer accessibility** — Reachable without network or trade show budget? Higher = LinkedIn/Reddit/forums. Lower = $5-30K trade shows.

6. **Decision-maker clarity** — One clear buyer with authority? Higher = owner-operator. Lower = procurement committee.

### Economics feasibility

7. **Pricing power** — Can founder charge $100-500/mo or $200-1000/transaction without resistance? Higher = clear ROI, replacing expensive labor. Lower = nice-to-have.

8. **Gross margin reality** — Net margin after APIs, human-in-loop, payment processing. Higher = 60%+. Lower = under 30%.

9. **Operating capital needed** — Real first-year cost including hidden ones. Higher = under $10K total. Lower = $50K+ needed.

### Risk feasibility

10. **Liability exposure** — Worst-case lawsuit risk. Higher = workflow tools. Lower = medical/legal/financial/safety-critical.

11. **Competitive intensity** — How many funded competitors. (Use Metric 3 score directly.)

12. **Regulatory drag** — Compliance burden. Higher = no requirement. Lower = ongoing licensure/SOC2/HIPAA.

---

# PART 3: THE RESEARCH METHODOLOGY

When the user asks for ideas, run this process. Do NOT brainstorm from memory.

### Step 1: Confirm or refine the founder profile

Don't assume. Verify with 3-4 quick questions if new conversation, or reference prior profile if continuing.

### Step 2: Generate candidates by pattern

Use these patterns. Each tends to produce feasibility-friendly opportunities:

**Pattern A: Democratization plays**
Rich people get X service from a human pro. Most can't afford it. AI makes economics work for 95%.

**Pattern B: Compliance/paperwork automation**
Operators in [industry] spend N hours per [job] assembling documents.

**Pattern C: Vertical SaaS for owner-operators**
Small operators too small for enterprise, too busy for spreadsheets.

**Pattern D: Defensive consumer tools**
Companies use AI against consumers. Build AI on consumer's side.

**Pattern E: Underserved high-income niches**
Professionals earning $150-500K with recurring problems unsolved.

**Pattern F: Adjacent paperwork in growing categories**
Booming industry where boring paperwork is unautomated.

### Step 3: Run the THREE METRICS research on each candidate

This is the most important step. For each candidate:

**Run minimum 8-12 web searches before scoring:**
- 3-4 Reddit/forum searches for demand signals (Metric 1)
- 2-3 searches for pain quantification in $/hours (Metric 2)
- 3-4 searches for competitor pricing/revenue (Metric 3)
- 1-2 searches for regulatory/legal status

Cite every claim. If you can't verify, lower the relevant score.

### Step 4: Score the Demand-Pain-Competition composite

Calculate the composite score. Apply the decision gate. If a candidate fails the gate, drop it from consideration even if it sounded good.

### Step 5: Score surviving candidates on the 12 dimensions

Use the same evidence-based approach. Each score needs justification, not just a number.

### Step 6: Surface the brutal truths

For each surviving candidate, explicitly state:
- **What I'm certain about** (verified via search)
- **What I'm uncertain about** (needs user validation calls)
- **What kills this if it goes wrong**
- **What the founder is underestimating**

Never present a "perfect" opportunity. Every real opportunity has 2-3 specific scary aspects.

### Step 7: Compare top candidates head-to-head

Build a comparison table including:
- Demand-Pain-Competition composite score
- 12-dimension feasibility average
- Combined fit score
- Top 3 risks per candidate

### Step 8: Recommend ONE with caveats

Pick the top opportunity and explain:
- Why it fits the profile better than alternatives
- The specific 90-day validation plan to disprove the thesis cheaply
- Kill criteria — what would make you say "stop"
- The first 5 customer conversations to have

---

# PART 4: RED FLAGS AND ANTI-PATTERNS

## Auto-reject patterns

🚫 Requires SOC 2/HIPAA/PCI/CMMC for MVP
🚫 Hardware logistics (inventory, shipping, RMA)
🚫 Enterprise procurement committees as primary buyer
🚫 Trade shows required for credibility ($10-30K)
🚫 Licensed professional required full-time for MVP
🚫 Network effects required to be useful
🚫 Big-tech alumni with $5M+ raised already dominating
🚫 Consumer app needing 10M+ users at $5/year
🚫 User-generated content moderation at scale
🚫 Education/healthcare delivery/fintech without specific exception

## LinkedIn/Twitter hype anti-patterns

❌ "AI agency" — actually consulting, not a product
❌ "AI faceless YouTube" — saturated, low CPM
❌ "AI Twitter ghostwriter" — saturated, no moat
❌ "Sell courses on AI" — feeds the hype cycle
❌ "AI cold email outreach" — deliverability collapsing
❌ "AI SDR/sales agent" — $50M+ funded competitors
❌ "AI legal contract review for SMBs" — Harvey/Ironclad/EvenUp own it
❌ "AI medical scribe" — Abridge/Suki/Nuance own it, $10M+ to compete
❌ "AI financial advisor" — RIA registration required
❌ "AI customer support" — Intercom/Zendesk + 50 startups

---

# PART 5: OUTPUT FORMAT

When presenting findings to the user:

## 1. Research summary
One paragraph stating: how many candidates evaluated, how many web searches run, how many failed the demand gate, top remaining.

## 2. Per-candidate demand evidence

For each candidate, present:

**[Candidate Name]**

**Demand Signal: X/10**
- "[Direct quote from Reddit user]" — r/subreddit, [upvotes] upvotes, [date]
- "[Direct quote from forum]" — [source], [engagement metric]
- "[Direct quote from review]" — [source]
- Google Trends pattern: [rising/stable/declining]
- Active communities: [list with member counts]

**Pain Severity: X/10**
- Cost of problem: $X per incident OR $X annually (source: [citation])
- Time cost: X hours per [unit] (source: [citation])
- Most visceral quote: "[quote]" — [source]
- Urgency triggers: [list]

**Competitive Reality: X/10**

| Competitor | Funding | Est. Revenue | Pricing | Top Complaint |
|---|---|---|---|---|
| [Name] | [$, year] | [$X ARR] | [$X] | [Verified gripe] |

Underserved gap: [specific segment or feature competitors miss]

**Composite Demand Score: X/10**

## 3. Feasibility scoring

12-dimension table for surviving candidates only.

## 4. Head-to-head comparison

Combined scoring matrix.

## 5. Top recommendation

The pick, with:
- Why it beats the others for this specific founder
- 90-day validation plan with concrete actions
- 5 specific customer conversations to have (where to find these people)
- Kill criteria with measurable thresholds

## 6. Risks and uncertainties

What you're betting on. What could go wrong. What you don't know yet.

---

# PART 6: HONESTY DISCIPLINE

Three rules that override everything else:

1. **Cite evidence for every demand and competitive claim**. Never assert demand without quoting users. Never assert competitor pricing without a source URL.

2. **Revenue projections in ranges, not points** — "$150-280K year one" not "$500K year one"

3. **Name the founder's blind spots** — if they lack domain expertise for an industrial play, say so directly

If the user pushes back on a realistic assessment, do not capitulate. Restate the constraint and ask what they want to change about their profile if they want different opportunities.

---

# PART 7: CONVERSATION MEMORY

Track ideas already discussed. Don't re-pitch the same idea unless profile or market changed. Reference prior comparisons.

---

# PART 8: CALIBRATION EXAMPLES

For reference, here's how previously evaluated ideas would score under this framework:

## EdgeSense AI (Industrial predictive maintenance)

**Demand Signal: 8/10**
- r/manufacturing 21+ upvotes on "Pains of Predictive Maintenance" thread
- r/PLC active discussion threads on vibration sensors and PdM
- Fluke/Censuswide survey: 55% of US manufacturers experienced unplanned downtime
- Active community discussions across years

**Pain Severity: 9/10**
- Verified $400K/hr to $1.7M/hr cost per incident (Fluke survey)
- $50B annual cost across US manufacturing (NeoBram research)
- "Catching it days early saves millions" quotes throughout r/engineering

**Competitive Reality: 5/10**
- Augury (well-funded, $100K+ pricing, enterprise focus)
- C3 AI (public co, $500K+, enterprise/gov)
- Samsara (public co, partial coverage)
- Tractian (mid-market growing)
- AVEVA/OSI (enterprise SCADA)
- Gap exists (mid-market edge-first) but multiple players adjacent

**Composite: 7.6 (passes gate)**

But fails feasibility: domain gap 3/10, sales cycle 3/10, capital needed 3/10 → average 4.75/10 → REJECT for this founder profile

## Solar Permit SaaS

**Demand Signal: 7/10**
- r/solar regular complaints about permit rejections
- DIY Solar Forum threads on PE costs and frustrations
- Multiple installer forum threads about outsourcing decisions

**Pain Severity: 8/10**
- $2,000-5,000 per rejected permit (verified via EnergyScape research)
- 1-2 week delay per rejection
- 4-8 hours per packet of permit coordinator time

**Competitive Reality: 4/10**
- GreenLancer ($100-585 range, 7,500+ contractors since 2013, integrations with OpenSolar/IronRidge)
- Scanifly ($7M+ raised, drone-based moat)
- Planet Plan Sets ($249-449, established)
- YourSolarPlans, Solar Permit Solutions, Techverse, EnergyScape — crowded
- High competitive intensity, all serving similar customers

**Composite: 6.4 (passes gate weakly)**

Feasibility: average 6.5/10 → CONSIDER WITH CAVEATS

## Hypothetical: Small Landlord SaaS (for comparison)

**Demand Signal: 9/10**
- r/landlord (200K+ members), r/realestateinvesting (2M+ members) active
- BiggerPockets forum thousands of threads
- 11 million small landlords in US
- Recurring complaints about tenant screening, lease compliance, late payments

**Pain Severity: 7/10**
- Average $3,500 cost per eviction (verified industry data)
- 20-30 hours/month on property management for 5 properties
- Real money but not crisis-level

**Competitive Reality: 7/10**
- TenantCloud ($15-50/mo), Hemlane ($30/mo), Avail (free + transaction fees), Stessa (free + paid tier)
- Fragmented, no dominant player <10 properties
- AI-native angle unclaimed

**Composite: 7.8 (strong gate pass)**

Feasibility: average 7.8/10 → STRONG FIT

---

# FINAL PRINCIPLE

Your job is not to make the user excited. Your job is to find them an opportunity with verified demand, manageable competition, and execution feasibility within their constraints. An unsexy idea with proven pain that ships is worth 100 sexy ideas with assumed demand that don't.

Every recommendation must answer: "Show me the receipts."

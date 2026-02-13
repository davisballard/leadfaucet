# Team Meeting: Lead Faucet Strategy & Website Review

**Date:** February 12, 2026 (Evening)  
**Attendees:** Danny, Sasha, Davis  
**Duration:** ~1 hour 45 minutes  
**Recording:** Saved with captions

---

## Executive Summary

Danny presented a comprehensive rebuild of the Lead Faucet website and suite of tools designed to position the company as a premium lead generation partner for law firms. The team discussed outreach strategy, purchased a 6,000-firm PI attorney list, set up Instantly.ai for email campaigns, and established compensation structure (20% net profit to whoever signs the client, in perpetuity).

---

## Key Accomplishments Presented

### 1. **Website Overhaul (Lead Faucet)**
- Complete redesign with premium positioning
- Vertical-specific pages: Personal Injury, Immigration, Mass Tort
- Custom ROI calculators for each vertical (different metrics per practice area)
- "One firm per metro" exclusivity positioning throughout
- Interactive quiz to establish thought leadership
- Dynamic intake forms that adapt based on entry point
- Service philosophy: **"We don't just generate demand, we build the tools that capture it"**

### 2. **Case Snapshot Tool (Product #1)**
- Immigration attorney friend gave feedback: "If you could build something specific for that niche, that would be killer"
- Zena conducted user research with someone who'd been in a bike accident (Benedict/Benny)
- Tool will be exclusive to partner firms in each metro

### 3. **Dynamic Landing Page Generator (Metro-Specific)**

**How it works:**
- Input: City name + legal vertical (e.g., "Las Vegas, Personal Injury")
- Uses API (Fire Scraper) to pull real-time data: population, accident statistics, Spanish speakers, etc.
- Generates custom landing page with:
  - Local market intelligence
  - "Where [City] firms lose cases"
  - Demand infrastructure specific to that metro
  - Projections and CTA specific to that region

**Use case:** Metro-specific Meta campaigns can send to hyper-relevant landing pages

**Examples generated:** San Diego PI, Los Angeles Immigration, Miami PI, Nevada PI

### 4. **Dynamic Firm-Specific Landing Pages**

**How it works:**
- Input: Competitor law firm website URL (e.g., sweetjames.com, sugarman.com)
- Scrapes firm website to analyze:
  - Their positioning and practice areas
  - Website gaps and weaknesses
  - Managing partners and locations
- Generates personalized pitch page:
  - "We know who you are" (acknowledges their strengths)
  - "Here's where your cases are leaking" (gaps analysis)
  - Custom economics and ROI calculator
  - CTA to start conversation

**Use case:** Sales tool for warm leads; pages saved as permalinks on Lead Faucet server

**Examples generated:** Sweet James (LA), Sugarman (Boston)

### 5. **Outreach Email Generator**
- Integrated with firm scraper
- Generates 3 versions per prospect:
  1. **Short version:** 1-liner to pique curiosity
  2. **Mid-length:** Moderate detail
  3. **Comprehensive:** Full pitch
- Uses firm-specific intel (practice areas, managing partners, gaps spotted)
- Pulls from Lead Faucet value props for consistency

### 6. **Internal Tools Page** (Not in navigation)
- **Agency Health Dashboard:** Revenue targets, partner acquisition, active partnerships, MRR, markets locked
- **Metro Landing Page Generator:** (described above)
- **Firm-Specific Page Generator:** (described above)
- **Outreach Generator:** (described above)
- **Future: Partner Portal** - Clients will log in to see real-time delivery (e.g., "42 of 50 leads delivered in California")

---

## Outreach Strategy & Tools

### Instantly.ai Setup
- **Danny signed up:** $47/month plan (Growth CRM)
- **Capabilities:**
  - Email warming
  - Dynamic personalization fields
  - A/B testing on subject lines
  - Conditional follow-up flows (nurture sequences)
  - CRM for tracking responses
- **Team approach:** All three will send emails (20-30/day each while warming up)
- **Issue encountered:** Built-in lead finder pulled wrong verticals (found "managing partners" across all industries, not just law)
- **Solution:** Will import the purchased list directly

### Lead List Purchase
- **Source:** EXA (private group member selling)
- **Cost:** $450
- **Size:** 6,000 firms
- **Quality:** Personal injury-specific (not just general law firms)
- **Key feature:** Includes email addresses + managing partner names (rare for scraped lists)
- **Urgency:** Seller only offering to 2 other people in group
- **Decision:** Danny buying tomorrow morning via Stripe link

### Outreach Approach (To be refined)
- **Top 50 firms:** Highly personalized approach (custom reports, dynamic pages, multiple touchpoints)
- **Remaining firms:** Shorter emails, follow-up sequences
- **Philosophy:** Multiple touches required (email + calls) per Jamie's advice
- **Resource:** KOD (Jacobe's group) has entire section on email outreach with templates, prompts, and examples
  - Includes AI prompts for writing emails
  - Decision-maker targeting guide
  - Personas: "Tony Reyes the Hungry Solo," "Jennifer Walsh the Established Builder," "The Tired King," "Marcus Chen the Marketing Director"
  - Sweet spot: $3-10M annual revenue firms (can dictate terms)
  - Sales cycle: 1-2 weeks for smaller firms, 4-8 weeks for $100M+ firms

---

## Business Model & Positioning

### "One Firm Per Metro"
- Exclusive territory model
- Fear of loss positioning: "Use us before someone else in your market does"
- When someone applies via intake form, system checks if their metro is taken
- If taken, they're informed it's unavailable
- Creates urgency and premium positioning

### Verticals & Differentiation

**Three initial verticals:**
1. **Personal Injury** - Primary focus, largest opportunity
2. **Immigration** - Secondary (meeting with Asham tomorrow to show immigration-specific version)
3. **Mass Tort** - Third vertical

**Key differentiator:** "We don't just generate demand, we build the tools that capture it"

**Positioning vs. typical vendors:**
- Most vendors: Sell leads, no control, mixed quality
- Lead Faucet: Proprietary tools, exclusive territories, full infrastructure

### Products Roadmap

**Current:**
- Case Snapshot (PI)

**Future:**
- Immigration Intake Tool
- [TBD third product]

**Product page:** Showcases all tools as part of the value prop, not just lead delivery

---

## Compensation & Incentive Structure

### Sales Commission
- **20% of net profit** to whoever signs the client
- **In perpetuity** (as long as client is active)
- **Separate from** any Lead Faucet equity arrangement
- **Standard in industry** (per Danny's experience)
- **Example math:** $20K buy → 50% net margin = $10K net → $2K to salesperson per month ongoing

### Revenue Model
- **Clients prepay** for lead batches (e.g., 50 leads)
- **Fulfillment obligation:** Must deliver agreed-upon leads or risk refund
- **Backup plan:** Can buy leads from Max/Kieran at margin if needed (buy at $150-250, sell at $350)
- **Goal:** Generate own leads via ads to keep full margin

### Financial Projections
- Davis created spreadsheet modeling:
  - Jacobe + Myers as initial clients
  - 1, 2, or 3 leads per day per state
  - Different bought lead percentages (100%, 75%, 50%, 25%)
  - Various split scenarios (30/30/10 for overhead, etc.)
- **Key insight:** Significant revenue ramp as own leads replace bought leads

---

## Immediate Action Items

### 🔴 Davis — HIGH PRIORITY

#### LinkedIn & Professional Presence (URGENT)
- [ ] **LinkedIn profile updates** for all three (bios, titles, headers aligned to Lead Faucet positioning)
- [ ] **Email signatures** - Animated, premium (Davis has tool from City of Angles work)
- [ ] Send SVG vectors needed to Danny

**Why urgent:** People will check LinkedIn when receiving outreach emails

#### Email Outreach Optimization
- [ ] **Review Instantly.ai emails** and optimize with strategist agents
- [ ] **Review all website prompts** (landing pages, email generator, etc.) to suggest improvements
- [ ] **Create email specialist agent** in Cursor (dedicated to outreach copy)
- [ ] **Build salesperson agent** in Cursor ("Glengarry Glen Ross" themed)

**Resources needed from Danny:**
- Access to Instantly.ai login to review flows
- All prompts used in landing page/email generators
- Current email templates being used

#### Strategic Support
- [ ] **Research top markets** to inform metro-specific campaigns with local insights
- [ ] **Consider:** Custom imagery per city (e.g., Boston skyline, Brooklyn Bridge) for landing pages
- [ ] **Optional:** Run website copy through copywriting agent for suggestions (Danny feels current copy is strong, but worth a pass)

### 🔴 Danny — HIGH PRIORITY

#### List Purchase & Setup (TODAY/TOMORROW)
- [ ] **Buy the 6,000-firm list** ($450 via Stripe link) - TOMORROW MORNING
- [ ] **Import list into Instantly.ai** (bypassing the built-in lead finder that pulled wrong verticals)
- [ ] **Create email templates** in Instantly for first outreach wave
- [ ] **Share Instantly.ai login** with Davis so he can review flows

#### Meetings & Presentations
- [ ] **Meeting with Asham tomorrow** to show immigration-specific version of website/calculator
- [ ] **Meeting with Jacobe tomorrow** - 4:30pm Pacific / 5:30pm Mountain
- [ ] **Meeting with Jamie** (appointmentsetter.com) at 3:30pm tomorrow

#### Documentation & Sharing
- [ ] **Share SVG vectors** of Lead Faucet logo with Davis
- [ ] **Share all prompts** used in landing page/email generators with Davis for optimization
- [ ] **Document brand ecosystem** (parent agency, subbrands, when to use which brand name)
  - E.g., consumer-facing MVA products shouldn't be "Lead Faucet" branded
- [ ] **Build partner portal login** (future priority, not urgent)

### 🔴 Sasha — HIGH PRIORITY

#### Research & Learning
- [ ] **Review KOD resources** - specifically "Getting Lead Buyers" section with email outreach video and templates
- [ ] **Explore Zoom Info trial** - Has "intent" filtering that might identify firms actively looking for leads
- [ ] **Provide any additional personal branding assets** to Davis for LinkedIn refresh

#### Outreach Preparation
- [ ] **Begin daily outreach** once list is imported and team strategy is set
- [ ] **Prepare for top 50 firm targeting** with highly personalized approach

### 🔴 All Three — TEAM PRIORITIES

#### Meetings
- [ ] **Meeting with Jacobe tomorrow** - 4:30pm Pacific / 5:30pm Mountain / 9:30pm Sasha's time
- [ ] Tommy might join

#### Outreach Execution
- [ ] **Divide top 50 firms** from list for highly personalized outreach
- [ ] **Each send 20-30 emails/day** once Instantly is configured and emails are warmed
- [ ] **Call follow-ups** in addition to email (per Jamie's advice: "You have to email multiple times and call")
- [ ] **A/B test approaches** - Strategy for short vs. long emails, whether to send dynamic pages upfront or after reply
- [ ] **Monitor responses** and iterate based on what's working

---

## Tools & Resources Discussed

### New Tools Adopted
1. **Instantly.ai** - Email outreach platform ($47/month)
2. **Fire Scraper** - API for real-time data (population, accidents, etc.) for landing pages
3. **EXA** - Lead list source (6K PI firms for $450)

### Resources Referenced
1. **KOD (Jacobe's group)** - "Getting Lead Buyers" section with outreach templates and prompts
2. **Zoom Info** - Potential trial for intent-based lead filtering
3. **Full Enrich, Cognism** - Alternatives to Zoom Info for phone/email enrichment
4. **Sales Navigator** (LinkedIn) - For prospecting
5. **Command+Shift+A** (Mac) - Tab search function (Danny just learned this!)

### Design/Dev Stack
- **Lovable** - Initial design system and prototyping
- **Framer** - Final website hosting
- **Cursor/Claude** - Heavy AI-assisted development
- **Gemini** - Image generation (Danny used for headshot improvement)

---

## Strategic Insights & Decisions

### Brand Strategy Discussion
- **Consideration:** Should they rebrand to "Claim Justice" or keep "Lead Faucet"?
- **Decision (tentative):** Lead Faucet works well with the current premium website; might create sub-brands for consumer-facing products
  - E.g., MVA-related customer tools might be "Case Snapshot" or similar, not Lead Faucet-branded
  - Immigration tools might have dedicated branding
- **Danny to document:** Full brand ecosystem and when to use which brand

### Messaging & Positioning Refinements
- **Davis suggests:** Small integration of empathy for how lawyers are viewed (seen as "ambulance chasers," clients feel greedy using PI attorneys)
- **Danny's approach:** Framing already addresses this via:
  - "One system, deep verticals" (we understand your specific challenges)
  - Vertical-specific pain points (e.g., "Where Miami PI firms lose cases")
  - Premium positioning counters "scummy" perception
- **Thought leadership:** Quiz on website ("Think you know PI marketing?") establishes authority without being preachy

### Competitive Intelligence
- **Morgan & Morgan:** Spends $391M/year in California alone (5x more than any other legal advertiser)
- **Insight:** Even huge players are spending massively, indicating market size and willingness to invest in leads

### Personas to Target (from KOD)
1. **Tony Reyes, The Hungry Solo** - Solo practitioner, scrappy, needs volume
2. **Jennifer Walsh, The Established Builder** - Mid-size firm, growth mode
3. **The Tired King** - Founding partner, wants "one more big case" before retirement/golf
4. **Marcus Chen, Marketing Director** - $100M+ firms, longer sales cycle (4-8 weeks)

**Sweet spot:** $3-10M annual revenue firms (shorter sales cycle, can dictate terms)

---

## Meeting Vibe & Dynamics

- **Danny:** In the zone, rapid-fire demos, clearly been grinding for 2 days straight building tools
- **Davis:** Enthusiastic, wants to contribute more, slightly feeling behind Danny's pace, focused on supporting with strategy/copy/branding
- **Sasha:** Tired (midnight+ for him), fell asleep earlier for an hour, but engaged and asking good questions
- **Energy:** High excitement about the tools, the upcoming list, and the potential
- **Running joke:** Sasha's camera issues at the start, Ben Salem being a "real city," Sasha's new headshot, Danny needing to exercise ("getting doughy")
- **Cultural references:** Glengarry Glen Ross ("the Glengarry leads"), Olympics snowboarding, Sweet James billboards

---

## Key Quotes

**Danny:** "No one's going to be able to fuck with us."

**Danny on compensation:** "You will keep 20% of the net profit from any client you sign in perpetuity."

**Davis:** "This is what I was telling you. The amount of effort... it's usually what I do where I'm like 'I'm just going to make a landing page' and then it's 3am and I made a whole tool."

**Sasha:** "I'm competitive, so I want to outdo everyone else."

**Danny on outreach:** "We're not going to do one and done. We're going to pick our favorites and email multiple times, call..."

**Website positioning:** "We don't just generate demand, we build the tools that capture it."

---

## Risks & Mitigations Discussed

**Risk:** Contractually obligated to deliver leads, could end up "upside down" (paying more for leads than client paid)  
**Mitigation:** Can buy leads from Max/Kieran at margin as backup; focus on generating own leads via ads

**Risk:** Email deliverability / landing in spam  
**Mitigation:** Warm up emails in Instantly.ai, send 20-30/day per person, avoid word walls

**Risk:** Website looks great but not converting  
**Mitigation:** User research already conducted (Zena's friend Benedict), A/B testing planned, multiple CTAs and calculators for engagement

**Risk:** Limited to 250 members in KOD group (resource might close)  
**Mitigation:** Already members "in perpetuity" per Danny

---

## Next Meeting

**Tomorrow (Feb 13):**
- 4:30pm Pacific / 5:30pm Mountain / 9:30pm Sasha's time
- **With Jacobe** (weekly check-in)
- Tommy might join

**Also tomorrow:**
- Danny meeting with Asham (immigration attorney) to show website
- Danny meeting with Jamie (appointmentsetter.com) at 3:30pm

---

## Long-term Vision Mentioned

- **Partner portal:** Real-time dashboards for clients showing lead delivery progress
- **Product expansion:** More vertical-specific intake tools beyond PI and immigration
- **Agency health dashboard:** Internal transparency on revenue, partners, locked markets
- **Scale strategy:** Once revenue is flowing, reinvest in ad spend to generate own leads at scale, creating surplus to sell to non-partner firms in uncovered metros
- **Territory expansion:** One firm per metro creates natural expansion opportunity across all U.S. markets
- **Thought leadership:** Continue building tools and content that position Lead Faucet as sophisticated tech partner, not just lead vendor

---

## Technology Highlights

### Danny's 2-Day Build Sprint

**What he built:**
1. Full website redesign with vertical-specific pages
2. 3 different ROI calculators (PI, Immigration, Mass Tort)
3. Dynamic metro-specific landing page generator
4. Dynamic firm-specific pitch page generator
5. Outreach email generator (3 variants per prospect)
6. Interactive thought leadership quiz
7. Internal tools dashboard
8. Future partner portal foundation

**Tools used:**
- Lovable for design system
- Framer for hosting
- Fire Scraper API for data
- Heavy Claude/Cursor usage
- Self-QA method: Ask AI to grade work A-F, identify gaps, iterate

**Davis reaction:** "This is usually what I do where I'm like 'I'm just gonna make a landing page' and then it's 3am and I made a whole tool."

---

**Recording saved with captions for team reference.**

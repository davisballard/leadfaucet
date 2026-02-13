# Partner Firms

> **Purpose:** Reference for dynamic consent forms. FCC 2025 requires specific named entities before consent.
> 
> **Last Updated:** January 30, 2026

---

## ⚠️ CRITICAL: FIRM NAME USAGE RULES

**Partner firm names can ONLY appear in these 3 places:**

| Location | Example | Allowed |
|----------|---------|---------|
| **1. Form fine print / disclosure** | "Claim Justice Now is a marketing partner of [Firm Name]..." | ✅ Yes |
| **2. Consent checkbox** | "I consent to receive calls/texts from [Firm Name]" | ✅ Yes |
| **3. Thank You page header** | "[Firm Name] will review your case" | ✅ Yes |
| Ads (headlines, body, images) | — | ❌ NO |
| Landing page hero/body | — | ❌ NO |
| Trust badges (pre-form) | — | ❌ NO |

### What CAN be used in ads/landing pages:
- ✅ Stats: "$2.2B+ Recovered", "95% Success Rate", "45+ Years"
- ✅ Testimonials: Quotes with first name only
- ✅ Settlement amounts: "$450,000 settlement"
- ✅ Generic claims: "Top-rated law firm", "#1 in California"

### What CANNOT be used in ads/landing pages:
- ❌ Firm name: "Larry H. Parker", "Jacoby & Meyers"
- ❌ Attorney names in headlines

**Why:** The consumer-facing brand is **"Claim Justice Now"** — the attorney name only appears at consent/disclosure points for FCC compliance.

---

## Active Partners

### Larry H. Parker
| Attribute | Value |
|-----------|-------|
| **Legal Name** | The Law Offices of Larry H. Parker |
| **Display Name for Forms** | Larry H. Parker |
| **States Licensed** | California |
| **Case Types** | MVA (Motor Vehicle Accidents), Personal Injury |
| **Status** | ✅ Active |
| **Consent Checkbox Text** | "I consent to receive calls/texts from Larry H. Parker" |

**Verified Stats (for ads/landing pages):**
| Stat | Value | Source |
|------|-------|--------|
| Total Recovered | $2.2 Billion+ | injury.larryhparker.com |
| Success Rate | 95% | injury.larryhparker.com |
| Years Experience | 45+ | injury.larryhparker.com |
| Clients Served | 100,000+ | larryhparker.com |
| Google Reviews | 847 | Birdeye |
| Birdeye Rating | 4.3 Stars | Birdeye (1,095 reviews) |
| BBB Rating | A+ | BBB.org |
| Availability | 24/7 | larryhparker.com |
| Fee Model | No Fee Unless We Win | injury.larryhparker.com |

**Required Footer Disclosure:**
> Claim Justice Now is not a law firm. We are marketing partners with Larry H. Parker.

**Reference Files:**
- Full research: `07_Research/Partner_Firms/Larry_H_Parker_Reference.md`
- CA ads stats: `07_Research/Partner_Firms/CA_Ads_Stats_Reference.md`

---

### Jacoby & Meyers
| Attribute | Value |
|-----------|-------|
| **Legal Name** | Jacoby & Meyers Law Offices |
| **Display Name for Forms** | Jacoby & Meyers |
| **States Licensed** | California, Colorado, Nevada, Washington |
| **Case Types** | MVA (Motor Vehicle Accidents) |
| **Status** | ✅ Active |
| **Consent Checkbox Text** | "I consent to receive calls/texts from Jacoby & Meyers" |

**Verified Stats (for ads/landing pages):**
| Stat | Value | Source |
|------|-------|--------|
| Total Recovered | $2 Billion+ | jacobyandmeyers.com |
| Years Experience | 50+ (Est. 1972) | jacobymeyers.com |
| Google Rating | 4.6 Stars | Google Reviews |
| Google Reviews | 2,200+ | Google via Birdeye |

**Required Footer Disclosure:**
> Claim Justice Now is not a law firm. We are marketing partners with Jacoby & Meyers. [Jacoby & Meyers California headquarters address].

**Reference Files:**
- Full research: `07_Research/Partner_Firms/Jacoby_Meyers_Reference.md`

**Compliance Notes:**
- Lawyers are very sensitive to compliance
- Must include CYA footer language on all funnels
- California has SB37 legislation affecting tone of voice

---

### Think Law
| Attribute | Value |
|-----------|-------|
| **Legal Name** | Think Law [verify full legal name] |
| **Display Name for Forms** | Think Law |
| **States Licensed** | North Carolina, South Carolina, Georgia, Mississippi |
| **Case Types** | MVA, Personal Injury |
| **Status** | ⏸️ Paused |
| **Consent Checkbox Text** | "I consent to receive calls/texts from Think Law" |

**Notes:**
- Campaigns currently paused
- Resume after Jacoby & Meyers pipeline is flowing

---

## Consumer-Facing Brand: Claim Justice Now

| Attribute | Value |
|-----------|-------|
| **Brand Name** | Claim Justice Now |
| **Purpose** | Consumer-facing lead capture brand |
| **URL Structure** | claimjusticenow.com/[state] (subdomains per state) |
| **Relationship** | Marketing partner to law firms; NOT a law firm |

**Claim Justice Now is the actual brand identity for lead capture**, while campaigns run under partner firm names for consent purposes.

### State Subdomains
- claimjusticenow.com/california
- claimjusticenow.com/colorado
- claimjusticenow.com/nevada
- claimjusticenow.com/washington

---

## Adding New Partners

When onboarding a new partner firm, collect:
1. Full legal entity name
2. Preferred display name for forms
3. States where they're licensed to practice
4. Case types they accept
5. Approved consent language
6. Required footer/disclosure language
7. Compliance sensitivity level

---

## Dynamic Consent Flow

Per FCC 2025 requirements:
1. User enters zip code + injury type
2. System pings partner network in real-time
3. Form displays actual firm names bidding on this lead
4. User sees unchecked checkbox for each firm
5. User selects which firms may contact them
6. Submission = consent only to selected entities

**Each checkbox must show the specific firm name BEFORE user consents.**

---

## Required Technical Integration

- **TrustedForm** — Video replay of consent moment (MANDATORY)
- **Jornaya LeadiD** — Audit trail + bot detection (MANDATORY)
- **Twilio** — SMS verification for lead capture
- Retain certificates for 5+ years

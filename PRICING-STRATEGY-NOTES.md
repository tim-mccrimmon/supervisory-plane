# SCP Pricing Strategy — Working Notes

**Status:** Draft / Thinking Out Loud
**Date:** January 28, 2026
**Purpose:** Capture pricing considerations for future refinement

---

## Current Pilot Pricing

- **5 agents, 90 days: $15,000 + reference**
- Simple, defensible, gets us in the door
- Reference requirement adds non-monetary value

---

## Production Pricing — Open Questions

### The Core Tension

**High-risk agents** (regulated decisions, PHI, financial impact):
- Fewer agents per enterprise (10-100)
- High value per agent — compliance failure is expensive
- $12K/agent/year might be right

**All agents** (general governance, assistants, automations):
- Many agents per enterprise (500-5,000)
- Lower value per agent individually
- $12K/agent/year is a non-starter

**Question:** Is SCP for governing critical agents, or infrastructure for all AI?

---

## Pricing Models Considered

### Model 1: Flat Per-Agent

| Agents | Price/Agent/Year |
|--------|------------------|
| Any | $12,000 |

**Pros:** Simple
**Cons:** Doesn't scale, loses deals with many agents

---

### Model 2: Volume Tiers

| Agents | Price/Agent/Year |
|--------|------------------|
| 1-10 | $12,000 |
| 11-50 | $6,000 |
| 51-200 | $3,000 |
| 201+ | $1,500 |

**Example — 100 agents:**
- (10 × $12K) + (40 × $6K) + (50 × $3K) = $510K/year

**Pros:** Rewards scale, reduces sticker shock at volume
**Cons:** More complex to explain

---

### Model 3: Risk-Based Tiers

| Tier | Description | Price/Agent/Year |
|------|-------------|------------------|
| Critical | Regulated decisions, PHI/PII, financial impact | $12,000 |
| Standard | Business operations, internal workflows | $3,000 |
| Basic | Dev tools, assistants, low-risk automation | $1,000 |

**Pros:** Captures full value on high-risk, doesn't lose deal on low-risk
**Cons:** Requires classification process, potential for gaming

---

### Model 4: Platform + Per-Agent

| Component | Price |
|-----------|-------|
| Platform base | $100,000/year |
| Per agent | $2,000/year |

**Example — 100 agents:** $100K + $200K = $300K/year

**Pros:** Predictable base revenue, low marginal cost encourages adoption
**Cons:** Base fee might scare smaller buyers

---

### Model 5: Tiered Packages

| Package | Agents | Price/Year |
|---------|--------|------------|
| Starter | Up to 10 | $80,000 |
| Growth | Up to 50 | $250,000 |
| Enterprise | Unlimited | $500,000 |

**Pros:** Simple to understand, encourages upgrades
**Cons:** Might leave money on table for very large deployments

---

### Model 6: Usage-Based

- Per context request
- Per decision audited
- Per bundle update

**Pros:** Aligns cost directly with value delivered
**Cons:** Hard to predict revenue, hard for customer to budget

---

## Competitive Considerations

- Large enterprises might build this themselves (build vs. buy)
- Need to price below the cost of a team building it internally
- But also need to signal "this is serious enterprise software"

---

## What We Need to Learn

1. **How many high-risk agents do enterprises actually have?**
   - If IBM has 50, $12K/agent = $600K — might work
   - If IBM has 5,000, $12K/agent = $60M — absurd

2. **What's the internal build cost?**
   - 2 engineers for 6 months = ~$300K loaded cost
   - If we're priced below that, we win on speed and TCO

3. **What do compliance buyers expect to pay?**
   - Vanta, Drata, etc. charge $10K-$100K/year
   - AI governance is newer — no established anchor

4. **Do buyers think in "per agent" terms?**
   - Or do they think in platform/deployment terms?

---

## Forrester SVP Questions (Next Week)

- What are enterprises actually paying for AI governance today?
- Is "per agent" the right unit, or something else?
- What price point makes this an easy yes vs. requires committee approval?
- Who's the buyer — CISO, CIO, VP Engineering, Compliance?

---

## Decision Log

| Date | Decision | Rationale |
|------|----------|-----------|
| 2026-01-28 | Pilot: $15K for 5 agents, 90 days + reference | Simple, gets us in the door, learn from real deals |
| TBD | Production pricing | Waiting for pilot learnings and Forrester input |

---

## Next Steps

1. Run pilots at $15K
2. Ask Forrester SVP about pricing expectations
3. After 2-3 pilots, revisit production pricing with real data
4. Consider risk-tier or volume-tier model based on what we learn

---

*Last updated: January 28, 2026*

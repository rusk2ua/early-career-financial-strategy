# Decisions Log

## Purpose
This log documents all significant decisions made during the project, including rationale, alternatives considered, and outcomes. Each entry should help future contributors understand why certain choices were made.

---

## Project Inception (November 2025)

### Decision: Target $80K Income Profile
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Needed to create a realistic, relatable scenario for early-career professionals.

**Decision:**
Use $80K annual income as the baseline profile for all calculations and recommendations.

**Rationale:**
- Median income for early-career professionals with bachelor's degree
- High enough to save meaningfully (30%+)
- Low enough to be relatable and aspirational
- Matches common tech/business entry-level salary range

**Alternatives Considered:**
- $60K (rejected: limits savings capacity too much)
- $100K (rejected: less relatable for most readers)
- Range of incomes (rejected: creates confusion, prefer one clear example)

**Impact:**
All calculators, examples, and recommendations are calibrated to this income level.

---

### Decision: Focus on Ages 55-60 Retirement
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Traditional retirement guides focus on age 65+, but early retirement requires different strategies.

**Decision:**
Target retirement window of ages 55-60, with primary focus on age 55.

**Rationale:**
- 55 is the earliest for "Rule of 55" 401(k) access
- 30-year accumulation period is realistic and achievable
- Bridges the gap to Medicare (age 65)
- Early enough to be motivating, late enough to be achievable

**Alternatives Considered:**
- Age 50 FIRE (rejected: requires extreme savings rate, less realistic)
- Age 40 FIRE (rejected: unrealistic for $80K income)
- Traditional 65 (rejected: not early retirement)

**Impact:**
- All timelines assume 30-year accumulation phase
- Healthcare bridge planning required for 55-65 gap
- Roth IRA becomes critical for penalty-free access

---

### Decision: Use 8% Default Return Rate
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Need consistent return rate for projections that's realistic but not overly optimistic.

**Decision:**
Use 8% as default annual return rate for all projections and calculators.

**Rationale:**
- Conservative vs historical S&P 500 (~10%)
- Accounts for fees and volatility
- Higher than bond-heavy portfolios (5-6%)
- Matches Vanguard's long-term projection for balanced portfolios

**Alternatives Considered:**
- 10% (rejected: too optimistic, sets unrealistic expectations)
- 7% (rejected: perhaps too conservative for 90% stock allocation)
- 6% (rejected: better for retirement phase, not accumulation)

**Impact:**
- Wealth timeline shows $2.655M at age 55
- Used in all compound interest calculations
- Sensitivity analysis shows 7% and 10% scenarios

---

### Decision: Recommend 90% Stock / 10% Bond Allocation
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Young investor with 30-year timeline needs growth-focused portfolio.

**Decision:**
Recommend 90% stocks / 10% bonds for ages 25-35.

**Rationale:**
- Maximizes long-term growth potential
- 30+ year timeline can weather volatility
- 10% bonds provide some stability during crashes
- Matches Vanguard target-date funds for same age group

**Alternatives Considered:**
- 100% stocks (rejected: too volatile for most investors psychologically)
- 80/20 (rejected: too conservative for 30-year horizon)
- Age-based formula only (rejected: prefer clear recommendation)

**Impact:**
- Expected returns assume 90/10 allocation
- Rebalancing strategy needed as user ages
- Provides emotional cushion during market downturns

---

### Decision: Prioritize Roth IRA Over Additional 401(k)
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
After getting company match, should user focus on 401(k) or Roth IRA?

**Decision:**
Max Roth IRA ($7K) before contributing beyond 15% to 401(k).

**Rationale:**
- Roth provides penalty-free access to contributions before 59½
- Critical for early retirement bridge strategy
- Tax diversification in retirement
- Flexibility for emergencies

**Alternatives Considered:**
- Max 401(k) first (rejected: locks up money until 59½)
- Split contribution (rejected: prefer clear priority)
- Taxable account first (rejected: lose tax advantages)

**Impact:**
- Recommend: 6% 401(k) → Max Roth → Additional 401(k)
- Early retirement bridge becomes viable
- Tax-free growth on $7K/year for life

---

### Decision: Target 30% Savings Rate
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Need to balance aggressive savings with realistic lifestyle maintenance.

**Decision:**
Recommend 30% gross income savings rate ($24K/year on $80K income).

**Rationale:**
- Gets to $250K in ~8.5 years
- Achieves age 55 retirement with $2.6M
- More aggressive than 15% standard advice
- Still allows reasonable quality of life

**Alternatives Considered:**
- 50% (FI standard) (rejected: too difficult for most)
- 20% (rejected: extends timeline too much)
- 15% (rejected: standard advice, not early retirement)

**Impact:**
- Monthly budget shows tight but doable spending
- Requires lifestyle discipline
- May need to ramp up from lower rate initially

---

### Decision: Focus on Index Funds Only
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Many investment options available - active funds, individual stocks, etc.

**Decision:**
Recommend only low-cost total market index funds (VTI, VXUS, BND equivalents).

**Rationale:**
- Lower fees (0.03-0.10% vs 1%+)
- Historically outperform active management
- Reduces complexity and decision paralysis
- Automatic diversification
- Backed by extensive research (Bogleheads philosophy)

**Alternatives Considered:**
- Individual stocks (rejected: requires expertise, higher risk)
- Target-date funds (rejected: higher fees, less control)
- Active management (rejected: higher fees, typically underperform)
- Robo-advisors (rejected: additional fee layer)

**Impact:**
- Simple 3-fund portfolio
- Minimal maintenance required
- Expected to match market returns minus tiny fees

---

### Decision: Include "Rule of 55" in Early Retirement Strategy
**Date:** November 2025  
**Status:** Active  
**Decision Maker:** Project Creator

**Context:**
Need penalty-free access to retirement funds before age 59½.

**Decision:**
Incorporate "Rule of 55" as primary 401(k) access strategy for early retirement.

**Rationale:**
- Allows penalty-free 401(k) withdrawal if retire at 55+
- No Roth ladder waiting period needed
- Simpler than SEPP/72(t) calculations
- Aligns perfectly with 55-60 retirement target

**Alternatives Considered:**
- Roth ladder only (rejected: 5-year waiting period)
- SEPP/72(t) (rejected: complex, inflexible)
- Wait until 59½ (rejected: delays retirement)

**Impact:**
- Can access 401(k) immediately at 55
- Should not roll 401(k) to IRA before retirement
- Simplifies early retirement planning

---

### Decision: Create Memory Bank System
**Date:** November 27, 2025  
**Status:** Active  
**Decision Maker:** Project Maintainer

**Context:**
Complex project with many interconnected assumptions and decisions needs systematic knowledge tracking.

**Decision:**
Implement comprehensive memory bank system with 5 core documents.

**Rationale:**
- Maintains consistency across all documents
- Documents decision rationale for future reference
- Enables easier updates when tax laws change
- Provides clear project context for contributors

**Alternatives Considered:**
- README-only approach (rejected: too limited)
- Wiki system (rejected: overkill for current scope)
- Issue tracker (rejected: not suited for knowledge base)

**Impact:**
- All major decisions documented with rationale
- Financial assumptions centralized and version-controlled
- Easier to maintain consistency across guides

---

## Template for New Decisions

### Decision: [Brief Title]
**Date:** [Date]  
**Status:** [Active/Superseded/Under Review]  
**Decision Maker:** [Role/Name]

**Context:**
[What situation required a decision?]

**Decision:**
[What was decided?]

**Rationale:**
[Why was this the best choice?]

**Alternatives Considered:**
- Option 1 (rejected: reason)
- Option 2 (rejected: reason)

**Impact:**
[What are the consequences/implications of this decision?]

---

**Last Updated:** November 27, 2025

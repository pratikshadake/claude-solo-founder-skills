# Example: Build vs Buy Decision

## Scenario

A SaaS startup is deciding whether to:

- **Build in-house authentication**
- **Use a third-party provider like Clerk, Auth0, or Supabase Auth**

### Context

- Team size: 3 engineers  
- Timeline pressure: launch in **4 weeks**  
- Budget: moderate, but not enterprise  
- Strategic focus: core product is **AI workflow automation**, not authentication  

---

# Decision Output (from the skill)

## Decision
**BUY**

---

## Rationale

Authentication is a **commodity capability** that does not provide strategic differentiation for the product.  
Given the **4-week launch constraint** and **small engineering team**, building in-house would significantly delay time to value and introduce ongoing **security, compliance, and maintenance burden**.

A third-party provider enables:

- Immediate production readiness  
- Proven security and compliance  
- Faster focus on core AI workflow features  

Therefore, purchasing is the **fastest and lowest-risk path**.

---

## Scorecard

### Time to value
- Build: ~3–6 weeks minimum for secure MVP  
- Buy: 1–2 days integration  
**→ Strong advantage: BUY**

### Total cost of ownership (24 months)
- Build: engineering time + security audits + maintenance  
- Buy: predictable SaaS pricing  
**→ Advantage: BUY**

### Strategic differentiation
- Authentication is **not core IP**  
**→ Strong advantage: BUY**

### Control & risk
- Vendor lock-in exists but acceptable  
- Security risk significantly higher if self-built  
**→ Advantage: BUY**

### Opportunity cost
- Building auth delays core AI capabilities  
**→ Strong advantage: BUY**

---

## Risks

- Future vendor pricing increases  
- Migration complexity if switching providers  
- Dependency on third-party uptime  

---

## Revisit Trigger

Re-evaluate this decision **if**:

- Authentication becomes part of core product differentiation  
- Monthly authentication costs exceed **10% of revenue**  
- Enterprise or compliance requirements demand full internal control  

---

# Why this example matters

This example demonstrates:

- Realistic startup context  
- Structured, transparent reasoning  
- Clear scoring logic  
- Founder-level recommendation quality  

It reflects the **expected output standard** of the Build vs Buy Decision Engine skill.


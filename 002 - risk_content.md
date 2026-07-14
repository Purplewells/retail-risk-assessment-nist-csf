# Risk Context

Urban Thread's risk profile is driven by three factors:

1. **Regulatory exposure** (PCI-DSS, UK GDPR)
   - Non-compliance fines: if customer data is mishandled (GDPR) or credit card  
     details, possible fines up to £20M or 4% of revenue under GDPR
   - PCI-DSS breaches: card network penalties, chargeback liability
   
2. **Reputational sensitivity**
   - Youth-focused brand; brand trust is currency on social/TikTok
   - Single incident (data breach, account compromise) can rapidly affect sales/
     social following
   
3. **Resource scarcity**
   - No dedicated IT; owner is stretched across operations, inventory, cash flow
   - Security *must* be framed as business enabler ("we can expand because we're 
     secure"), not overhead

**Risk appetite:** Low-to-moderate. Urban Thread wants to grow and process cards safely, but won't fund a full enterprise security program. Trade-offs are expected.


---

## Assessment Methodology

This assessment uses the **NIST Cybersecurity Framework (CSF)** as the organizing structure, with risk scoring aligned to NIST SP 800-30 (Guide for Conducting Risk Assessments).

**Why NIST CSF for an SMB?**
- Framework-agnostic; maps to ISO 27001, PCI-DSS, and GDPR where relevant
- Five simple functions (Identify, Protect, Detect, Respond, Recover) are easier to communicate to non-technical stakeholders
- Widely recognized; helps with future vendor/partner discussions

**Risk Scoring Formula:**  
Risk Score = Likelihood (1–5) × Impact (1–5)

- **Score ≥12** = High priority (address within 30–90 days)
- **Score 6–11** = Medium priority (address within 90–180 days)
- **Score <6** = Low priority (address in roadmap; reassess annually)


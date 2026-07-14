# Key Assumptions
For this assessment to remain realistic and actionable, the following business constraints and operating assumptions must hold. If your scenario differs, adjust the risk register and roadmap accordingly.

## Financial & Staffing Constraints
### Annual Security Budget
£5,000 - £10,000

- **Rationale**: For a 12-person retail SMB; security is overhead, not a revenue center
- **Allocation**: Prioritises SaaS tools over custom builds; outsourced services over FTE hires
- **Impact on assessment**: Controls must be low-cost or free (MFA, patching, training). Enterprise tools (SIEM, EDR) are out of scope until Year 2 expansion

### Available IT/Security Staffing

**~5 hours per week** (part-time manager wearing many hats)

- **Rationale**: No dedicated IT hire; operations manager handles POS, inventory, and now security
- **Impact on assessment**: Roadmap assumes external support for complex tasks (incident response, DPIA, vendor vetting). Implementation relies on automation and managed services, not manual monitoring
- **Scaling assumption:** Expansion to 3 stores (Year 2) will justify a part-time security hire or outsourced CISO

## Regulatory & Compliance Scope
**Primary Compliance Drivers**

#### PCI-DSS (payment card processing) and UK GDPR (customer data, minors)


- Rationale: Urban Thread processes cards daily and collects data from ~40% under-18 customers
- Not in scope (at this stage): ISO 27001, SOC 2, HIPAA, or other industry-specific standards
- Impact: Roadmap focuses on PCI-DSS + GDPR requirements; other frameworks used for reference only

## UK GDPR Child Data Handling

**Article 8 applies** (verifiable parental consent or age verification for under-16 data)

- Rationale: ~40% of customer base is under 18; heightened liability under GDPR Article 8
- Impact: Customer data breach involving minors elevated to High priority (R1) regardless of raw likelihood
- Practical requirement: DPIA required; consent mechanisms reviewed in Phase 2

## Technical Architecture Assumptions

**Payment Processing**
**Assumed: Third-party SaaS processor (Stripe, Square, Shopify Payments) handling PCI compliance**

- Rationale: Most SMBs do not self-host payment gateways; reduces scope and risk
- Verification required: Real assessment would confirm processor's PCI DSS certification
- Impact: R2 (card data breach) risk is lower than it would be for on-premise processing; focus shifts to misconfiguration and access control

## E-Commerce Platform
**Assumed: Shopify or equivalent SaaS (not custom-built or self-hosted)**

- Rationale: Reduces infrastructure burden; vendor patches core platform
- Risk shift: Exposure moves to third-party app/plugin security and merchant account misconfiguration
- Impact on roadmap: Phase 1 includes plugin audit and patch schedule; Phase 3 adds WAF (managed, not self-hosted)

## Customer Database

**Assumed: Single database hosting customer contact info, purchase history, and (minimal) payment metadata**

- Rationale: Typical for retail SMB; no data warehouse or advanced analytics initially
- Data residency: Assumed UK-hosted (complies with GDPR residency preferences)
- Impact: Encryption at rest (Phase 3) is achievable with SaaS tools; no custom encryption engineering

## Staff Systems

**Assumed:** Cloud-based email (Office 365, Google Workspace), shared password manager, no enterprise directory

- Rationale: Cost-effective for small team; avoids on-premise AD complexity
- Impact on roadmap: MFA (Phase 1) is straightforward; access review (Phase 4) is simpler with fewer systems

## Business Context & Growth

### Current State

- 1 physical store (Birmingham)
- 12 FTE staff (owner/manager + 11 floor/delivery staff)
- Revenue split: 60% e-commerce, 40% in-store
- Customer focus: Fashion-forward teens and young adults; social media (TikTok, Instagram) is primary acquisition channel

### Expansion Plans (Year 2)

- Opening: 2 additional stores (Manchester, London)
- Headcount: Expected to grow to ~25 FTE
- Systems impact: 3× POS terminals, centralized inventory system, likely need for proper IT/ops hire
- Roadmap assumption: Budget and staffing scale accordingly; Phase 4 recommendations assume post-expansion capacity


### Brand Risk Profile

- High sensitivity to social media crises: TikTok/Instagram followings drive word-of-mouth sales
- Reputational damage from data breach: Quick loss of customer trust in a youth-focused brand
- Implication: R3 (social media account takeover) and R1 (child data breach) are weighted heavily for impact despite lower raw likelihood

## Vendor & Third-Party Assumptions

We assumed **Payment Processor** is PCI-DSS compliant; DPA in place; no raw card data stored by Urban Thread

- Verification step in Phase 2: Confirm processor's compliance certification and sub-processor list
- Impact: Reduces card data breach risk to lower than typical; focus is on proper use, not processor vetting


*Hosting Provider & E-Commerce Platform*

Assumed Shopify (or equivalent); vendor responsible for core infrastructure security


- Assessment scope: Configuration, access control, app ecosystem security (not vendor SLA compliance)
- Phasing: Plugin audit (Phase 2), WAF implementation (Phase 3)


## Third-Party Marketing Tools

Assumed: Google Analytics, Facebook Pixel, email marketing platform (e.g., Mailchimp) collecting customer data

- DPA requirement (Phase 2): Confirm all vendors have signed DPAs; review sub-processor disclosures
- Data sharing risk: Low immediate risk if data minimisation is practiced, but requires vendor review

## Risk Appetite & Trade-Offs

### Risk Appetite: Low-to-Moderate

- Urban Thread wants to grow safely and remain compliant
- Owner accepts some residual risk in exchange for cost-efficiency
- Will not invest in enterprise-grade tools (SIEM, EDR, threat intel) at this stage

## Budget vs Coverage Trade-Off

| Priority | Funded            |Not Funded (Accepted Risk) |
| -------- | ----------------- |---------------------------|
| High     | PCI-DSS compliance, GDPR data protection, incident response basics |Real-time threat detection, penetration testing, bug bounty|
|Medium    |Social media MFA, basic security training, vendor questionnaires|Advanced threat monitoring, security awareness platform|
|Low | Annual access review, tabletop exercises | Cyber insurance, redundant systems, DDoS mitigation|
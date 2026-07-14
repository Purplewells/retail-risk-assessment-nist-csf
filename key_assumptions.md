# Key Assumptions
For this assessment to remain realistic and actionable, the following business constraints and operating assumptions must hold. If your scenario differs, adjust the risk register and roadmap accordingly.

## Financial & Staffing Constraints
### Annual Security Budget
£5,000 - £ 10,000

- **Rationale**: For a 12-person retail SMB; security is overhead, not a revenue center
- **Allocation**: Prioritises SaaS tools over custom builds; outsourced services over FTE hires
- **Impact on assessment**: Controls must be low-cost or free (MFA, patching, training). Enterprise tools (SIEM, EDR) are out of scope until Year 2 expansion

### Available IT/Security Staffing

**~5 hours per week** (part-time manager wearing many hats)

- **Rationale**: No dedicated IT hire; operations manager handles POS, inventory, and now security
- **Impact on assessment**: Roadmap assumes external support for complex tasks (incident response, DPIA, vendor vetting). Implementation relies on automation and managed services, not manual monitoring
- **Scaling assumption:** Expansion to 3 stores (Year 2) will justify a part-time security hire or outsourced CISO

## Regulatory & Compliance Scope

### Primary Compliance Drivers

#### PCI-DSS (payment card processing) and UK GDPR (customer data, minors)


- Rationale: Urban Thread processes cards daily and collects data from ~40% under-18 customers
- Not in scope (at this stage): ISO 27001, SOC 2, HIPAA, or other industry-specific standards
- Impact: Roadmap focuses on PCI-DSS + GDPR requirements; other frameworks used for reference only
# Risk Treatment Plan

### Purpose

The purpose of the Risk Treatment Plan is to define how Urban Thread will reduce cyber security risks to an acceptable level in line with its risk appetite, available budget and operational capacity. The plan prioritises actions based on the results of the risk assessment and aligns with the NIST Cybersecurity Framework (CSF) 2.0 functions of Govern, Identify, Protect, Detect, Respond and Recover.

Given the organisation's limited cyber security resources, the treatment strategy focuses on implementing affordable, practical controls that provide the greatest reduction in risk while supporting business growth and regulatory compliance.


## Treatment Strategy

Urban Thread will apply one or more of the following risk treatment options:

| Treatment Option | Description                                                                          | Example                                                                        |
| ---------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| **Mitigate**     | Implement controls to reduce the likelihood or impact of a risk.                     | Enable Multi-Factor Authentication (MFA) and conduct staff awareness training. |
| **Transfer**     | Shift part of the risk to a third party.                                             | Use a PCI-DSS compliant payment processor and obtain cyber insurance.          |
| **Accept**       | Accept the remaining (residual) risk where further mitigation is not cost-effective. | Accept the limited risk of temporary Shopify service outages.                  |
| **Avoid**        | Eliminate the activity creating the risk.                                            | Remove unnecessary Shopify plugins or discontinue unsupported software.        |

Most of Urban Thread's identified risks will be mitigated, while selected operational risks will be transferred or accepted where appropriate.


## Phase 1 – Immediate Actions (0–3 Months)

**Objective:** Reduce the likelihood of the highest-priority risks through rapid implementation of low-cost, high-impact security controls.


| Action                                                                                                                     | Risks Addressed    | Priority | Responsibility                         |
| -------------------------------------------------------------------------------------------------------------------------- | ------------------ | -------- | -------------------------------------- |
| Enforce Multi-Factor Authentication (MFA) for Microsoft 365, Shopify, payment portals and social media accounts            | R1, R2, R3, R5, R6 | High     | Operations Manager                     |
| Review user accounts and remove unnecessary administrator privileges                                                       | R1, R2, R5, R8     | High     | Operations Manager                     |
| Implement a password manager and require strong, unique passwords                                                          | R2, R3, R5         | High     | Operations Manager                     |
| Deliver basic cyber security awareness training covering phishing, password security and incident reporting                | R1, R4, R5, R8     | High     | Operations Manager / External Provider |
| Verify automated backups and perform an initial recovery test                                                              | R4, R11            | High     | Operations Manager                     |
| Apply outstanding software and device patches, including POS systems and employee devices                                  | R4, R6             | High     | Operations Manager                     |
| Document a basic Incident Response Plan with contact lists and escalation procedures                                       | R1, R4, R5         | High     | Business Owner                         |
| Confirm PCI-DSS compliance status of the payment processor and update Data Processing Agreements (DPAs) with key suppliers | R2, R7, R12        | High     | Business Owner                         |


### Expected Outcomes

- Significant reduction in account compromise risk.
* Improved resilience against phishing and ransomware.
* Stronger compliance with UK GDPR and PCI-DSS.
* Improved ability to recover from cyber incidents.

## Phase 2 – Medium-Term Improvements (3–6 Months)

**Objective:** Strengthen governance, improve data protection practices and enhance visibility over cyber security risks.

| Action                                                                                                   | Risks Addressed | Priority | Responsibility                       |
| -------------------------------------------------------------------------------------------------------- | --------------- | -------- | ------------------------------------ |
| Conduct a Data Protection Impact Assessment (DPIA) for customer data processing, particularly for minors | R1, R12         | High     | Business Owner / External Consultant |
| Review customer data retention and deletion practices                                                    | R1, R12         | Medium   | Operations Manager                   |
| Audit Shopify themes, plugins and third-party applications; remove unused or unsupported integrations    | R6, R7          | High     | Operations Manager                   |
| Review supplier security documentation, DPAs and sub-processor lists                                     | R7, R12         | Medium   | Business Owner                       |
| Implement a quarterly access review process for all cloud services                                       | R1, R5, R8      | Medium   | Operations Manager                   |
| Enable enhanced logging and security alerts available within Microsoft 365 and Shopify                   | R5, R6          | Medium   | Operations Manager                   |
| Develop and test a Business Continuity Plan (BCP) and Disaster Recovery (DR) procedures                  | R4, R10, R11    | Medium   | Business Owner                       |
| Introduce a formal asset inventory and software register                                                 | All             | Medium   | Operations Manager                   |


### Expected Outcomes

* Improved compliance with UK GDPR.
* Reduced third-party and supply chain risk.
* Better visibility of user access and system changes.
* Greater confidence in business continuity arrangements.

## Phase 3 – Long-Term Improvements (6–12 Months)

**Objective:** Establish a scalable cyber security capability that supports business expansion to additional retail locations.

| Action                                                                                                                          | Risks Addressed | Priority | Responsibility             |
| ------------------------------------------------------------------------------------------------------------------------------- | --------------- | -------- | -------------------------- |
| Introduce Mobile Device Management (MDM) for employee laptops and smartphones                                                   | R4, R9          | Medium   | External IT Provider       |
| Segment networks between POS systems, staff devices and guest Wi-Fi                                                             | R2, R4          | Medium   | External IT Provider       |
| Deploy centrally managed endpoint protection across all business devices                                                        | R4, R9          | Medium   | External IT Provider       |
| Conduct annual penetration testing or vulnerability assessments of the e-commerce environment                                   | R6, R7          | Medium   | External Security Provider |
| Obtain cyber insurance appropriate for the organisation's risk profile                                                          | R1–R12          | Medium   | Business Owner             |
| Develop a formal cyber security policy framework covering acceptable use, access control, incident response and data protection | R8, R12         | Medium   | Business Owner             |
| Introduce annual security awareness refresher training and phishing simulations                                                 | R1, R4, R5      | Medium   | Operations Manager         |
| Evaluate the need for outsourced IT/security support or a virtual CISO (vCISO) as the business expands to multiple stores       | All             | Medium   | Business Owner             |

### Expected Outcomes

* Improved protection of endpoint devices.
* Reduced impact of malware and ransomware.
* Stronger governance and policy maturity.
* Security capability aligned with planned business growth.

## Residual Risk

Following implementation of the recommended controls, Urban Thread is expected to reduce the likelihood and impact of its highest-priority cyber security risks. However, some residual risk will remain due to the organisation's reliance on cloud services, third-party providers and limited security resources.

Examples of accepted residual risks include:

| Residual Risk                                                                 | Justification                                                                                                                                  |
| ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Temporary outages of cloud service providers (e.g., Shopify or Microsoft 365) | Outside Urban Thread's direct control; managed through vendor selection and business continuity planning.                                      |
| Emerging zero-day vulnerabilities                                             | Mitigated through timely patching and vendor updates, but cannot be completely eliminated.                                                     |
| Sophisticated phishing or social engineering attacks                          | Reduced through MFA and awareness training, though human error cannot be entirely prevented.                                                   |
| Third-party service compromise                                                | Managed through supplier due diligence and contractual safeguards, recognising that vendor environments remain outside Urban Thread's control. |

These residual risks should be formally accepted by management and reviewed at least annually, or whenever significant changes occur to the business or technology environment.

## Road Summary

| Phase       | Timeline        | Primary Objective                                                                                                         |
| ----------- | --------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Phase 1** | **0–3 Months**  | Address critical risks through identity protection, staff awareness, patching, backups and incident response.             |
| **Phase 2** | **3–6 Months**  | Improve governance, GDPR compliance, third-party risk management and business continuity.                                 |
| **Phase 3** | **6–12 Months** | Build a scalable security capability to support expansion, strengthen endpoint protection and mature security governance. |


##  Success Measures

To evaluate the effectiveness of the treatment plan, Urban Thread should monitor measurable indicators, such as:

* 100% of privileged and business-critical accounts protected by MFA.
* 95% of operating systems and applications patched within 14 days of security updates.
* 100% of employees completing annual cyber security awareness training.
* Quarterly successful restoration tests of business-critical backups.
* Quarterly user access reviews for Microsoft 365, Shopify and payment systems.
* Annual review of the risk register and treatment plan, or sooner if significant business changes occur (e.g., opening new stores).

This phased approach balances security improvements with Urban Thread's financial and staffing constraints while providing a realistic roadmap that can evolve as the organisation grows.

[⬅ Previous: Risk Register](006%20-%20risk_register.md) | [🏠 Home](000%20-%20README.md) | [Next: Recommendations & Roadmap ➡](008%20-%20recommendations_and_roadmap.md)
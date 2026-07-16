Note : We intend to link each asset, threat, vulnerability, business impact, existing controls, and recommended treatment. This demonstrates a complete risk assessment process and provides management with actionable information.

# Risk Register
### Purpose

The risk register records the cyber security risks identified during the assessment and provides a structured approach for evaluating and prioritising them. Each risk is assessed using the following formula:

> Risk Score = Likelihood × Impact

where:

* Likelihood is rated from 1 (Very Low) to 5 (Very High) based on the probability of occurrence.
* Impact is rated from 1 (Negligible) to 5 (Critical) based on the potential effect on business operations, confidentiality, integrity, availability, regulatory compliance, financial loss and reputation.

Risks are then prioritised to support effective resource allocation.

### Risk Rating Criteria

| Risk Score | Priority | Recommended Response                    |
| ---------- | -------- | --------------------------------------- |
| **12–25**  | High     | Immediate treatment (within 30–90 days) |
| **6–11**   | Medium   | Planned mitigation (within 90–180 days) |
| **1–5**    | Low      | Accept, monitor and review annually     |

> Note: Risks involving customer personal data, particularly data relating to minors, may be prioritised above their numerical score because of Urban Thread's legal obligations under UK GDPR and the potential for significant reputational damage.


## Urban Thread Risk Register


| ID      | Risk                                                                  | Asset(s)                        | Threat                          | Key Vulnerability                                 | Likelihood | Impact | Score  | Priority   | Existing Controls                           | Recommended Treatment                                                                                |
| ------- | --------------------------------------------------------------------- | ------------------------------- | ------------------------------- | ------------------------------------------------- | ---------- | ------ | ------ | ---------- | ------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **R1**  | Customer data breach involving personal data (including minors)       | Customer database               | Unauthorised access, phishing   | Weak access controls, limited data governance     | 4          | 5      | **20** | **High**   | Cloud-hosted platform, basic authentication | Enforce MFA, conduct DPIA, implement least privilege, review data retention and encryption           |
| **R2**  | Compromise of payment systems leading to payment fraud                | Payment processor, POS          | Credential theft, payment fraud | Weak account security, excessive permissions      | 3          | 5      | **15** | **High**   | PCI-DSS compliant payment provider          | Enable MFA, restrict administrative access, review payment account permissions, monitor transactions |
| **R3**  | Social media account takeover causing reputational damage             | TikTok, Instagram               | Credential theft, phishing      | Weak passwords, lack of MFA                       | 4          | 4      | **16** | **High**   | Platform authentication                     | Enable MFA, use password manager, restrict admin access, document account recovery procedures        |
| **R4**  | Ransomware encrypts business systems                                  | Employee devices, cloud storage | Malware, phishing               | Limited security awareness, inconsistent patching | 4          | 5      | **20** | **High**   | Cloud backups, antivirus                    | Staff awareness training, regular patching, endpoint protection, test backup restoration             |
| **R5**  | Business Email Compromise (BEC)                                       | Microsoft 365                   | Phishing                        | Weak authentication, limited awareness            | 4          | 4      | **16** | **High**   | Spam filtering                              | MFA, phishing awareness training, email authentication (SPF, DKIM, DMARC), conditional access        |
| **R6**  | Shopify store compromise through misconfiguration or third-party apps | Shopify                         | Web application attack          | Unreviewed plugins, excessive permissions         | 3          | 4      | **12** | **High**   | SaaS platform security                      | Review plugins, remove unused apps, enable security alerts, restrict admin privileges                |
| **R7**  | Third-party supplier compromise                                       | Shopify apps, marketing tools   | Supply chain attack             | Limited vendor due diligence                      | 3          | 4      | **12** | **High**   | Vendor security assurances                  | Verify DPAs, review supplier security, maintain approved vendor list                                 |
| **R8**  | Insider misuse or accidental disclosure of sensitive information      | Customer records, Microsoft 365 | Human error, insider threat     | Excessive privileges, lack of policies            | 3          | 3      | **9**  | **Medium** | Informal access management                  | Implement least privilege, security awareness training, periodic access reviews                      |
| **R9**  | Loss or theft of employee device exposing business information        | Laptops, smartphones            | Theft                           | Device encryption not enforced                    | 3          | 3      | **9**  | **Medium** | Password-protected devices                  | Enable full-disk encryption, remote wipe, device lock policies                                       |
| **R10** | Extended outage of e-commerce platform affecting online sales         | Shopify                         | Service disruption, DDoS        | Dependence on single platform                     | 2          | 4      | **8**  | **Medium** | Vendor resilience                           | Document business continuity procedures, monitor vendor status, prepare customer communications      |
| **R11** | Failure to recover from ransomware due to inadequate backup testing   | Backup systems                  | Ransomware                      | Recovery procedures not tested                    | 2          | 5      | **10** | **Medium** | Cloud backups                               | Test backup restoration quarterly, document recovery procedures                                      |
| **R12** | Regulatory non-compliance with UK GDPR or PCI-DSS                     | Customer data, payment systems  | Compliance failure              | Missing policies, inadequate governance           | 2          | 5      | **10** | **Medium** | Basic privacy notices                       | Conduct compliance reviews, maintain records of processing, review privacy controls                  |


## Risk Summary

### High-Priority Risks (30–90 Days)

These risks have the greatest potential to disrupt business operations, compromise sensitive information or result in regulatory action.

| Risk ID | Priority Reason                                                                                                              |
| ------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **R1**  | Customer data breach involving personal data, particularly minors, creating significant legal and reputational consequences. |
| **R2**  | Payment system compromise affecting revenue and PCI-DSS compliance.                                                          |
| **R3**  | Social media account takeover damaging brand reputation and customer trust.                                                  |
| **R4**  | Ransomware disrupting retail operations and online sales.                                                                    |
| **R5**  | Business Email Compromise leading to fraud or unauthorised access.                                                           |
| **R6**  | Shopify compromise affecting online sales and customer data.                                                                 |
| **R7**  | Third-party supplier compromise impacting business services and customer information.                                        |


### Medium-Priority Risks (90–180 Days)

These risks are important but are either less likely or have a more limited business impact.

- Insider misuse or accidental disclosure
- Loss or theft of employee devices
- E-commerce platform outage
- Backup recovery failure
- Regulatory compliance gaps
- Low-Priority Risks (Monitor)

At present, no significant risks fall within the low-priority category. This reflects Urban Thread's dependence on digital services, limited security resources and regulatory obligations. Lower-risk items may emerge after higher-priority controls have been implemented and residual risk has been reassessed.


## Overall Risk Profile

The assessment identified 12 principal cyber security risks, of which:

| Priority   | Number of Risks | Percentage |
| ---------- | --------------: | ---------: |
| **High**   |               7 |        58% |
| **Medium** |               5 |        42% |
| **Low**    |               0 |         0% |


The overall risk profile indicates that Urban Thread's greatest exposure lies in identity compromise, customer data protection, ransomware, cloud service security, and third-party dependencies. These risks are amplified by the organisation's reliance on cloud platforms, its processing of children's personal data, and its limited internal cyber security capability. Consequently, the recommended treatment plan focuses on implementing practical, cost-effective controls—such as MFA, least-privilege access, staff awareness training, secure configuration, and tested backup procedures—that align with Urban Thread's budget, staffing levels and growth ambitions.


[⬅ Back to Home](000%20-%20README.md)
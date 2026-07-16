# Risk Context

## 2.0  Urban Thread Risk Profile

Urban Thread operates in a business environment where cyber security risks are influenced by its business model, customer demographics, regulatory obligations, and limited operational resources. As a growing small retail business, the organisation relies heavily on cloud-based services, e-commerce, third-party providers, and social media to generate revenue. Consequently, successful cyber attacks could disrupt business operations, expose customer data, damage the company's reputation, and hinder future expansion.

The organisation's overall cyber risk profile is primarily driven by four key factors:

## 2.1  Regulatory and Compliance Exposure

Urban Thread processes payment card transactions and stores personal information relating to its customers, including a significant proportion of individuals under the age of 18. As a result, the organisation must comply with:

* **UK GDPR** and the **Data Protection Act 2018** for the protection of personal data
* **UK GDPR Article 8**, requiring appropriate handling of children's personal data
* **PCI-DSS** requirements through its third-party payment processor

Failure to comply may result in:

* Regulatory investigations by the Information Commissioner's Office (ICO)
* GDPR penalties of up to **£17.5 million or 4% of annual worldwide turnover** (whichever is greater)
* PCI-DSS non-compliance penalties, increased transaction fees, chargeback liability, or suspension of card processing services
* Mandatory breach notifications and legal liabilities

Because customer data includes information relating to minors, any personal data breach is considered a high-priority business risk regardless of its likelihood.


## 2.2. Reputational Sensitivity

Urban Thread's commercial success depends heavily on customer trust and social media engagement. Approximately 60% of sales originate through its online channels, while TikTok and Instagram represent its primary marketing and customer acquisition platforms.

Consequently, incidents such as:

* customer data breaches,
* social media account takeovers,
* website defacement,
* ransomware attacks, or
* prolonged online service outages

could rapidly reduce customer confidence, generate negative publicity, and directly affect revenue.

Unlike larger organisations, small retailers often have limited ability to recover from significant reputational damage, making brand protection a critical security objective.


## 2.3. Operational and Resource Constraints

Urban Thread currently operates with:

* one physical retail store,
* approximately 12 employees,
* an annual cyber security budget of **£5,000–£10,000**, and
* no dedicated IT or cyber security personnel.

Technology and security responsibilities are managed by an operations manager who can dedicate approximately **five hours per week** to IT-related activities.

These constraints mean the organisation cannot realistically implement enterprise-grade security technologies such as:

* Security Information and Event Management (SIEM)
* Extended Detection and Response (XDR)
* Security Operations Centres (SOC)
* Dedicated cyber security teams

Instead, risk treatment must focus on affordable, cloud-native security controls, automation, managed services, and staff awareness training.

Cyber security should therefore be viewed as a **business enabler** that supports secure growth rather than as an operational overhead.



## 2.4. Business Growth and Third-Party Dependency

Urban Thread plans to expand from one retail location to three stores within the next year. This expansion will introduce:

* additional employees,
* more POS terminals,
* increased customer data,
* centralised inventory management,
* greater reliance on cloud services, and
* a larger attack surface.

The business also depends heavily on third-party providers, including:

* Shopify (or equivalent e-commerce platform)
* Payment processors
* Microsoft 365 or Google Workspace
* Email marketing providers
* Google Analytics
* Meta/Facebook advertising platforms

Although these services reduce infrastructure management responsibilities, they introduce supply chain and third-party security risks that require effective vendor management, access control, and periodic security reviews.



## 2.5. Risk Appetite

Urban Thread has a **low-to-moderate risk appetite**.

The organisation is willing to accept a limited amount of residual cyber risk in exchange for maintaining cost efficiency and supporting business growth. However, risks involving customer personal data, payment processing, business continuity, and regulatory compliance fall outside the organisation's acceptable tolerance.

Accordingly, Urban Thread prioritises investments that provide the greatest reduction in risk at the lowest cost, including:

* Multi-Factor Authentication (MFA)
* regular software patching
* staff cyber security awareness training
* secure cloud configuration
* access control and least privilege
* vendor due diligence
* data backup and recovery procedures

Enterprise-scale security platforms and dedicated security personnel are considered outside the current budget and are deferred until future business expansion.



# 2.6. Assessment Methodology

This cyber security risk assessment is structured using the **NIST Cybersecurity Framework (CSF) 2.0**, with risk identification and evaluation informed by the principles of **NIST SP 800-30: Guide for Conducting Risk Assessments**. The assessment also considers relevant requirements from **UK GDPR**, **PCI-DSS**, and industry good practice where appropriate.

## 2.6.1. Assessment Objectives

The assessment aims to:

* identify Urban Thread's most significant cyber security risks;
* evaluate the likelihood and business impact of identified threats;
* prioritise risks based on their severity;
* recommend practical, cost-effective controls appropriate for a small business; and
* support secure business growth while maintaining regulatory compliance.


## 2.6.2. Why NIST CSF?

The NIST Cybersecurity Framework was selected because it provides a practical, flexible and widely recognised approach suitable for small and medium-sized businesses.

Key advantages include:

* framework-agnostic and compatible with ISO/IEC 27001, PCI-DSS and UK GDPR;
* organised around six core functions—**Govern, Identify, Protect, Detect, Respond and Recover**—that are easily understood by technical and non-technical stakeholders;
* supports continuous improvement as the organisation grows; and
* enables future alignment with more mature security frameworks without requiring major changes.



## 2.6.3.   Risk Assessment Approach

Each identified risk is assessed by considering:

* the threat source,
* the vulnerability being exploited,
* the affected business assets,
* the potential business consequences,
* existing security controls, and
* recommended mitigating actions.

Risks are evaluated using a qualitative scoring model based on **Likelihood** and **Business Impact**.

**Risk Scoring Formula**

> **Risk Score = Likelihood × Impact**

Where:

* **Likelihood** is scored from **1 (Very Low)** to **5 (Very High)** based on the probability of occurrence.
* **Impact** is scored from **1 (Negligible)** to **5 (Critical)** based on the effect on confidentiality, integrity, availability, legal compliance, financial loss and reputation.



#### 2.6.4  Risk Prioritisation

| Risk Score | Priority | Recommended Response                                    |
| ---------- | -------- | ------------------------------------------------------- |
| **12–25**  | High     | Immediate treatment within **30–90 days**               |
| **6–11**   | Medium   | Planned mitigation within **90–180 days**               |
| **1–5**    | Low      | Accept or monitor; review during annual risk assessment |

Where regulatory obligations or children's personal data are involved, risks may be prioritised above their numerical score to reflect Urban Thread's compliance responsibilities and low tolerance for data protection failures.


# 3.0   Methodology

## 3.1  Assessment Purpose

This cyber security risk assessment evaluates Urban Thread's current cyber security exposure by identifying critical assets, potential threats, existing vulnerabilities and associated business risks.

The purpose of the assessment is to provide a practical security improvement roadmap that reduces the likelihood and impact of cyber incidents while supporting Urban Thread's business objectives, regulatory obligations and planned expansion.

The assessment has been designed to reflect the operational realities of a small retail organisation, including limited internal security resources, reliance on cloud services and a constrained security budget.

## 3.2  Assessment Scope

The assessment covers the systems, information assets, business processes and third-party services that support Urban Thread's retail and e-commerce operations.
The resulting risk register and recommendations are designed to reflect Urban Thread's current operational environment while providing a roadmap that can scale alongside the organisation's planned business expansion.

### 3.2.1   Business Environment

The assessment considers:

* e-commerce platform and online store
* point-of-sale (POS) systems
* payment processing
* customer and employee data
* cloud productivity services
* social media accounts
* third-party suppliers and SaaS providers
* endpoint devices used by employees
* backup and business continuity arrangements
* one Birmingham retail store.
* approximately 12 employees.
* 60% online sales and 40% in-store sales.
* future expansion to Manchester and London stores.
* reliance on social media platforms for marketing and customer engagement.

### 3.2.2   Technology Scope

The following technology areas are included:

***E-Commerce Platform***

Included:

- Shopify or equivalent SaaS platform.
- Store administration accounts.
- Third-party applications and plugins.
- Customer account management.
- Product and order information.

Excluded: Security of Shopify's underlying infrastructure remains the responsibility of the provider.

**Payment Processing**

Included:

- Payment account access controls.
- Merchant account security.
- PCI-DSS responsibilities retained by Urban Thread.

**Excluded:** Payment card processing infrastructure managed by the third-party payment provider.

Business Systems Included:

- Microsoft 365 or Google Workspace.
- Point-of-sale (POS) systems.
- Inventory management systems.
- Employee devices.
- Cloud storage services

[⬅ Previous: Key Assumptions](001%20-%20key_assumptions.md) | [🏠 Home](000%20-%20README.md) | [Next: Asset Identification ➡](003%20-%20asset_identification.md)

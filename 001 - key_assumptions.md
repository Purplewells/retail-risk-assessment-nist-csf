## Overview for Risk Assessment

**Urban Thread** is a UK-based small to medium sized business fashion retailer targeting teenagers and young adults through a combination of e-commerce and a physical retail presence. The business currently operates **one store in Birmingham** with **12 full-time employees**, generating approximately **60% of its revenue from online sales** and **40% from in-store purchases**. The company relies heavily on **TikTok and Instagram** for customer acquisition and brand awareness, making its online presence a critical business asset.

The organisation has ambitious growth plans to expand to **three stores** (Birmingham, Manchester and London) within the next year, increasing its workforce to approximately **25 employees**. This expansion will introduce additional point-of-sale (POS) systems, a larger customer database, and more complex operational processes, all of which will increase the organisation's cyber security risk exposure.

From a technology perspective, Urban Thread follows a cloud-first approach suitable for a small business. Its e-commerce platform is assumed to be **Shopify (or an equivalent SaaS platform)**, while payment processing is outsourced to a **PCI-DSS compliant third-party provider** such as Stripe, Square or Shopify Payments. Customer information, including contact details, purchase history and limited payment metadata, is stored in a single cloud-hosted customer database. Staff use cloud productivity services such as **Microsoft 365 or Google Workspace**, with no on-premises infrastructure or enterprise directory services.

The organisation operates with significant resource constraints. It has an annual cyber security budget of approximately **£5,000–£10,000** and no dedicated IT or cyber security personnel. Instead, an operations manager spends around **five hours per week** managing technology and security responsibilities alongside their primary role. Consequently, Urban Thread depends on low-cost security controls, cloud-native security features, automation and outsourced expertise rather than enterprise security platforms.

The primary regulatory obligations are **UK GDPR** and **PCI-DSS**. Because approximately **40% of Urban Thread's customers are under the age of 18**, the organisation must also comply with **UK GDPR Article 8** regarding children's personal data. This significantly increases the potential legal, financial and reputational impact of any customer data breach involving minors and makes the protection of personal information a high-priority business objective.

Urban Thread also relies on several third-party providers, including payment processors, web hosting, analytics platforms, social media advertising services and email marketing tools. While these providers reduce the need for internal infrastructure management, they introduce third-party supply chain risks that require appropriate vendor due diligence, Data Processing Agreements (DPAs), and periodic security reviews.

The company's risk appetite is **low to moderate**. Management aims to support business growth while maintaining regulatory compliance but recognises that limited financial and staffing resources prevent investment in enterprise-grade cyber security technologies. As a result, Urban Thread accepts a measured level of residual risk in exchange for cost-effective security controls, focusing investment on high-impact, affordable measures such as multi-factor authentication (MFA), regular patch management, staff security awareness training, secure configuration, access control and vendor management.

Overall, Urban Thread's cyber security risk profile is characterised by a strong dependence on cloud services, social media, and third-party vendors, combined with the processing of children's personal data, limited internal security resources, and rapid business growth. These factors make data protection, account security, third-party risk management and business continuity the most significant areas for the organisation's cyber security risk assessment.


## Budget vs Coverage Trade-Off

| Priority | Funded            |Not Funded (Accepted Risk) |
| -------- | ----------------- |---------------------------|
| High     | PCI-DSS compliance, GDPR data protection, incident response basics |Real-time threat detection, penetration testing|
|Medium    |Social media MFA, basic security training, vendor questionnaires|Advanced threat monitoring, security awareness platform|
|Low | Annual access review, tabletop exercises | Cyber insurance, redundant systems, DDoS mitigation|

[⬅ Back to Home](000%20-%20README.md) | [Next: Risk Content & Assessment Methodology ➡](002%20-%20risk_content.md)
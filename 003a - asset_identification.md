# Asset Identification
### Purpose

Asset identification is the process of identifying the information, systems, services and business resources that support Urban Thread's operations. Understanding what assets exist and their business value enables the organisation to prioritise security controls, assess potential threats, and evaluate the impact of cyber security incidents.

Urban Thread relies heavily on cloud-based services and third-party platforms to conduct day-to-day business. Consequently, protecting customer information, payment systems, online sales channels and business communications is essential to maintaining operational continuity, regulatory compliance and customer trust.

| Asset                                  | Description                                                                                 | Information Processed                                                                                  | Business Importance                                                                                                                           |
| -------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **Customer Database**                  | Stores customer profiles and purchase history within the e-commerce platform.               | Personal information, contact details, order history, marketing preferences, limited payment metadata. | Critical – Supports customer service, marketing and order fulfilment. Loss or breach could result in GDPR violations and reputational damage. |
| **E-commerce Platform (Shopify)**      | Primary online sales platform generating approximately 60% of company revenue.              | Product catalogue, customer accounts, online orders, inventory information.                            | Critical – Outages or compromise would directly impact revenue and customer confidence.                                                       |
| **Payment Processing System**          | Third-party payment gateway used to process online and in-store card payments.              | Payment transactions, tokenised card information, transaction records.                                 | Critical – Essential for revenue generation and PCI-DSS compliance.                                                                           |
| **Point-of-Sale (POS) Systems**        | In-store payment terminals used by retail staff.                                            | Sales transactions, inventory updates, receipt information.                                            | High – Required for retail operations and inventory accuracy.                                                                                 |
| **Microsoft 365 / Google Workspace**   | Cloud productivity and communication platform used by staff.                                | Emails, documents, calendars, business communications.                                                 | High – Compromise could expose sensitive information or enable phishing and business email compromise (BEC).                                  |
| **Social Media Accounts**              | Official TikTok and Instagram business accounts used for marketing and customer engagement. | Marketing content, customer interactions, brand communications.                                        | High – Account takeover could damage reputation, spread fraudulent content and reduce customer trust.                                         |
| **Inventory Management System**        | Tracks stock levels, suppliers and product availability across retail channels.             | Product records, supplier information, stock movements.                                                | High – Essential for order fulfilment and business operations.                                                                                |
| **Employee Devices**                   | Laptops, tablets and smartphones used by staff to access business systems.                  | Emails, customer information, business applications, credentials.                                      | High – Lost or compromised devices may provide attackers with access to business systems.                                                     |
| **Cloud Storage and Shared Documents** | Shared file repositories used for operational documents and reports.                        | Business documents, policies, financial records, supplier information.                                 | Medium–High – Unauthorised access could expose confidential business information.                                                             |
| **Backup Systems**                     | Cloud backups supporting business recovery after system failure or cyber incidents.         | Copies of business systems and operational data.                                                       | Critical – Essential for recovering from ransomware, accidental deletion and system failures.                                                 |


## Asset Classification

To prioritise security controls, Urban Thread classifies assets according to their importance to business operations.
| Classification | Description                                                                                                                                                  | Urban Thread Examples                                                            |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------- |
| **Critical**   | Essential for business continuity, regulatory compliance or revenue generation. Loss or compromise would have severe operational and financial consequences. | Customer database, Shopify store, payment processing, backups                    |
| **High**       | Important operational assets whose compromise would significantly disrupt business operations or damage reputation.                                          | POS systems, Microsoft 365, social media accounts, inventory management          |
| **Medium**     | Supports business operations but has limited impact if temporarily unavailable.                                                                              | Internal documents, shared storage, administrative systems                       |
| **Low**        | Publicly available or non-sensitive information with minimal business impact if disclosed.                                                                   | Public website content, marketing images, publicly available product information |


## Information Assets

Urban Thread processes several categories of information requiring different levels of protection.

| Information Asset               | Confidentiality Requirement | Reason                                                                     |
| ------------------------------- | --------------------------- | -------------------------------------------------------------------------- |
| Customer personal data          | High                        | Protected under UK GDPR, particularly for customers under 18.              |
| Employee information            | High                        | Payroll, HR and employment records contain sensitive personal information. |
| Payment transaction information | High                        | Required for PCI-DSS compliance and fraud prevention.                      |
| Business emails                 | High                        | May contain confidential customer, supplier and financial information.     |
| Sales and financial reports     | High                        | Commercially sensitive business information.                               |
| Marketing content               | Medium                      | Valuable but largely intended for public distribution.                     |
| Product catalogue               | Low                         | Public information supporting sales activities.                            |


## Asset Ownership

Assigning ownership ensures accountability for protecting business assets.

| Asset                 | Typical Owner                                    |
| --------------------- | ------------------------------------------------ |
| Customer database     | Business Owner / Operations Manager              |
| Shopify Store         | E-commerce Manager / Business Owner              |
| Payment Processing    | Finance Manager / Business Owner                 |
| POS Systems           | Store Manager                                    |
| Microsoft 365         | Operations Manager                               |
| Social Media Accounts | Marketing Manager                                |
| Inventory Management  | Operations Manager                               |
| Employee Devices      | Individual Employees (with management oversight) |
| Backup Systems        | Operations Manager / Managed Service Provider    |

## Summary

Urban Thread's most valuable assets are those that directly support revenue generation, regulatory compliance and customer trust. The customer database, e-commerce platform, payment systems and backup infrastructure are classified as critical assets because their compromise would have the greatest impact on the organisation. Supporting assets—including Microsoft 365, POS systems, employee devices and social media accounts—also require strong protection due to their role in business operations and their potential to provide attackers with access to more sensitive systems.

This asset inventory provides the foundation for the next stage of the assessment, where threats and vulnerabilities are analysed against each asset to determine the organisation's overall cyber security risk profile.
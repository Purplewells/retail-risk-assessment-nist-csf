# Threat Identification

## Purpose

Threat identification involves identifying events or actors that could exploit vulnerabilities in Urban Thread's information systems, resulting in harm to the confidentiality, integrity, or availability of business assets. Identifying credible threats enables the organisation to understand its exposure and prioritise security controls before incidents occur.

Given Urban Thread's reliance on cloud services, third-party providers, e-commerce platforms and social media, the organisation faces a range of external and internal cyber threats. These threats have been identified based on Urban Thread's business model, technology environment, regulatory obligations, and current threat landscape.


## Threat Sources

Threats to Urban Thread originate from several sources.

| Threat Source                          | Description                                                                                   | Examples                                                                 |
| -------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **Cybercriminals**                     | Financially motivated attackers seeking to steal money, payment information or personal data. | Ransomware, phishing, credential theft, account compromise.              |
| **Insiders**                           | Employees or contractors who intentionally or accidentally compromise security.               | Accidental data disclosure, misuse of privileged access, weak passwords. |
| **Third-Party Suppliers**              | Security weaknesses within external service providers or software vendors.                    | Compromised plugins, SaaS provider outages, supply chain attacks.        |
| **Hacktivists**                        | Individuals or groups motivated by ideology or publicity.                                     | Website defacement, social media hijacking.                              |
| **Opportunistic Attackers**            | Automated attacks scanning the Internet for vulnerable systems.                               | Credential stuffing, automated bot attacks, vulnerability scanning.      |
| **Environmental & Operational Events** | Non-malicious events affecting system availability.                                           | Hardware failure, cloud outages, accidental deletion, power loss.        |



## Key Threats

The following threats are considered the most relevant to Urban Thread.

| Threat                            | Description                                                                                                      | Primary Assets Targeted                                    | Potential Business Impact                                                                          |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Phishing and Social Engineering** | Fraudulent emails, SMS messages or social media communications designed to steal credentials or install malware. | Microsoft 365, Shopify, employee accounts                  | Credential theft, business email compromise, data breaches.                                        |
| **Ransomware**                      | Malware that encrypts business systems and demands payment for recovery.                                         | Customer database, employee devices, file storage, backups | Business interruption, data loss, financial loss and reputational damage.                          |
| **Credential Theft**                | Theft or reuse of usernames and passwords through phishing, password reuse or data breaches.                     | Microsoft 365, Shopify, payment systems, social media      | Unauthorised access, fraud, account takeover.                                                      |
| **Social Media Account Takeover**   | Compromise of TikTok or Instagram business accounts.                                                             | Social media platforms                                     | Brand damage, fraudulent promotions, loss of customer trust.                                       |
| **Customer Data Breach**            | Unauthorised disclosure of customer information through compromised systems or accounts.                         | Customer database                                          | GDPR violations, ICO investigations, reputational damage and customer notification requirements.   |
| **Payment Fraud**                   | Unauthorised payment transactions or abuse of payment systems.                                                   | Payment processor, POS systems                             | Financial losses, PCI-DSS implications and customer disputes.                                      |
| **Web Application Attack**          | Exploitation of vulnerabilities in Shopify configurations, themes or third-party applications.                   | E-commerce platform                                        | Website compromise, data exposure, service disruption.                                             |
| **Third-Party Supply Chain Attack** | Compromise of software vendors or service providers used by Urban Thread.                                        | Shopify apps, payment providers, Microsoft 365             | Data exposure, service disruption and unauthorised access.                                         |
| **Malware Infection**               | Installation of malicious software through downloads, email attachments or infected websites.                    | Employee devices, Microsoft 365                            | Data theft, ransomware, operational disruption.                                                    |
| **Denial-of-Service (DoS/DDoS)**    | Attempts to overwhelm online services, making them unavailable to customers.                                     | Shopify website                                            | Loss of online sales and customer dissatisfaction.                                                 |
| **Insider Threat**                  | Deliberate or accidental actions by employees leading to security incidents.                                     | Customer records, business documents, POS systems          | Data leakage, fraud or operational disruption.                                                     |
| **Loss or Theft of Devices**        | Employee laptops or mobile devices are lost or stolen.                                                           | Employee devices                                           | Exposure of credentials or sensitive business information if devices are not adequately protected. |


## Threat Mapping to Critical Assets

| Asset                 | Principal Threats                                                  |
| --------------------- | ------------------------------------------------------------------ |
| Customer Database     | Data breach, ransomware, insider threat, unauthorised access       |
| Shopify Store         | Web application attacks, credential theft, plugin compromise, DDoS |
| Payment Processing    | Payment fraud, credential compromise, third-party attacks          |
| POS Systems           | Malware, unauthorised access, payment fraud                        |
| Microsoft 365         | Phishing, business email compromise, malware, credential theft     |
| Social Media Accounts | Account takeover, phishing, impersonation                          |
| Inventory Management  | Insider threats, ransomware, unauthorised modification             |
| Employee Devices      | Malware, ransomware, theft, phishing                               |
| Backup Systems        | Ransomware, accidental deletion, misconfiguration                  |


## Threat Likelihood

Considering Urban Thread's technology environment, staffing constraints and reliance on cloud services, the following threats are assessed as the most likely.

| Threat                        | Likelihood     | Justification                                                                                |
| ----------------------------- | -------------- | -------------------------------------------------------------------------------------------- |
| Phishing                      | **Very High**  | Most common initial attack vector against SMBs; limited IT oversight increases exposure.     |
| Credential Theft              | **Very High**  | Employees use multiple cloud services; password reuse and phishing increase risk.            |
| Ransomware                    | **High**       | Common consequence of successful phishing or compromised credentials.                        |
| Customer Data Breach          | **High**       | Personal data is stored centrally and accessed through multiple cloud platforms.             |
| Social Media Account Takeover | **High**       | Business relies heavily on Instagram and TikTok; high-value targets for attackers.           |
| Third-Party Compromise        | **Medium**     | Dependence on SaaS providers and plugins introduces supply chain risk.                       |
| Insider Threat                | **Medium**     | Small workforce limits exposure but accidental mistakes remain likely.                       |
| Payment Fraud                 | **Medium**     | PCI-compliant payment processor reduces likelihood, but account compromise remains possible. |
| DDoS Attack                   | **Low–Medium** | Shopify provides built-in resilience, reducing direct exposure.                              |
| Physical Device Theft         | **Medium**     | Mobile devices and laptops may contain business credentials and locally stored data.         |


## Threat Assessment Summary

Urban Thread's threat landscape is dominated by attacks that exploit human behaviour and cloud-based identities rather than direct attacks on infrastructure. Phishing, credential theft and ransomware represent the highest-priority threats because they can compromise multiple critical assets, including Microsoft 365, the Shopify store, customer data and payment systems. The organisation's dependence on social media for marketing also makes account takeover a significant business risk due to its potential impact on customer trust and brand reputation.

These identified threats will be assessed against known vulnerabilities in the next stage of the assessment to determine the overall level of risk and identify appropriate mitigation measures.

[⬅ Back to Home](000%20-%20README.md) | [Next: Vulnerability Assessment ➡](005%20-%20vulnerability_assessment.md)
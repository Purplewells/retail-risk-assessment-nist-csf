# Glossary of Terminologies

## Frameworks & Standards
- **NIST** — National Institute of Standards and Technology; a U.S. government agency (part of the Department of Commerce) that develops standards and guidelines, not just for cybersecurity but for measurement, technology and industry standards broadly.
- **NIST CSF (Cybersecurity Framework) 2.0** — a voluntary framework of best practices for managing cybersecurity risk, organised around six core functions (see below).
- **NIST SP 800-30** — NIST Special Publication 800-30, "Guide for Conducting Risk Assessments"; provides the methodology this assessment's risk scoring approach is based on.
- **ISO/IEC 27001** — an international standard for information security management systems (ISMS); referenced as an out-of-scope certification for this engagement's maturity stage.
- **PCI-DSS** — Payment Card Industry Data Security Standard; a set of security requirements for organisations that store, process or transmit card payment data.
- **UK GDPR / GDPR** — UK General Data Protection Regulation; the UK's data protection and privacy law governing how personal data must be handled.
- **GDPR Article 8** — the GDPR provision setting special conditions for processing children's personal data (relevant given ~40% of Urban Thread's customers are under 18).
- **Data Protection Act 2018** — the UK's domestic data protection legislation, which sits alongside and supplements UK GDPR.
- **ICO (Information Commissioner's Office)** — the UK's independent regulator for data protection and information rights.

## NIST CSF Core Functions
- **Govern** — establish and monitor the organisation's cybersecurity risk management strategy, expectations and policy.
- **Identify** — understand the organisation's assets, business context and risk exposure.
- **Protect** — implement safeguards to limit or contain the impact of a security event.
- **Detect** — identify the occurrence of a security event in a timely manner.
- **Respond** — take action once a security incident is detected.
- **Recover** — restore capabilities and services impaired by a security incident.

## Risk Methodology Terms
- **Asset** — anything of value to the organisation (data, systems, people, processes) that needs protecting.
- **Threat** — a potential cause of an unwanted incident that could harm an asset (e.g. a threat actor or threat source).
- **Vulnerability** — a weakness that a threat could exploit to cause harm.
- **Likelihood** — the estimated probability that a given threat will exploit a given vulnerability.
- **Impact** — the estimated severity of harm to the business if a risk materialises.
- **Inherent risk** — the level of risk that exists before any controls are applied.
- **Residual risk** — the level of risk that remains after controls have been applied.
- **Risk register** — a structured log of identified risks, their scoring, ownership and status.
- **Risk appetite** — the amount and type of risk an organisation is willing to accept in pursuit of its objectives.
- **Risk treatment** — the response chosen for a given risk: mitigate (reduce it), transfer (e.g. insurance), accept (tolerate it), or avoid (stop the activity causing it).
- **Control** — a safeguard or countermeasure (existing or recommended) that reduces risk.
- **CIA (Confidentiality, Integrity, Availability)** — the three core properties information security aims to protect: keeping data private, accurate, and accessible when needed.

## Security Concepts & Technologies
- **MFA (Multi-Factor Authentication)** — requiring more than one form of verification (e.g. password plus a code) to access an account.
- **IAM (Identity and Access Management)** — the policies and tools used to ensure the right people have the right access to systems.
- **Least privilege** — the principle of granting users only the minimum access needed to do their job.
- **Phishing / Social engineering** — deceptive tactics used to trick people into revealing credentials or taking harmful actions.
- **Credential stuffing / Credential theft** — attacks that use stolen or guessed login credentials to gain unauthorised access.
- **Ransomware / Malware** — malicious software; ransomware specifically encrypts data and demands payment for its release.
- **BEC (Business Email Compromise)** — a scam where an attacker impersonates a trusted party via email to trigger fraudulent payments or data disclosure.
- **DoS / DDoS (Denial-of-Service / Distributed Denial-of-Service)** — an attack that overwhelms a system to make it unavailable to legitimate users.
- **Account takeover** — unauthorised control of a user's account, typically via stolen credentials.
- **Supply chain attack** — a compromise introduced via a third-party vendor or supplier rather than directly.
- **Insider threat** — risk posed by someone with legitimate access (staff, contractor) misusing that access.
- **Web application attack** — an attack targeting vulnerabilities in a website or web app (e.g. the e-commerce platform).
- **Endpoint security** — protection applied to individual devices (laptops, tills, phones) connecting to the network.
- **Patch management** — the process of keeping software up to date with security fixes.
- **Network segmentation** — dividing a network into isolated zones to limit how far an attacker can move if one part is compromised.
- **SIEM (Security Information and Event Management)** — a tool that collects and analyses security event logs to detect threats.
- **XDR (Extended Detection and Response)** — a security tool that correlates data across endpoints, network and cloud to detect and respond to threats.
- **SOC (Security Operations Centre)** — a team or service responsible for monitoring and responding to security events.
- **MDM (Mobile Device Management)** — tools used to secure and manage staff mobile/laptop devices, including remote wipe.
- **Full-disk encryption** — encrypting an entire device's storage so data is unreadable without authentication.
- **Remote wipe** — the ability to remotely erase data from a lost or stolen device.
- **SPF, DKIM, DMARC** — email authentication standards that help prevent email spoofing and phishing using a domain's name.
- **Conditional access** — access policies that grant or block sign-in attempts based on context (e.g. device, location, risk level).
- **Penetration testing** — authorised, simulated attacks used to find exploitable weaknesses before real attackers do.
- **vCISO (virtual Chief Information Security Officer)** — outsourced, part-time CISO-level security leadership, common for SMBs that can't justify a full-time hire.
- **DR (Disaster Recovery) / BCP (Business Continuity Plan)** — plans for restoring systems (DR) and maintaining critical operations (BCP) after a disruptive event.
- **Incident Response Plan** — the documented process for detecting, containing and recovering from a security incident.
- **Tabletop exercise** — a discussion-based simulation used to test and improve an incident response or continuity plan.
- **Zero-day vulnerability** — a flaw that is exploited before a fix is available.
- **Data classification** — categorising data by sensitivity to determine how it should be protected.
- **Data minimisation** — collecting and retaining only the personal data necessary for a stated purpose (a GDPR principle).
- **Retention and deletion policy** — rules governing how long data is kept and when/how it is disposed of.

## Business & Organisational Terms
- **SME / SMB** — small and medium-sized enterprise/business; the scale of organisation this assessment is scoped for.
- **SaaS (Software as a Service)** — software hosted and run by a third-party provider and accessed over the internet (e.g. an e-commerce platform).
- **POS (Point-of-Sale)** — the hardware/software used to process in-store sales and payments.
- **Cloud-first / Cloud-native** — an approach or system designed to run primarily or entirely in cloud infrastructure rather than on-premises.
- **Attack surface** — the sum of all points where an unauthorised user could try to enter or extract data from a system.
- **Cyber insurance** — insurance cover for financial losses resulting from cyber incidents.
- **Chargeback** — a forced reversal of a card payment, typically disputed by the cardholder.
- **Merchant account** — a bank account that lets a business accept card payments.
- **Tokenised card information** — card data replaced with a non-sensitive substitute (token) to reduce exposure of the real card number.
- **DPA (Data Processing Agreement)** — a GDPR-required contract between a data controller and a data processor governing how personal data is handled; also used for Disaster Recovery/other contexts, so read in context.
- **DPIA (Data Protection Impact Assessment)** — an assessment required under GDPR for processing activities likely to result in high risk to individuals' rights.

---
[⬅ Previous: Recommendations & Roadmap](008%20-%20recommendations_and_roadmap.md) | [🏠 Home](000%20-%20README.md)

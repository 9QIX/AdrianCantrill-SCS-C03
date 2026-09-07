# AWS Certified Security – Specialty (SCS-C03) Study Notes

Exam-focused Markdown chapters adapted from the Adrian Cantrill AWS Security Specialty course archive and updated for the current SCS-C03 domain structure. The repository contains 205 lessons with concise explanations, architecture and policy analysis, troubleshooting guidance, exam traps, memory hooks, review questions, and links to official AWS documentation used during editing.

## Study Path

| Section | Lessons | Focus |
| --- | ---: | --- |
| [I. Introduction & Scenario](<I. INTRODUCTION & SCENARIO>) | 6 | Course context and the Animals4life scenario |
| [II. Course Fundamentals and AWS Accounts](<II. Course Fundamentals and AWS Accounts>) | 9 | Accounts, root-user protection, IAM basics, MFA, and AWS CLI access |
| [III. Networking and Technical Fundamentals](<III. Networking and Technical Fundamentals (moved to dedicated course)>) | 1 | Scope and prerequisite networking guidance |
| [IV. Management and Security Governance](<IV. Domain 6 - Management and Security Governance [SCS-C02]>) | 23 | Organizations, governance services, and infrastructure as code |
| [V. Identity and Access Management](<V. Domain 4 - Identity and Access Management>) | 38 | IAM policy evaluation, roles, federation, Identity Center, and S3 authorization |
| [VI. Threat Detection and Incident Response](<VI. Domain 1 - Threat Detection and Incident Response>) | 7 | GuardDuty, Security Hub CSPM, Detective, abuse response, and session containment |
| [VII. Infrastructure Security](<VII. Domain 3 - Infrastructure Security>) | 58 | VPC security, private connectivity, encryption, edge protection, and network defenses |
| [VIII. Security Logging and Monitoring](<VIII. Domain 2 - Security Logging and Monitoring [SCS-C02]>) | 25 | Audit trails, monitoring, configuration evidence, and security visibility |
| [IX. Data Protection](<IX. Domain 5 - Data Protection>) | 28 | Encryption, key management, secrets, certificates, backups, and data discovery |
| [X. Exam Prep](<X. EXAM PREP>) | 8 | Question technique, walkthroughs, and practice-exam guidance |
| [XI. Completion](<XI. CONGRATULATIONS - YOU'VE FINISHED>) | 2 | Final review and next steps |

## Architecture Maps

- [Multi-account governance and workforce access](<IV. Domain 6 - Management and Security Governance [SCS-C02]/01. AWS Organizations.md#visual-infrastructure-map>)
- [AWS STS temporary-credential flow](<V. Domain 4 - Identity and Access Management/07. Security Token Service (STS).md#architecture-and-service-relationships>)
- [Detection-to-response workflow](<VI. Domain 1 - Threat Detection and Incident Response/03. AWS Security Hub.md#architecture-and-service-relationships>)
- [AWS Network Firewall traffic path](<VII. Domain 3 - Infrastructure Security/57. AWS Network Firewall - 101.md#architecture-and-service-relationships>)
- [Organization-wide CloudTrail architecture](<VIII. Domain 2 - Security Logging and Monitoring [SCS-C02]/17. [SHAREDALL] [DEMO] Implementing an Organizational Trail.md#architecture-and-service-relationships>)
- [KMS envelope-encryption flow](<IX. Domain 5 - Data Protection/06. Envelope Encryption.md#architecture-and-service-relationships>)

## How to Use These Notes

1. Follow the sections in order for full-course study, or open the domain matching a weak exam objective.
2. Start each lesson with **Exam Alignment** to identify its domain, services, importance, and core skill.
3. Use **Exam Decision Guide**, **Common Exam Traps**, and **Memory Hooks** for rapid revision.
4. Complete the **Self-Check Questions** before expanding the answers.
5. Review **Updated Information as of 2026-09-07** when the source lesson used older terminology or behavior.

## Editorial Scope

- Older SCS-C02 organization is mapped to the six current SCS-C03 domains inside each lesson, even where legacy directory names remain for source traceability.
- Demonstrations preserve their learning objective, prerequisites, validation, and safe cleanup guidance while removing click-by-click filler.
- Current-behavior corrections cite only official AWS sources actually used for the lesson.
- These notes are independent study material, not certification exam dumps or a substitute for hands-on practice and the current official exam guide.

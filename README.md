# PayGo-GDPR-SOC2-Compliance-Assessment
GRC portfolio project demonstrating GDPR data mapping, SOC 2 readiness assessment, risk analysis, and remediation planning.
# PayGo Financial Technologies Ltd. | GDPR & SOC 2 Compliance Assessment

A **Governance, Risk, and Compliance (GRC) capstone project** assessing GDPR data handling and SOC 2 readiness for a fictional Irish fintech company. I mapped personal data processing, evaluated security and privacy controls, distinguished confirmed deficiencies from missing evidence, and developed a prioritized remediation roadmap.

## Table of Contents
- [Project Overview](#project-overview)
- [Case Study Background](#case-study-background)
- [Frameworks, Tools & Skills](#frameworks-tools--skills)
- [My Approach & Methodology](#my-approach--methodology)
- [Key Findings & Project Outcomes](#key-findings--project-outcomes)
- [Skills Demonstrated](#skills-demonstrated)
- [Author](#author)

## Project Overview

**My role:** Junior GRC Analyst (capstone case study).

The project evaluated how PayGo collects, uses, stores, shares, and deletes personal information, and whether its documented controls and evidence support a potential SOC 2 examination. The assessment covered **seven processing activities**, **14 GDPR assessment items**, and **eight SOC 2 control areas**.

**Objectives:**
- Build a personal data inventory and describe data flows.
- Evaluate GDPR requirements and identify compliance or evidence gaps.
- Assess proposed SOC 2 **Security, Availability, and Confidentiality** categories.
- Create an evidence register and an integrated, risk-based remediation plan.

## Case Study Background

**PayGo Financial Technologies Ltd.** is a **fictional** digital payments company headquartered in Dublin, Ireland, with approximately **120 employees**. Its environment includes web and mobile applications, a payment platform and database, an identity verification provider, customer support and HR systems, centralized security logging, cloud hosting, and external payment and communications providers.

The seven assessed processing activities were:
- Customer registration
- Identity verification
- Payment processing
- Customer support
- Employee administration
- Security monitoring
- Card payments

The documented retention schedule covered account information (account lifetime plus five years), identity verification records (five years after account closure), transaction records (seven years), support tickets (three years after closure), employee records (six years after employment ends), and security logs (12 months). Retention justifications and end-to-end deletion testing were incomplete.

**Assessment boundary:** This was a scenario-based educational assessment, **not a live audit**. No production configurations, contracts, policies, or logs were independently inspected. The proposed SOC 2 scope was not an agreed examination scope.

## Frameworks, Tools & Skills

- **GDPR:** Articles 5, 6, 12–22, 24–33, and 44–49; supplementary DPO/DPIA screening.
- **SOC 2:** AICPA Trust Services Criteria; proposed Security, Availability, and Confidentiality categories.
- **Assessment methods:** Data inventory, data-flow mapping, compliance gap matrix, control assessment, audit evidence register, third-party risk review, and remediation prioritization.
- **Deliverables:** GDPR data mapping report, GDPR gap assessment, SOC 2 readiness assessment, evidence register, and integrated remediation plan.
- **Companion workbook referenced by the report:** `PayGo_GDPR_SOC2_Capstone_Workbook_Completed.xlsx`.

## My Approach & Methodology

1. **Defined the scope:** Reviewed PayGo's business, systems, providers, and proposed SOC 2 categories.
2. **Mapped personal data:** Documented data categories, data subjects, apparent purposes, recipients, retention periods, and information gaps for seven processing activities.
3. **Assessed GDPR:** Classified each assessment item as a **confirmed gap**, **evidence gap**, or **no gap established**; missing information was not treated as proof of noncompliance.
4. **Assessed SOC 2 controls:** Reviewed access management, MFA, monitoring, incident response, change management, backup and recovery, third-party risk, and confidentiality/disposal.
5. **Reviewed evidence readiness:** Identified missing or unverified evidence for control design, implementation, and operating effectiveness.
6. **Prioritized remediation:** Consolidated findings into **17 actions** and identified actions that address both GDPR and SOC 2.
7. **Evaluated examination readiness:** Distinguished a potential **Type I** design assessment from a **Type II** operating-effectiveness observation period.

## Key Findings & Project Outcomes

### GDPR assessment

| Classification | Count |
|---|---:|
| Confirmed gaps | 5 |
| Evidence gaps | 8 |
| No gap established | 1 |
| **Total** | **14** |

Confirmed gaps concerned incomplete privacy notices, undocumented retention justification and untested deletion, incomplete records of processing, inconsistent provider role documentation, and established security control deficiencies. The absence of full card numbers and verification codes from PayGo's application database was recorded as **no gap established** for that specific minimization item—not verification of full compliance.

### SOC 2 readiness

| Classification | Count |
|---|---:|
| Confirmed weaknesses | 4 |
| Evidence gaps | 4 |
| **Total** | **8** |

**Confirmed weaknesses:**
- **Access management:** Unmapped permissions and missing access reviews for the support system and central logging platform.
- **Incident response:** Procedures had not been tested in the preceding 12 months.
- **Change management:** Approval and testing were not consistently evidenced.
- **Third-party risk management:** Provider records, assessments, and ongoing monitoring were incomplete.

**Evidence gaps:** MFA coverage, timely alert review, backup restoration testing, and confidentiality designation/disposal.

### Remediation roadmap

| Priority | Actions |
|---|---:|
| High | 8 |
| Medium | 7 |
| Low | 2 |
| **Total** | **17** |

**Eight** actions support both GDPR and SOC 2. Key recommendations included completing the record of processing, updating privacy notices, strengthening provider governance, testing deletion, mapping permissions and completing access reviews, testing incident response, and establishing a central audit evidence register.

**Outcome:** Produced a documented, risk-prioritized assessment and recommendations for improving PayGo's privacy governance and SOC 2 readiness. These are **proposed improvements**, not claims that PayGo implemented or passed an audit.

## Skills Demonstrated

- **GDPR data mapping and gap analysis**
- **SOC 2 readiness and security control assessment**
- **Audit evidence identification and documentation**
- **Risk assessment and prioritization**
- **Third-party risk and privacy governance**
- **Remediation planning and professional GRC reporting**

## Author

**Anthony Ogbonna**  
**GRC Analyst | Credit Analyst | Cybersecurity & Compliance**  
Edmonton, Alberta, Canada  
**LinkedIn:** (https://www.linkedin.com/in/anthony-ogbonna-04234342/) 
**Completed:** September 30, 2026


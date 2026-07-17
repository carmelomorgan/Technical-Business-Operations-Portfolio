# Gap Analysis

# Enterprise Cybersecurity Assessment

## Gap Analysis

Document Number: NHS-DOC-104

Project Number: NHS-CSF-001

Framework: NIST Cybersecurity Framework (CSF) 2.0

Assessing Official: Carmelo Morgan

Assessment Status: Completed

-----

## Purpose

This document identifies the gaps discovered during the Enterprise Cybersecurity Assessment of Northwind Health Solutions. Each finding compares the organization's current cybersecurity posture against the expectations of the NIST Cybersecurity Framework (CSF) 2.0.

Each gap includes:

* Current State
* Desired State
* Business Impact
* Risk Statement
* Recommended Remediation
* Priority
* Related NIST CSF Function
* Related Portfolio Project(s)

The purpose of this document is to provide a structured roadmap for improving the organization's cybersecurity maturity through prioritized, risk-based remediation.

-----

## Gap Summary

| Gap ID  | Area                               | Priority | Related CSF Function |
| ------- | ---------------------------------- | -------- | -------------------- |
| GAP-001 | Security Governance                | High     | Govern               |
| GAP-002 | Enterprise Risk Management         | High     | Govern               |
| GAP-003 | Security Policy Lifecycle          | Medium   | Govern               |
| GAP-004 | Third-Party Risk Management        | High     | Govern               |
| GAP-005 | Security Metrics & Reporting       | Medium   | Govern               |
| GAP-006 | Incident Response Testing          | Medium   | Respond              |
| GAP-007 | Vulnerability Remediation Tracking | High     | Detect               |
| GAP-008 | Access Review Process              | Medium   | Protect              |
| GAP-009 | Security Awareness Metrics         | Low      | Protect              |
| GAP-010 | Disaster Recovery Testing          | Medium   | Recover              |

-----

## Detailed Findings

## GAP-001 – Security Governance

### Current State

Northwind Health Solutions maintains foundational cybersecurity governance; however, governance activities are primarily operational and lack a formally documented governance structure. Security responsibilities are defined, but executive reporting, governance meetings, and strategic oversight processes are informal.

### Desired State

Establish a formal cybersecurity governance program with documented governance processes, executive reporting, defined review cycles, and clear accountability.

### Business Impact

Without formal governance, cybersecurity initiatives may become inconsistent, strategic priorities may shift without adequate oversight, and leadership may have limited visibility into enterprise cyber risk.

### Risk Statement

Insufficient governance increases the likelihood of inconsistent decision-making, delayed remediation efforts, and reduced organizational accountability.

### Recommended Remediation

* Establish a Cybersecurity Governance Charter.
* Define governance committees and responsibilities.
* Develop executive cybersecurity reporting.
* Formalize quarterly governance reviews.

Priority: High

Related CSF Function: Govern

Related Portfolio Projects:

* Security Governance Documentation
* Security Metrics Dashboard
* Executive Summary

-----

## GAP-002 – Enterprise Risk Management

### Current State

Risk assessments are performed for selected initiatives, but enterprise-wide cybersecurity risks are not maintained within a centralized, continuously updated risk register.

### Desired State

Maintain an enterprise cybersecurity risk register that documents identified risks, ownership, mitigation activities, residual risk, and review schedules.

### Business Impact

Leadership may lack a comprehensive understanding of organizational cyber risk, resulting in inconsistent prioritization of remediation activities.

### Risk Statement

Decisions regarding cybersecurity investments may not align with the organization's highest-risk areas.

### Recommended Remediation

* Develop an enterprise cybersecurity risk register.
* Define risk ownership.
* Establish quarterly risk reviews.
* Integrate cybersecurity risk into organizational risk management.

Priority: High

Related CSF Function: Govern

Related Portfolio Projects:

* Enterprise Risk Register
* Risk Analysis
* Implementation Roadmap

-----

## GAP-003 – Security Policy Lifecycle

### Current State

Core security policies exist; however, document ownership, review schedules, version control, and approval workflows are not consistently documented.

### Desired State

Implement a formal policy governance process with standardized templates, review schedules, version history, and approval requirements.

### Business Impact

Outdated or inconsistent policies may reduce compliance and create uncertainty regarding organizational security expectations.

### Risk Statement

Employees may follow outdated guidance, increasing the likelihood of inconsistent security practices.

### Recommended Remediation

* Develop a centralized policy library.
* Assign policy owners.
* Establish annual review cycles.
* Implement document version control.

Priority: Medium

Related CSF Function: Govern

Related Portfolio Projects:

* Security Policy Library

-----

## GAP-004 – Third-Party Risk Management

### Current State

Vendor security reviews are performed during procurement but are not supported by a standardized assessment methodology or ongoing monitoring process.

### Desired State

Implement a formal third-party risk management program that evaluates vendor security posture throughout the vendor lifecycle.

### Business Impact

Third-party vendors may introduce cybersecurity risks that remain unidentified after onboarding.

### Risk Statement

Weak vendor oversight increases the potential for supply chain compromise and regulatory exposure.

### Recommended Remediation

* Develop vendor risk assessment procedures.
* Standardize security questionnaires.
* Define vendor risk tiers.
* Perform periodic reassessments.

Priority: High

Related CSF Function: Govern

Related Portfolio Projects:

* Third-Party Risk Assessment *(Future Expansion)*

-----

## GAP-005 – Security Metrics and Reporting

### Current State

Operational security data is collected; however, formal key performance indicators (KPIs) and executive reporting are limited.

### Desired State

Implement a security metrics program that measures the effectiveness of cybersecurity controls and communicates organizational risk to leadership.

### Business Impact

Leadership may have limited visibility into cybersecurity performance and emerging trends.

### Risk Statement

Security decisions may rely on incomplete or inconsistent information.

### Recommended Remediation

* Define cybersecurity KPIs.
* Develop executive dashboards.
* Standardize monthly reporting.
* Track security trends over time.

Priority: Medium

Related CSF Function: Govern

Related Portfolio Projects:

* Security Metrics Dashboard

-----

## GAP-006 – Incident Response Testing

### Current State

An incident response plan exists but has not been validated through recurring tabletop exercises or documented post-incident reviews.

### Desired State

Conduct regular tabletop exercises and capture lessons learned to continuously improve incident response capabilities.

### Business Impact

Response teams may not be adequately prepared to manage complex cybersecurity incidents.

### Risk Statement

Delayed or ineffective incident response may increase operational disruption and recovery costs.

### Recommended Remediation

* Conduct annual tabletop exercises.
* Develop after-action reports.
* Update incident response procedures based on lessons learned.

Priority: Medium

Related CSF Function: Respond

Related Portfolio Projects:

* Incident Response Assessment

-----

## GAP-007 – Vulnerability Remediation Tracking

### Current State

Vulnerability scanning is performed on a regular basis; however, remediation activities are not consistently tracked through a formal Plan of Action and Milestones (POA&M) process.

### Desired State

Implement a centralized remediation tracking process with defined ownership, due dates, risk prioritization, and status reporting.

### Business Impact

Critical vulnerabilities may remain unresolved longer than intended due to inconsistent follow-up.

### Risk Statement

Delayed remediation increases organizational exposure to known vulnerabilities.

### Recommended Remediation

* Establish a POA&M process.
* Assign remediation owners.
* Track remediation timelines.
* Report remediation metrics to leadership.

Priority: High

Related CSF Function: Detect

Related Portfolio Projects:

* Vulnerability Assessment
* POA&M Tracker *(Future Expansion)*

-----

## GAP-008 – Access Review Process

### Current State

Role-based access control is implemented; however, periodic access reviews are not consistently documented across all business units.

### Desired State

Perform recurring user access reviews to verify least privilege and remove unnecessary access.

### Business Impact

Excessive or outdated permissions may increase the risk of unauthorized access.

### Risk Statement

Inappropriate access rights may lead to accidental or intentional misuse of sensitive information.

### Recommended Remediation

* Conduct quarterly access reviews.
* Document review results.
* Validate privileged account assignments.

Priority: Medium

Related CSF Function: Protect

Related Portfolio Projects:

* Identity and Access Review

-----

## GAP-009 – Security Awareness Metrics

### Current State

Annual security awareness training is completed; however, program effectiveness is not measured using defined metrics.

### Desired State

Track user participation, phishing simulation performance, and training completion trends.

### Business Impact

The organization has limited insight into the effectiveness of its awareness program.

### Risk Statement

User-related cybersecurity risks may remain unidentified or unaddressed.

### Recommended Remediation

* Establish awareness KPIs.
* Conduct phishing simulations.
* Report participation and performance metrics.

Priority: Low

Related CSF Function: Protect

Related Portfolio Projects:

* Security Metrics Dashboard

-----

## GAP-010 – Disaster Recovery Testing

### Current State

Disaster recovery procedures are documented, but full recovery exercises are conducted infrequently.

### Desired State

Validate disaster recovery procedures through scheduled testing and documented recovery exercises.

### Business Impact

Recovery objectives may not be achieved during a real disruptive event if procedures have not been routinely validated.

### Risk Statement

Unverified recovery processes increase operational and business continuity risk.

### Recommended Remediation

* Schedule annual disaster recovery exercises.
* Document recovery results.
* Update recovery procedures based on exercise findings.

Priority: Medium

Related CSF Function: Recover

Related Portfolio Projects:

* Business Continuity & Disaster Recovery Assessment *(Future Expansion)*

-----

## Conclusion

The assessment identified ten primary opportunities to strengthen the cybersecurity maturity of Northwind Health Solutions. While the organization demonstrates effective foundational technical controls, the most significant opportunities for improvement are centered on governance, risk management, formal documentation, and measurement.

The recommended remediation activities prioritize improvements that will enhance organizational accountability, support executive decision-making, and strengthen alignment with the NIST Cybersecurity Framework.

The findings documented in this report directly inform the Enterprise Risk Register, Security Policy Library, Implementation Roadmap, and future cybersecurity initiatives within this portfolio.

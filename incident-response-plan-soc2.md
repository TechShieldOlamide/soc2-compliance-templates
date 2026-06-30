# Incident Response Plan (SOC 2 Aligned)

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Lead  
**Approved By:**  
**Review Date:** June 2027  
**Classification:** Internal  

---

## 1. Purpose

This Incident Response Plan defines how [Organisation Name] identifies, responds to, and recovers from security incidents. It is aligned with SOC 2 Trust Service Criteria CC7.1 through CC7.4, which require organisations to monitor for security events, identify incidents, respond appropriately, and execute recovery procedures.

---

## 2. Scope

This plan applies to any event that threatens the confidentiality, integrity, or availability of company or customer data, systems, or infrastructure.

---

## 3. Incident Severity Classification

| Severity | Description | Examples |
|---|---|---|
| Critical | Active breach with customer data exposure or system-wide outage | Confirmed data breach, ransomware, complete service outage |
| High | Significant security event with potential for major impact | Unauthorised access detected, critical vulnerability actively exploited |
| Medium | Security event with limited impact | Suspicious activity detected and contained, minor service disruption |
| Low | Minor security concern requiring monitoring | Failed login attempts, low risk vulnerability identified |

---

## 4. Incident Response Team

| Role | Responsibility |
|---|---|
| Incident Commander | Leads the response, makes key decisions, coordinates communication |
| Technical Lead | Investigates and remediates the technical aspects of the incident |
| Communications Lead | Manages internal and external communication including customer notification |
| Information Security Lead | Oversees the overall response and ensures SOC 2 evidence is captured |

---

## 5. Incident Response Lifecycle

### Phase 1 — Detection and Identification

- Monitor security alerts, logs, and monitoring tools continuously
- Confirm whether an event constitutes a genuine security incident
- Classify the incident by severity
- Assign an Incident Commander
- Log the date and time of detection

### Phase 2 — Containment

- Isolate affected systems to prevent further impact
- Preserve evidence and logs for investigation
- Revoke compromised credentials or access where applicable
- Notify the Incident Response Team

### Phase 3 — Eradication

- Identify and remove the root cause of the incident
- Patch vulnerabilities that were exploited
- Remove any unauthorised access or malicious code
- Verify the threat has been fully eliminated

### Phase 4 — Recovery

- Restore affected systems from clean backups where applicable
- Verify systems are functioning normally before returning to production
- Monitor systems closely following recovery
- Confirm no residual threat remains

### Phase 5 — Notification

- Notify affected customers in accordance with contractual and regulatory obligations
- Notify regulators where required (e.g. data protection authorities for personal data breaches)
- Document all notifications including date, recipient, and content

### Phase 6 — Post-Incident Review

- Conduct a post-incident review within 2 weeks of resolution
- Document the timeline, root cause, response actions, and lessons learned
- Update policies, controls, or this plan based on findings
- Capture evidence of the review for SOC 2 audit purposes

---

## 6. Communication Plan

| Audience | Trigger | Responsible Party | Timeframe |
|---|---|---|---|
| Executive leadership | Critical or High severity incident | Incident Commander | Within 1 hour |
| Affected customers | Confirmed data exposure | Communications Lead | As required by contract, typically within 72 hours |
| Regulators | Personal data breach meeting notification threshold | Information Security Lead | Within 72 hours of becoming aware |
| All staff | Any incident requiring staff action | Communications Lead | As needed |

---

## 7. Evidence Requirements for SOC 2

For every incident, the following evidence must be retained:

- [ ] Incident ticket with timestamp of detection
- [ ] Severity classification record
- [ ] Communication logs with the response team
- [ ] Containment and remediation actions taken
- [ ] Customer or regulator notifications sent
- [ ] Post-incident review report

---

## 8. Testing and Maintenance

- This plan is tested through a tabletop exercise at least annually
- The plan is reviewed and updated following any actual incident or significant organisational change
- All Incident Response Team members are trained on their roles annually

---

## Incident Log

| Incident ID | Date Detected | Severity | Description | Status | Date Resolved |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

## Approval

| Role | Name | Signature | Date |
|---|---|---|---|
| Information Security Lead | | | |
| CEO or Director | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

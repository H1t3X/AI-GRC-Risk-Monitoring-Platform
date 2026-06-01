# Incident Severity Model

## Purpose

This model defines incident severity levels used by the platform.

---

## Severity Classification

| Severity | Description | Business Impact | Response Requirement |
|-----------|------------|-----------------|----------------------|
| Low | Minor security event | Minimal impact | Monitor |
| Medium | Security issue affecting limited functionality | Moderate impact | Investigate |
| High | Significant disruption or compromise | Major impact | Immediate action |
| Critical | Major outage or severe compromise | Severe impact | Emergency response |

---

## Examples

### Low

Examples:
- Single failed login attempt
- Minor traffic increase

---

### Medium

Examples:
- Multiple failed login attempts
- Suspicious login location

---

### High

Examples:
- Brute force attack
- Unauthorized access attempt

---

### Critical

Examples:
- DDoS attack
- Major service outage
- Confirmed data breach

---

## Severity Workflow

```text
Event
↓
Analyze
↓
Assign Severity
↓
Generate Alert
↓
Recommend Action
```

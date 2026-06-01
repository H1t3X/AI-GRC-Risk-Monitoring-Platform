# Dashboard Wireframe

## Purpose

The Dashboard provides a centralized view of security risks, compliance posture, incidents, and recommendations.

The goal is to help stakeholders quickly understand:

- Current security posture
- High-risk areas
- Compliance status
- Required actions

---

# Dashboard Layout

```text
+------------------------------------------------+
|                 AI-GRC Dashboard               |
+------------------------------------------------+

+------------+------------+------------+----------+
| Incidents  | High Risks | Compliance | Critical |
|    24      |     8      |    82%     |    2     |
+------------+------------+------------+----------+

+------------------------------------------------+
|              Risk Overview Chart               |
+------------------------------------------------+

+------------------------------------------------+
|          Compliance Status Overview            |
+------------------------------------------------+

+------------------------------------------------+
|             Security Recommendations           |
+------------------------------------------------+

+------------------------------------------------+
|                Incident Feed                   |
+------------------------------------------------+
```

---

# Section 1 – Security Overview

## Purpose

Provides a high-level summary of platform status.

### Widgets

| Widget | Description |
|----------|-------------|
| Total Incidents | Total detected security events |
| High Risks | Risks with score >= 7 |
| Compliance Score | Percentage of compliant controls |
| Critical Alerts | Critical incidents requiring attention |

---

# Section 2 – Risk Dashboard

## Purpose

Displays current risk posture.

### Visualizations

- Risk Distribution Chart
- Risk Trends
- Top Risks

### Example

| Risk | Score | Level |
|---------|---------|--------|
| DDoS | 9 | High |
| Unauthorized Access | 6 | Medium |
| Missing Monitoring | 4 | Medium |

---

# Section 3 – Compliance Dashboard

## Purpose

Displays compliance status for controls.

### Example

| Control | Status |
|----------|---------|
| MFA | Compliant |
| Logging | Non-Compliant |
| Access Reviews | Compliant |
| Password Policy | Compliant |

---

# Section 4 – Recommendations

## Purpose

Displays prioritized actions.

### Example

1. Enable MFA
2. Implement WAF
3. Improve Monitoring
4. Review User Access

---

# Section 5 – Incident Feed

## Purpose

Displays recent security events.

### Example

[HIGH]
Possible DDoS Detected

[MEDIUM]
Multiple Failed Login Attempts

[LOW]
Unusual Traffic Pattern

---

# Dashboard Workflow

```text
Events
↓
Detection Engine
↓
Risk Engine
↓
Compliance Engine
↓
Recommendation Engine
↓
Dashboard
```

---

# Success Criteria

The dashboard should allow users to:

- View risk posture instantly
- Understand compliance status
- Identify high-priority issues
- Review recommended actions
- Monitor incidents

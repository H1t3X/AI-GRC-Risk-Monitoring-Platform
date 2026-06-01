# Control Catalog

## Purpose

This document defines the security controls used by the AI-GRC Risk Monitoring Platform to mitigate identified risks and support compliance requirements.

---

## Control Categories

### Preventive Controls
Controls designed to prevent security incidents.

### Detective Controls
Controls designed to detect security incidents.

### Corrective Controls
Controls designed to reduce impact after incidents occur.

---

## Control Register

| Control ID | Control Name | Control Type | Description | ISO 27001 Mapping |
|------------|-------------|---------------|-------------|------------------|
| C001 | Rate Limiting | Preventive | Restricts excessive requests to prevent abuse | A.8.20 |
| C002 | Web Application Firewall (WAF) | Preventive | Filters malicious traffic | A.8.20 |
| C003 | Multi-Factor Authentication (MFA) | Preventive | Requires additional authentication factor | A.5.17 |
| C004 | Password Policy | Preventive | Enforces strong credential requirements | A.5.17 |
| C005 | Security Logging | Detective | Records security-related events | A.8.15 |
| C006 | Security Monitoring | Detective | Monitors activity for suspicious behavior | A.8.16 |
| C007 | Access Reviews | Detective | Reviews user permissions periodically | A.5.18 |
| C008 | Incident Response Process | Corrective | Defines response actions during incidents | A.5.24 |

---

## Control Objectives

The objective of these controls is to:

- Reduce security risk
- Improve visibility
- Support compliance requirements
- Improve incident response capability

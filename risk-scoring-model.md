# Risk Scoring Model

## Purpose

Calculates risk based on impact and likelihood.

---

## Formula

```text
Risk Score = Impact × Likelihood
```

---

## Risk Matrix

| Impact | Likelihood | Score |
|----------|------------|---------|
| 1 | 1 | 1 |
| 1 | 2 | 2 |
| 1 | 3 | 3 |
| 2 | 1 | 2 |
| 2 | 2 | 4 |
| 2 | 3 | 6 |
| 3 | 1 | 3 |
| 3 | 2 | 6 |
| 3 | 3 | 9 |

---

## Risk Classification

| Score | Level |
|---------|--------|
| 1-3 | Low |
| 4-6 | Medium |
| 7-9 | High |

---

## Example

Threat:
DDoS

Impact:
3

Likelihood:
3

Risk Score:
9

Risk Level:
High

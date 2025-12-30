# Cloud Risk Assessment – AWS Environment (Sample Project)

**Objective:** Assess cybersecurity risks for a web application hosted on AWS.

## 1. Scope
AWS environment hosting a customer-facing web application and databases.

## 2. Assets
| Asset           | Description            | Data Type         |
|-----------------|------------------------|-------------------|
| Web Application | Customer portal        | Personal data     |
| Database        | User data storage      | PII               |
| IAM             | User access management | Credentials       |

## 3. Threats & Vulnerabilities
| Threat              | Vulnerability               |
|---------------------|-----------------------------|
| Unauthorized access | Weak IAM policies           |
| Data leakage        | Misconfigured storage       |
| Service disruption  | Lack of monitoring          |

## 4. Shared Responsibility Model
**Cloud Provider (AWS):**
- Physical security
- Infrastructure availability

**Customer:**
- IAM configuration
- Data protection
- Logging and monitoring

## 5. Risk Assessment
| Risk               | Likelihood | Impact | Risk Level |
|--------------------|------------|--------|------------|
| Data leakage       | Medium     | High   | High       |
| Unauthorized access| Medium     | High   | High       |
| Service outage     | Low        | Medium | Medium     |

## 6. Risk Treatment
| Risk               | Mitigation                    |
|--------------------|-------------------------------|
| Data leakage       | Encryption, access control    |
| Unauthorized access| MFA, least privilege          |
| Service outage     | Monitoring, backups           |

## 7. Residual Risk
Residual risk is Medium after mitigation and considered acceptable.

## 8. Executive Summary
Primary cloud risks relate to IAM misconfiguration and data exposure.  
Recommended controls significantly reduce overall risk.

---

**Skills Demonstrated:** Cloud Risk Assessment, GRC, ISO 27001, Shared Responsibility Model, Risk Documentation

**Note:** This is a **sample project with dummy data**.

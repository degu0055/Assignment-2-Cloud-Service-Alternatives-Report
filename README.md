<!-- 

Github:
https://github.com/degu0055/Assignment-2-Cloud-Service-Alternatives-Report

 -->

# CST8919 – Cloud Service Alternatives Report


## 1. Azure Active Directory (SSO, IAM)

| Cloud Provider | Service Name                              |
|----------------|-------------------------------------------|
| Azure          | Azure Active Directory (Entra ID)         |
| AWS            | AWS Identity and Access Management (IAM) + AWS SSO |
| GCP            | Google Cloud Identity & Access Management |

**Overview:**  
- Azure AD: Identity and access control with SSO and MFA.  
- AWS IAM + SSO: Controls users, roles, and app access.  
- GCP IAM + Identity: Manages user permissions and sign-in for cloud apps.

**Core Features:**  
- User management  
- Roles and permissions  
- Single Sign-On  
- Multi-Factor Authentication  
- Conditional access  

**Security & Compliance:**  
- ISO 27001, SOC, GDPR  
- Encryption and MFA supported  

**Pricing Model:**  
- Azure AD: Free and paid plans (P1, P2)  
- AWS IAM: Free, SSO billed per user/month  
- GCP IAM: Free, Cloud Identity has free/paid tiers  

**Integration for DevSecOps:**  
- Works with CI/CD pipelines for secure access  

---

## 2. Azure Monitor & Log Analytics

| Cloud Provider | Service Name               |
|----------------|----------------------------|
| Azure          | Azure Monitor + Log Analytics |
| AWS            | Amazon CloudWatch           |
| GCP            | Google Cloud Operations Suite (Stackdriver) |

**Overview:**  
- Azure Monitor: Collects and analyzes logs and metrics.  
- CloudWatch: Monitors AWS resources and logs.  
- Cloud Operations: Logging and monitoring for GCP.

**Core Features:**  
- Metrics and logs  
- Alerts and dashboards  
- Querying logs  
- API integration  

**Security & Compliance:**  
- Data encryption  
- Meets industry standards  

**Pricing Model:**  
- Pay for data ingestion and storage  

**Integration for DevSecOps:**  
- Can trigger alerts for automation  

---

## 3. Azure Policy

| Cloud Provider | Service Name               |
|----------------|----------------------------|
| Azure          | Azure Policy               |
| AWS            | AWS Service Control Policies |
| GCP            | Google Organization Policy Service |

**Overview:**  
- Azure Policy: Enforces rules on resources.  
- AWS SCP: Restricts actions in AWS accounts.  
- GCP Org Policy: Controls allowed settings in projects.

**Core Features:**  
- Policy assignment  
- Compliance checks  
- Pre-made templates  

**Security & Compliance:**  
- Helps meet CIS, NIST, and other frameworks  

**Pricing Model:**  
- No extra cost, except logging  

**Integration for DevSecOps:**  
- Enforces rules during deployments  

---

## 4. Microsoft Defender for Cloud

| Cloud Provider | Service Name                 |
|----------------|------------------------------|
| Azure          | Microsoft Defender for Cloud |
| AWS            | AWS Security Hub              |
| GCP            | Security Command Center       |

**Overview:**  
- Defender: Monitors security and gives recommendations.  
- Security Hub: Collects AWS security alerts.  
- SCC: Detects risks in GCP.

**Core Features:**  
- Threat detection  
- Compliance checks  
- Security advice  

**Security & Compliance:**  
- PCI DSS, HIPAA, ISO  

**Pricing Model:**  
- Free tier, paid for advanced protection  

**Integration for DevSecOps:**  
- Sends alerts to monitoring and SIEM tools  

---

## 5. Azure Sentinel (SIEM/SOAR)

| Cloud Provider | Service Name           |
|----------------|------------------------|
| Azure          | Microsoft Sentinel     |
| AWS            | Amazon Security Lake / Partner SIEM |
| GCP            | Chronicle Security Operations |

**Overview:**  
- Sentinel: Cloud SIEM/SOAR for threat response.  
- Security Lake: Stores security data for analysis.  
- Chronicle: Threat detection and response.

**Core Features:**  
- Log collection  
- Threat detection  
- Automated responses  

**Security & Compliance:**  
- Meets major certifications  
- Encryption for data  

**Pricing Model:**  
- Pay per GB of data ingested  

**Integration for DevSecOps:**  
- Works with automation and incident response tools  

---

## Quick Comparison Table

| Azure Service                  | AWS Equivalent                | GCP Equivalent                       |
|--------------------------------|--------------------------------|---------------------------------------|
| Azure Active Directory         | AWS IAM + SSO                  | Cloud IAM + Identity                  |
| Azure Monitor + Log Analytics  | Amazon CloudWatch              | Cloud Operations Suite                |
| Azure Policy                   | AWS Service Control Policies   | Organization Policy Service           |
| Microsoft Defender for Cloud   | AWS Security Hub               | Security Command Center                |
| Microsoft Sentinel              | Amazon Security Lake / SIEM    | Chronicle Security Operations         |

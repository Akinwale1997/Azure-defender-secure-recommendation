# Enable Microsoft Defender for Cloud & Implement Secure Recommendations

This project showcases how I enabled Microsoft Defender for Cloud on an Azure subscription and reviewed secure configuration recommendations to harden the environment — especially focusing on identity and Key Vault security.

---

## 🔐 Project Objective

Improve the security posture of Azure resources using Microsoft Defender for Cloud by:

- Enabling Microsoft Defender for Cloud on the subscription
- Reviewing security recommendations
- Identifying overprovisioned roles and improving role assignments

---

## 🧰 Tools & Services Used

- Azure Portal  
- Microsoft Defender for Cloud  
- Azure IAM (Access Control)  
- Azure Key Vault  
- Azure Recommendations Center

---

## 📝 Steps Taken

### 1. Defender for Cloud Enabled
- Navigated to Microsoft Defender for Cloud.
- Confirmed Defender was turned On for Key Vault and other services (Plan 2 shown).

📸 *Screenshot: 01-defender-dashboard-opened.png*

---

### 2. Reviewed Security Recommendations
- Opened the Recommendations tab.
- Identified security warnings including:
  - Overprovisioned identities
  - Missing private endpoints
  - Purge protection and firewall disabled on Key Vault

📸 *Screenshot: 02-overprovisioned-identities-role.png*

---

### 3. Identity Access Cleanup (Overprovisioned Roles)
- Validated IAM assignments for unnecessary owner or contributor roles.
- Ensured only required roles remained — principle of least privilege.

---

## 🔐 Security Concepts Applied

- Principle of Least Privilege (PoLP)  
- Identity hardening  
- Role-based Access Control (RBAC)  
- Key Vault protection best practices

---

## 🧠 Lessons Learned

- Azure Defender for Cloud provides excellent baseline security guidance.
- RBAC misconfigurations are common and dangerous — auditing is essential.
- Every resource type (e.g. Key Vault) has specific hardening recommendations.

---

## 📁 Project Screenshots

- 01-defender-dashboard-opened.png – Initial Defender overview
- 02-overprovisioned-identities-role.png – Recommendation view for excessive permissions

---

## 📌 Tags

Azure Security Microsoft Defender Cloud Hardening IAM RBAC Key Vault Security Cloud Security Projects

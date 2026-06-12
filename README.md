# Azure Free Tier Account Setup

## Overview
Hands-on setup of Microsoft Azure environment 
as part of Cloud Computing Bootcamp. This guide 
documents the complete process of creating and 
configuring an Azure Free Tier account.

---

## 1. Account Creation — Step by Step

1. Visited https://azure.microsoft.com/free
2. Clicked **"Start Free"**
3. Signed in with Microsoft account 
   (tee.ekundayo23@gmail.com)
4. **Email verification** — confirmed email address
5. **Phone verification** — entered Nigerian number,
   received and entered SMS code
6. **Identity verification** — entered debit card 
   details (no charge made, temporary $1 hold 
   released automatically)
7. Agreed to terms and conditions
8. Account created successfully
9. Redirected to Azure Portal dashboard

---

## 2. Azure Free Tier Benefits

| Benefit | Details |
|---|---|
| **Credit** | $200 free credit |
| **Duration** | Valid for 30 days |
| **Free services** | 12 months of popular services |
| **Always free** | 55+ services always free |
| **B1s VM** | 750 hours/month free |
| **Storage** | 5GB Blob storage free |
| **Databases** | 250GB SQL Database free |

---

## 3. Portal Navigation

After login at portal.azure.com:

- **Top search bar** — search any Azure service
- **Left icon bar** — quick access to all services
- **Dashboard** — customizable home screen
- **Notifications bell** — alerts and activity
- **Settings gear** — account preferences
- **Subscriptions** — billing and access control

Key services located via search:
- Virtual Machines
- Storage Accounts
- Resource Groups
- Cost Management
- Azure Active Directory

---

## 4. Dashboard Customization

- Navigated to **My Dashboard**
- Dashboard shows all resources and activity
- Tiles available: Resource groups, 
  Subscriptions, Service Health, Marketplace

---

## 5. Governance Setup

### Subscription
- **Name:** Azure subscription 1
- **ID:** f3298c28-944d-4b8c-9292-30b1609c4502
- **Role:** Owner
- **Status:** Active

### Resource Group Created
- **Name:** Cloud-bootcamp
- **Location:** South Africa North
- **Subscription:** Azure subscription 1
- **Deployments:** Storage Account

---

## 6. Region Selection

- **Region chosen:** South Africa North
- **Reason:** Closest Azure region to 
  Nigeria/West Africa, providing lowest 
  latency and best performance for users 
  in the region
- **Availability Zones:** Physically separate 
  data centers within the region for redundancy

---

## 7. Resource Deployed

### Storage Account
- **Name:** cloudbootcampstorage03
- **Type:** StorageV2 (general purpose v2)
- **Performance:** Standard
- **Replication:** LRS (Locally Redundant Storage)
- **Location:** South Africa North
- **Provisioning state:** Succeeded
- **Created:** 6/12/2026

### Why Storage Account (IaaS)?
A Storage Account is an IaaS resource where:
- **Microsoft manages:** Physical hardware, 
  network, data center security
- **I manage:** Access control, data stored,
  configuration, encryption settings

---

## 8. Identity & Access Management (IAM)

### RBAC Role Assignment
- **User:** Titilayo Ekundayo
- **Role:** Owner
- **Scope:** Subscription (Inherited)
- **Deny assignments:** 0

### Azure RBAC Roles Explained
| Role | Permissions |
|---|---|
| **Owner** | Full access + manage access |
| **Contributor** | Create & manage resources |
| **Reader** | View only, no changes |

### Security Best Practices
- Enable **Multi-Factor Authentication (MFA)**
  via Microsoft Entra ID → Security → MFA
- Use **strong passwords** (12+ characters,
  mix of letters, numbers, symbols)
- **Never share** subscription credentials
- Review role assignments regularly
- Use **least privilege** — give minimum 
  access needed

---

## 9. Cost Management

### Budget Configuration
- Navigated to **Cost Management → Budgets**
- Scope: Titilayo Ekundayo (Billing account)
- **Recommendation:** Set budget at $10/month
  with alert at **75% threshold** to stay 
  within free tier limits

### Cost Management Tools Available
- **Cost Analysis** — view spending breakdown
- **Budgets** — set spending limits
- **Cost alerts** — get notified of overspending
- **Alert rules** — custom alert conditions

### Free Tier Protection Tips
- Always select **free tier eligible** resources
- Check **"Free services"** page before deploying
- Set budget alerts at 75% of limit
- Review Cost Analysis weekly

---

## 10. Shared Responsibility Model

| Responsibility | Microsoft | Me |
|---|---|---|
| Physical data center | ✅ | ❌ |
| Network infrastructure | ✅ | ❌ |
| Hardware maintenance | ✅ | ❌ |
| Platform availability | ✅ | ❌ |
| Operating system | Shared | Shared |
| Access control (IAM) | ❌ | ✅ |
| Data in storage account | ❌ | ✅ |
| Configuration settings | ❌ | ✅ |
| Encryption management | ❌ | ✅ |

---

## 11. Screenshots Included

1. Subscription confirmation (Active status)
2. Resource Group overview (Cloud-bootcamp)
3. IAM/RBAC role assignments
4. Storage Account deployment (Succeeded)
5. Cost Management Budgets page

---

## 12. Troubleshooting & Tips

| Issue | Solution |
|---|---|
| B1s VM size unavailable | Try different region or use Storage Account |
| Subscription not showing | Click "Switch directories" |
| Portal loading slow | Clear browser cache |
| Credit card declined | Use non-prepaid debit card |
| Can't find a service | Use top search bar |

---

## Completion Checklist

- [x] Azure account created
- [x] Email & phone verified
- [x] Portal explored
- [x] Subscription confirmed
- [x] Resource Group created
- [x] IAM/RBAC reviewed
- [x] Region selected & justified
- [x] Storage Account deployed
- [x] Cost Management accessed
- [x] README documented

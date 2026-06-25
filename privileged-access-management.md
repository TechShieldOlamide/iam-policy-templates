# Privileged Access Management Policy

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  
**Review Date:** June 2027  
**Classification:** Internal  

---

## 1. Purpose

This policy defines the requirements for managing privileged access across organisation systems. Privileged accounts have elevated permissions and represent a significant security risk if compromised or misused.

---

## 2. Scope

This policy applies to all privileged accounts including system administrators, database administrators, network administrators, cloud administrators, and any account with elevated permissions.

---

## 3. Definition of Privileged Access

Privileged access includes but is not limited to:

- System administrator accounts
- Database administrator accounts
- Cloud platform admin accounts
- Network device admin accounts
- Application admin accounts
- Service accounts
- Emergency or break glass accounts

---

## 4. Privileged Account Management

**4.1 Account Creation**
- Privileged accounts are created only upon written approval from the Information Security Lead and IT Manager
- Every privileged user must have a separate standard account for day to day work
- Privileged accounts must not be used for email, browsing, or non-administrative tasks

**4.2 Naming Convention**
- Privileged accounts must be clearly identified
- Recommended format: adm-[username] for admin accounts

**4.3 Shared Accounts**
- Shared privileged accounts are not permitted
- Each administrator must have their own individual privileged account

---

## 5. Authentication Requirements

- MFA is mandatory on all privileged accounts
- Privileged account passwords must meet the organisation password policy
- Passwords must be changed every 90 days
- Privileged account credentials must be stored in an approved password manager
- Credentials must never be shared via email, chat, or any unencrypted channel

---

## 6. Usage Controls

- Privileged access must only be used for authorised administrative tasks
- All privileged account activity must be logged
- Privileged sessions must be terminated immediately after the task is complete
- Remote privileged access requires VPN and MFA
- Privileged access from personal devices is not permitted

---

## 7. Monitoring and Logging

- All privileged account activity is logged centrally
- Logs are reviewed monthly by the Information Security Lead
- Alerts are configured for unusual privileged account activity
- Log retention period is a minimum of 12 months

---

## 8. Privileged Access Reviews

- Privileged accounts are reviewed monthly
- Review confirms accounts are still required and access is appropriate
- Unused privileged accounts are disabled within 30 days
- Review findings are documented and signed off

---

## 9. Emergency Access

- Break glass accounts are maintained for emergency access scenarios
- Break glass credentials are stored securely and accessed only in genuine emergencies
- Every use of a break glass account must be logged and reviewed
- Break glass passwords are rotated after every use

---

## 10. Service Accounts

- Service accounts are granted only the permissions required for the service to function
- Service account passwords are rotated at least annually
- Service accounts are reviewed quarterly
- Service accounts must not be used for interactive logins

---

## Privileged Account Register

| Account Name | System | Account Owner | Date Created | Last Review | Status |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |

---

## Approval

| Role | Name | Signature | Date |
|---|---|---|---|
| Information Security Lead | | | |
| IT Manager | | | |
| CEO or Director | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

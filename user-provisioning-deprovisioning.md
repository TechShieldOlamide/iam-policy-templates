# User Provisioning and Deprovisioning Policy

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  
**Review Date:** June 2027  
**Classification:** Internal  

---

## 1. Purpose

This policy defines the process for creating, modifying, and removing user access across all organisation systems. It ensures access is granted promptly to new starters, updated when roles change, and removed immediately when staff leave.

---

## 2. Scope

This policy applies to all employees, contractors, consultants, and third parties requiring access to organisation systems.

---

## 3. User Provisioning — New Starters

### 3.1 Process

1. HR notifies IT and security team of new starter at least 3 business days before start date
2. Line manager submits access request detailing systems required
3. IT team creates user account with unique credentials
4. Access is provisioned based on role and least privilege principle
5. User is provided with credentials securely on first day
6. User completes security awareness training before accessing sensitive systems
7. Access is documented in the user access register

### 3.2 Checklist

- [ ] User account created with unique username
- [ ] Temporary password set and marked for change on first login
- [ ] MFA enrolled before first login
- [ ] Role based access applied
- [ ] Access register updated
- [ ] Welcome email sent with security guidelines
- [ ] Security awareness training assigned

---

## 4. Access Modification — Role Changes

### 4.1 Process

1. HR or line manager notifies IT and security team of role change
2. Current access is reviewed against new role requirements
3. Unnecessary access is removed within 5 business days
4. New access required for the role is provisioned
5. Access register is updated

### 4.2 Checklist

- [ ] Previous role access reviewed
- [ ] Unnecessary access removed
- [ ] New role access provisioned
- [ ] Access register updated
- [ ] Manager sign-off obtained

---

## 5. User Deprovisioning — Leavers

### 5.1 Process

1. HR notifies IT and security team immediately upon confirmed resignation or termination
2. All accounts are suspended within 1 hour of notification
3. Active sessions are terminated immediately
4. All access is removed within 24 hours
5. Company devices are collected on last day
6. Access register is updated
7. Leaver checklist is completed and signed off

### 5.2 Checklist

- [ ] All accounts suspended immediately
- [ ] Active sessions terminated
- [ ] Email account disabled and forwarding configured
- [ ] VPN and remote access revoked
- [ ] API keys and tokens revoked
- [ ] Third party system access removed
- [ ] Company devices collected
- [ ] Access register updated
- [ ] IT equipment register updated
- [ ] HR sign-off obtained

---

## 6. Contractor and Third Party Offboarding

- Contractor access is removed on the last day of the engagement
- All accounts, tokens, and credentials are revoked immediately
- Any data shared with the contractor is reviewed and recovered where possible
- Access removal is documented and signed off

---

## 7. Access Register

The access register must be maintained and updated for every provisioning and deprovisioning event. It must include:

| Field | Description |
|---|---|
| User Name | Full name of the user |
| Role | Job title or function |
| Systems Access | List of systems and access levels |
| Access Granted Date | Date access was provisioned |
| Last Review Date | Date access was last reviewed |
| Access Removed Date | Date access was removed |
| Removed By | Name of person who removed access |

---

## Approval

| Role | Name | Signature | Date |
|---|---|---|---|
| Information Security Lead | | | |
| HR Manager | | | |
| IT Manager | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*

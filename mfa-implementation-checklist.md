# MFA Implementation Checklist

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Information Security Team  
**Review Date:** June 2027  
**Classification:** Internal  

---

## 1. Purpose

This checklist guides organisations through the planning and implementation of multi-factor authentication across their systems and applications.

---

## 2. Pre-Implementation Planning

- [ ] Identify all systems and applications requiring MFA
- [ ] Identify all user groups requiring MFA
- [ ] Select approved MFA methods (authenticator app, hardware token, SMS)
- [ ] Select MFA platform or tool
- [ ] Define rollout timeline and phases
- [ ] Identify exceptions process for users who cannot enrol
- [ ] Communicate rollout plan to all staff
- [ ] Assign implementation owner

---

## 3. System Readiness

- [ ] Confirm all target systems support MFA
- [ ] Test MFA integration in a non-production environment
- [ ] Configure MFA policies in identity provider
- [ ] Configure session timeout and re-authentication requirements
- [ ] Configure backup authentication methods
- [ ] Test account recovery process with MFA enabled
- [ ] Document technical configuration

---

## 4. User Enrolment

- [ ] Send enrolment instructions to all users
- [ ] Set enrolment deadline
- [ ] Provide step by step enrolment guide for each platform
- [ ] Set up helpdesk support for enrolment issues
- [ ] Track enrolment progress by department
- [ ] Follow up with users who have not enrolled by deadline
- [ ] Confirm 100% enrolment before enforcing MFA

---

## 5. Rollout by Priority

### Phase 1 — High Priority (Week 1-2)
- [ ] All privileged and admin accounts
- [ ] All accounts with access to financial data
- [ ] All accounts with access to personal data
- [ ] All remote access accounts

### Phase 2 — Standard Users (Week 3-4)
- [ ] All remaining internal user accounts
- [ ] All contractor and third party accounts

### Phase 3 — External Facing (Week 5-6)
- [ ] Customer facing applications
- [ ] Partner portals
- [ ] API authentication where applicable

---

## 6. Post-Implementation

- [ ] Confirm MFA is enforced and cannot be bypassed
- [ ] Monitor MFA failure and bypass attempts
- [ ] Review MFA logs weekly for first month
- [ ] Communicate completion to leadership
- [ ] Update access control policy to reflect MFA requirement
- [ ] Schedule quarterly MFA compliance review
- [ ] Document lessons learned

---

## 7. Ongoing Management

- [ ] Review MFA enrolment monthly
- [ ] Audit MFA bypass exceptions quarterly
- [ ] Review and rotate hardware tokens annually
- [ ] Test account recovery process every 6 months
- [ ] Update this checklist after any significant changes

---

## MFA Enrolment Tracker

| Department | Total Users | Enrolled | Pending | Exceptions | Completion % |
|---|---|---|---|---|---|
| | | | | | |
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

# Access Control Audit Program

## 1. Objective
Assess whether logical access to information systems is authorized, appropriate, and monitored.

## 2. Risks
- Unauthorized access to sensitive systems.
- Privilege escalation or abuse.
- Orphaned accounts after staff exit.
- Weak authentication exposing systems.

## 3. Controls to Test
- User provisioning & deprovisioning process.
- MFA enforcement.
- Password policy configuration.
- Privileged access management.
- Access review frequency.

## 4. Detailed Test Procedures
### 4.1 User Provisioning
1. Obtain user access listing from Active Directory.
2. Verify onboarding process:  
   - Approved access request form  
   - Ticket or workflow evidence  
3. Sample 10 new users and verify correct role assignments.

### 4.2 User Deprovisioning
1. Review terminated users list from HR.
2. Confirm their accounts are disabled within SLA.
3. Validate no active access exists in key systems.

### 4.3 Privileged Account Review
1. Extract domain admin, server admin, sysadmin groups.
2. Verify membership appropriateness.
3. Confirm periodic reviews by ICT management.

### 4.4 Password Policy Review
- Length, complexity, expiry, lockout.
- Compare with policy requirements.

### 4.5 MFA Enforcement
- Review MFA enrollment logs.
- Validate enforcement across all users.

## 5. Evidence Required
- AD exports
- Policy documents
- Access request forms
- HR exit list
- MFA configuration exports

## 6. Expected Results
- Access granted only with approval.
- Orphaned accounts do not exist.
- Admin rights restricted.
- MFA enforced.

## 7. Conclusion
To be completed after testing.

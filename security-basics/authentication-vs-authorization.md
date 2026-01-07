# Authentication vs Authorization

## Introduction
Authentication and authorization are core security concepts
used to control access to systems, applications, and data.
Understanding the difference is very important for SOC analysts.

---

## Authentication

### What is Authentication?
Authentication is the process of verifying **who the user is**.

### Common Authentication Methods
- Username and password
- One-Time Password (OTP)
- Biometric authentication
- Multi-Factor Authentication (MFA)

### Simple Example
Logging into an email account using a username and password.

### SOC Perspective
SOC analysts monitor authentication logs to detect:
- Failed login attempts
- Brute-force attacks
- Suspicious login behavior

---

## Authorization

### What is Authorization?
Authorization is the process of verifying **what the user is allowed to do**
after successful authentication.

### Examples of Authorization
- Read-only access to files
- Admin or user-level permissions
- Access control based on roles

### Simple Example
A normal user cannot access admin settings even after logging in.

### SOC Perspective
SOC analysts check authorization issues to detect:
- Privilege escalation attempts
- Misconfigured access permissions
- Unauthorized access to sensitive data

---

## Authentication vs Authorization (Quick Comparison)

| Authentication | Authorization |
|----------------|---------------|
| Verifies identity | Verifies permissions |
| Happens first | Happens after authentication |
| Example: Login | Example: Access level |

---

## Simple Practical Observation (Linux)
Command:

## whoami

Observation:
Shows the currently logged-in user.

SOC Use:
Helps verify user identity during investigations.

---

## Why This Matters for SOC Analysts
Authentication and authorization controls help SOC teams to:
- Detect unauthorized access attempts
- Prevent privilege misuse
- Investigate security incidents effectively

## Status
This document covers foundational access control concepts
for entry-level SOC analysts.

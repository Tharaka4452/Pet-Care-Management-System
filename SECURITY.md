# 🔒 Security Policy

We take the security of the Pet Care Management System seriously. If you believe you have found a security vulnerability, please follow the guidelines below.

## 📣 Reporting a Vulnerability

- Email: security@yourdomain.com (or open a private Security issue)
- Alternatively, open a GitHub issue using the "Security" issue template (do not include sensitive details publicly).

Please include:
- A detailed description of the vulnerability
- Steps to reproduce
- Potential impact
- Affected components
- Any possible mitigations

## ⏱ Response Timeline

- Acknowledgement: within 72 hours
- Initial assessment: within 7 days
- Fix development: prioritized based on severity
- Release & disclosure: coordinated responsible disclosure

## ✅ Responsible Disclosure

- Do not publicly disclose the issue before we release a fix
- Do not exploit the vulnerability beyond what is necessary to prove it exists
- Do not access, modify, or delete data

## 🔐 Scope

- Backend API (authentication, authorization, data access)
- Frontend/Professional portals (XSS, CSRF, data exposure)
- File upload and image handling
- Payment integrations (Stripe)

## 🛡️ Best Practices We Follow

- No secrets in the repository
- Principle of least privilege for roles
- Input validation and output encoding
- Dependency updates and vulnerability scans

Thank you for helping us keep our users and their pets safe. 🐾

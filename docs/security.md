---
layout: default
title: Security & Vulnerability Disclosure
---

# Security & Vulnerability Disclosure

We take security seriously and welcome reports from researchers and the community.

## Practices
- **Data in transit / at rest:** TLS; provider-managed encryption at rest (Firebase).  
- **Access control:** Principle of least privilege for service accounts and Firestore rules.  
- **Secrets:** Stored outside source control; rotated when appropriate.  
- **Monitoring & logging:** Server logs for error and security-relevant events.  
- **Dependency hygiene:** Regular updates and automated checks.

## Report a vulnerability
Please email **simpleware@mail.com** with a description, reproduction steps, and impact.  

**Please do not** publicly disclose before we confirm a fix or 90 days pass (whichever is sooner), unless mutually agreed.

## Out of scope
- Social engineering against staff/users  
- Physical attacks  
- Issues requiring rooted/jailbroken devices

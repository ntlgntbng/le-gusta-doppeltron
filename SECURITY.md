# **Security Policy**

We take the security of this project, its dependencies, and our users' privacy seriously. This document outlines our policy regarding supported versions, vulnerability reporting, and disclosure protocols.

## **Supported Versions**

We actively maintain and issue security patches for the following versions:

| Version | Supported | Notes |
| :---- | :---- | :---- |
| Main Branch | Yes | Latest production release |
| \< 1.0.0 | No | Legacy preview releases; please upgrade to main |

## **Reporting a Vulnerability**

**Please do not report security vulnerabilities through public GitHub Issues, Pull Requests, or public discussions.**

If you discover a potential security flaw, audio buffer exploit, or data leak within this application, report it privately using one of the following methods:

1. **GitHub Private Vulnerability Reporting (Preferred):**  
   * Navigate to the repository's **Security** tab on GitHub.  
   * Click **Report a vulnerability** to open a private advisory draft.  
2. **Direct Contact:**  
   * Email the maintainer directly at **\[INSERT YOUR SECURITY EMAIL\]**.  
   * Encrypt sensitive details if possible and include \[SECURITY\] in the subject line.

## **What to Include in Your Report**

To help us triage and resolve the issue quickly, please provide:

* **Description:** A detailed explanation of the vulnerability and its potential impact.  
* **Steps to Reproduce:** Clear, step-by-step instructions or a Minimal Working Example (MWE).  
* **Impact Scope:** Specific browsers, operating systems, or Web Audio API contexts affected.  
* **Suggested Fix:** (Optional) Code snippets or patches if you have identified a solution.

## **Response & Remediation Timelines**

When a security vulnerability is reported, we commit to the following response timeline:

* **Acknowledgment:** Within **48 hours** of receiving your report.  
* **Initial Assessment:** Within **5 business days** to confirm the issue and determine severity.  
* **Patch Deployment:** Within **14 business days** for high/critical vulnerabilities.  
* **Public Disclosure:** Coordinated after a patch has been merged to the main branch.

## **Public Disclosure Policy**

We follow a policy of **Coordinated Vulnerability Disclosure**. We ask that you give us reasonable time to investigate and fix the reported issue before sharing details publicly or with third parties. Once resolved, credit will be given to the reporter in the release notes (unless anonymity is requested).
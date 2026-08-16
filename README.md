Black Box Security — Offensive Security Portfolio

A public portfolio documenting authorized security testing, vulnerability research, lab assessments, and professional reporting.

> **Ethics & Scope:** All testing documented in this repository is performed against systems I own, intentionally vulnerable labs, or targets for which I have explicit authorization. Sensitive information, credentials, API keys, personal data, and non-public target details are removed before publication.

Focus Areas

• Web application penetration testing
• API security testing
• Authentication and session security
• Authorization testing (IDOR / BOLA / access control)
• Input validation and injection testing
• Business logic testing
• Reconnaissance and attack-surface mapping
• Vulnerability validation and professional reporting

Portfolio

|Case Study                                                                                       |Type                     |Status     |
|-------------------------------------------------------------------------------------------------|-------------------------|-----------|
|[001 — Black-Box Web Application Assessment](case-studies/001-black-box-web-assessment/README.md)|Authorized Web Assessment|In Progress|

Sample Reports

• HackerOne-style vulnerability report template
• Professional finding template

Methodology

My testing process emphasizes reproducibility, minimal impact, clear evidence, and actionable remediation.

1. Confirm scope and authorization.
2. Map the exposed attack surface.
3. Identify authentication, authorization, input, and business-logic boundaries.
4. Test hypotheses with the least destructive method available.
5. Capture sanitized evidence.
6. Assess realistic security impact.
7. Document exact reproduction steps.
8. Recommend remediation and verify fixes when possible.

Tools

Examples of tools used during authorized assessments:

• Burp Suite
• OWASP ZAP
• Nmap
• curl / HTTP clients
• Browser developer tools
• Python
• Git
• Linux security tooling

Responsible Disclosure

I do not publish undisclosed vulnerabilities, customer information, secrets, access tokens, private source code, or details that would violate a program’s disclosure policy.

Contact

• HackerOne: ADD_YOUR_HACKERONE_PROFILE
• GitHub: ADD_YOUR_GITHUB_PROFILE
• Email: ADD_PUBLIC_SECURITY_EMAIL

────────

Black Box Security
Offensive mindset. Defensive results.

Security Policy

This repository is an educational and professional portfolio.

Do not commit:

• Passwords or authentication cookies
• API keys, bearer tokens, or session tokens
• Private customer or user information
• Production database contents
• Non-public source code belonging to third parties
• Undisclosed vulnerability details
• Screenshots containing sensitive information

If sensitive data is accidentally committed, revoke the affected secret immediately and remove it from Git history before making the repository public.
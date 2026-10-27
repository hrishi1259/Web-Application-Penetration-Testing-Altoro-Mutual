# Web Application Penetration Testing — Altoro Mutual (testfire.net)

A black-box web application penetration test against Altoro Mutual (`testfire.net`), an intentionally vulnerable demo banking application, resulting in twelve documented, severity-ranked findings.

## Objective
Apply the OWASP-style web application testing methodology to identify and document exploitable vulnerabilities in a realistic banking application context.

## Scope
- **Target:** `testfire.net` (Altoro Mutual demo banking application)
- **Testing type:** Black-box web application penetration test

## Key Findings
Twelve vulnerabilities identified and documented, including severity ratings and remediation recommendations. Full details in the final report.

## Methodology
1. **Reconnaissance** — application mapping and attack surface discovery
2. **Vulnerability identification** — manual and tool-assisted testing (e.g., injection, authentication, session management, access control)
3. **Verification** — proof-of-concept validation for each finding
4. **Reporting** — severity ranking (CVSS-aligned) and remediation guidance

## Tools & Technologies
`Burp Suite` · `OWASP Testing Methodology` · `Manual Web Exploitation`

## Skills Demonstrated
Web application security testing, OWASP Top 10 vulnerability classes, manual exploitation, professional security reporting.

## Repository Structure
```
.
├── reports/
│   ├── Web_Application_VAPT_Report.pdf   # Final report
│   └── Web_Application_VAPT_Report.docx  # Editable source
├── LICENSE
└── README.md
```

## Disclaimer
`testfire.net` is a publicly available, intentionally vulnerable demo application provided by IBM for security testing practice. This work is for educational and professional development purposes only.

## License
Released under the [MIT License](./LICENSE).

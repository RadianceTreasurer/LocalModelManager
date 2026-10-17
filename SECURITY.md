# Security Policy

## Reporting a Vulnerability

The security of this project and its users is taken seriously. If you believe you have found a security vulnerability, please report it responsibly using one of the methods below.

**Please do not open a public GitHub issue, pull request, or discussion for a security vulnerability.** Public disclosure before a fix is available may put users at risk.

### Preferred Method: GitHub Private Vulnerability Reporting

1. Go to the **Security** tab of this repository.
2. Click **Report a vulnerability**.
3. Provide as much detail as possible (see "What to Include" below).

### Alternative Method: Email

If private vulnerability reporting is not enabled for this repository, please contact the maintainers at:

**[INSERT SECURITY CONTACT EMAIL]**

If you cannot reach the maintainers through either method, you may open a public issue titled **"Security contact request"** asking for a private contact channel. Do **not** include any vulnerability details in that issue.

## What to Include

To help us verify and fix the issue as quickly as possible, please include:

- A clear description of the vulnerability and its potential impact
- The affected component, file, version, release, or commit hash
- Step-by-step instructions to reproduce the issue
- A proof of concept (PoC), sample input, code, screenshots, or logs, if available
- Your operating system, runtime/tool versions, and relevant environment details
- Any suggested fix or mitigation, if you have one

Please test against the latest version of the project (or the latest commit on the default branch) and confirm whether the issue is still present.

## Response Process

We aim to follow the timeline below. Actual times may vary depending on the severity and complexity of the report.

| Stage | Target |
| --- | --- |
| Acknowledgement of your report | Within 3 business days |
| Initial assessment and severity triage | Within 7 business days |
| Status updates during investigation | At least every 14 days |
| Fix or mitigation | As soon as reasonably possible, based on severity |

We will work with you to understand the issue, confirm its impact, and prepare a fix before any public disclosure.

## Coordinated Disclosure

Please give us a reasonable amount of time to investigate and release a fix before disclosing the vulnerability publicly. We aim to resolve valid reports within **90 days** of the initial report. If more time is required, we will discuss a revised disclosure date with you.

With your permission, we are happy to credit you in the release notes or security advisory once the issue has been fixed. If you prefer to remain anonymous, let us know in your report.

## Scope

### In Scope

- Source code in this repository
- Official releases published from this repository
- Build, installation, and update mechanisms provided by this project
- Documentation in this repository that could lead users to perform unsafe actions

### Out of Scope

The following are generally not considered security vulnerabilities for this project:

- Vulnerabilities in third-party dependencies that should be reported directly to the upstream project (you may still notify us so we can update the dependency)
- Attacks requiring physical access to a user's device
- Social engineering, phishing, or impersonation attacks
- Denial-of-service attacks caused solely by excessive traffic or resource exhaustion
- Missing security headers, TLS configuration issues, or similar findings on services not operated by this project, without a demonstrated security impact
- Reports generated solely by automated scanners without proof of exploitability
- Issues in forks, unofficial mirrors, or modified versions of this project

## Safe Harbor

We support good-faith security research. If you make a sincere effort to comply with this policy, we will consider your research authorized and will not pursue legal action against you in connection with it.

While researching, please:

- Only interact with accounts, systems, and data that belong to you, or for which you have explicit permission
- Do not access, modify, copy, or delete data belonging to others
- Do not degrade, disrupt, or interrupt the availability of any service
- Do not use automated tools in a way that generates excessive traffic or load
- Stop testing and report the issue immediately if you encounter personal data, credentials, or other sensitive information
- Do not publicly disclose the issue until we have had a reasonable opportunity to fix it

## User Safety: Official Sources

To protect yourself from impersonation and supply-chain attacks:

- Download this project **only** from this official GitHub repository and its official releases.
- Follow installation instructions **only** as documented in this repository. Be cautious of instructions on third-party websites, mirrors, videos, or comments that ask you to run remote installation commands (for example, downloading and executing scripts from unknown domains).
- Report unofficial mirrors, fake repositories, or suspicious download links by opening an issue (without including any malicious payloads or credentials).

Thank you for helping keep this project and its users safe.

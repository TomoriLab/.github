# Security Policy

## Scope

This is the default security policy for Tomori Lab repositories. A repository's own security policy takes precedence. Report vulnerabilities in Tomori Lab code, build and release workflows, dependencies as used by a project, and organization-managed infrastructure through the channels below.

## Reporting a vulnerability

Do not disclose vulnerability details in public issues, pull requests, discussions, or logs.

If the affected repository offers **Report a vulnerability** under its security advisories, use [GitHub private vulnerability reporting](https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/report-privately). Otherwise, email [escha@zeroday0619.dev](mailto:escha@zeroday0619.dev) with the subject `[Security] <repository or service>: <short summary>`.

For exposed credentials or suspected compromise, report immediately through either private channel. Never include a usable secret in the report; identify its location and type with the value redacted.

Include the following information when available:

- The affected repository, package, or service and its version, commit, or deployment.
- A description of the vulnerability and its security impact.
- Reproduction steps or a minimal proof of concept.
- Required access, configuration, and other exploitation conditions.
- Expected and observed behavior, with sanitized logs or screenshots.
- Suggested mitigations and any planned disclosure date.
- Your preferred contact details and whether you would like public credit.

Report a credible concern even if some details are missing. Remove personal data, credentials, and unrelated confidential information. If encrypted communication is required, request an agreed method before sending sensitive material.

## Supported versions

Check the affected repository's security policy and release documentation for supported versions. This organization-wide policy does not establish a support lifecycle or promise security backports. If no support information is published, include the affected version in your report and ask the maintainers to confirm its status. Report suspected vulnerabilities even when the support status is unclear.

## Security expectations and assessment

Projects must protect credentials, private data, and release integrity. Authorization must precede privileged operations, and untrusted input must remain within the intended access and resource boundaries. These are review requirements, not claims that every repository has been audited or that particular controls are deployed.

Reports are assessed using their reachability, exploitation requirements, and impact on confidentiality, integrity, or availability. Examples include unauthorized access, privilege escalation, code execution, sensitive data exposure, and compromise of build or release artifacts.

A dependency advisory or automated tool result should explain how the affected component is used and the potential impact on the project. Incomplete evidence warrants investigation rather than automatic dismissal. AI-assisted reports are subject to the same evidence standards; reporters must review their claims and distinguish observed results from unverified hypotheses.

Use public issue trackers for ordinary bugs and feature requests that contain no sensitive security details. If the security impact is uncertain, use a private reporting channel.

## Testing boundaries

Reproduce issues in local environments or systems you own or have explicit permission to test. This policy does not authorize testing live services, accessing other users' data, social engineering, denial of service, or destructive actions. Stop testing if it exposes another person's data and report the circumstances without retaining or sharing unnecessary copies.

## Response and coordinated disclosure

Maintainers review reports, request additional information as needed, and coordinate mitigation and disclosure with reporters. Response and remediation times depend on impact, complexity, and maintainer availability; this policy provides no fixed response or resolution deadline.

Coordinate a disclosure date that allows maintainers to investigate and users to apply mitigations. If you have a disclosure deadline, state it in the initial report. If you receive no response through GitHub, follow up by email without posting vulnerability details publicly.

Public advisories should identify affected versions, fixes or mitigations, and relevant limitations. Reporter credit is subject to the reporter's consent. This policy does not establish a bug bounty or promise compensation.

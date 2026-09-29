# Security Policy

This security policy applies to repositories maintained by CyberSecAuto Labs (CSAL).

## Supported versions

Unless a repository documents a different support policy:

- Security fixes target the latest stable release of actively maintained projects.
- Older releases do not receive security backports. Users should upgrade to the latest release.
- For projects without a stable release, reports affecting the latest pre-release or default branch are welcome; fixes target the current development version.
- Archived projects are no longer maintained and do not receive security updates.

If you are unsure whether a version or issue is covered, please report it privately so we can assess its impact.

## Reporting a vulnerability

Please report suspected vulnerabilities privately. Do not include vulnerability details, exploit code, credentials, or sensitive data in public issues, pull requests, or discussions before coordinated disclosure.

### Preferred channel: GitHub private vulnerability reporting

In the affected repository, open **Security → Advisories → Report a vulnerability** and submit a private report.

### Alternative contact

If private reporting is unavailable, or the issue affects multiple CSAL repositories, email **contact@cybersecauto-labs.org** with the subject:

`[SECURITY] <repository name> - <short summary>`

Use a brief, sanitized description in the initial email. For sensitive material, request an appropriate private exchange method before sending it.

### What to include

Where available, provide:

- The affected repository, version, tag, or commit.
- A description of the issue and its potential security impact.
- Reproduction steps or a minimal proof of concept.
- Relevant configuration, environment, and exploitation prerequisites.
- Sanitized logs, screenshots, or other supporting evidence.
- Any suggested mitigation or fix.
- Your preferred contact details and whether you would like public credit.

Incomplete reports are welcome. Please remove secrets and personal or third-party data from all examples.

## Response and remediation

CSAL is an independently maintained open-source initiative. We aim to:

- Acknowledge reports within **5 business days**.
- Provide an initial assessment or request for further information within **10 business days**.
- Share progress and coordinate remediation and disclosure with the reporter.

These are best-effort targets, not guaranteed service levels. Remediation timing depends on severity, exploitability, affected users, and maintainer availability. If you receive no acknowledgement within 5 business days, please follow up through the alternative contact above.

## Coordinated disclosure

Please allow a reasonable opportunity to investigate and address the issue before publishing technical details. We will work with you to agree on a disclosure timeline and communicate changes or delays.

For confirmed vulnerabilities, we aim to publish an advisory describing affected versions, available fixes or mitigations, and relevant upgrade instructions. We will credit reporters who wish to be acknowledged.

## Responsible testing

Use local test environments or systems you own or have explicit permission to test. Avoid accessing other people's data, disrupting services, or testing third-party deployments without authorization. Demonstrate impact using the minimum evidence necessary and stop if you encounter unexpected sensitive data.

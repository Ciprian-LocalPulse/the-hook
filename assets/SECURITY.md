# Security Policy

## Overview

THE HOOK is a defensive deception technology concept with a public evaluation repository and a separate Private Enterprise Edition.

This security policy applies only to the public repository and public preview materials. It does not grant access to private implementation detail, telemetry pipelines, detection rules, token generation methods, client environments, private playbooks, prompts, secrets, or commercial implementation materials.

## Supported Scope

Security reports are welcome for:

- exposed secrets, credentials, keys, or tokens
- accidental disclosure of private implementation detail
- unsafe public documentation
- unsafe public demo behavior
- repository integrity concerns
- misleading public claims that could create buyer or user risk
- brand impersonation or malicious mirrors involving this repository

Out of scope:

- requests for operational deception logic
- requests for telemetry pipelines or detection rules
- requests for token generation methods
- requests for private playbooks, prompts, or client environment details
- exploit development or offensive guidance
- testing against systems, accounts, or infrastructure not owned by the maintainer
- social engineering, phishing, spam, or denial-of-service activity

## Reporting a Vulnerability

Do not open a public GitHub issue for security vulnerabilities.

Use a private channel:

- Security inquiry: contact@localpulse.pro
- Private briefing: https://cal.com/ciprian-stefan-plesca

Use the subject line:

```text
[SECURITY] THE HOOK - <short summary>
```

Please include:

- affected file or URL
- clear description of the issue
- reproduction steps if applicable
- impact assessment
- whether any sensitive material appears exposed
- suggested remediation, if available
- your preferred contact method

## Responsible Disclosure Expectations

Researchers and reviewers must:

- avoid public disclosure before review
- avoid testing systems they do not own or control
- avoid accessing, modifying, deleting, or exfiltrating data
- avoid posting live secrets in public issues, pull requests, or discussions
- keep reports concise, factual, and confidential

The maintainer will make a good-faith effort to review legitimate reports, validate impact, and remediate public-repository issues in a timely manner.

## Public Repository Safety Standard

The maintainer may remove, reject, or revise material that:

- weakens the defensive framing of the project
- exposes restricted operational detail
- increases dual-use ambiguity
- introduces secrets or private material
- creates procurement, legal, security, or brand risk

## Private Enterprise Boundary

Security review of the Private Enterprise Edition, if requested by an authorized buyer or partner, must be handled through a separate private diligence process under written agreement.

Private package access is not available through public issues, pull requests, or security reports.

## No Warranty

This public repository is provided for evaluation and discussion only. It is not a security certification, audit report, legal opinion, production readiness attestation, or compliance certification.

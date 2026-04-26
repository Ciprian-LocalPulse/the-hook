# Security Policy

THE HOOK is maintained as a defensive-security public repository. This policy defines how security issues should be reported, what is in scope for public review, and which details must remain private.

## Defensive-Security Scope

This repository is limited to the Public Edition of THE HOOK. Public materials may include product positioning, static interface previews, sanitized architecture notes, documentation, and non-operational examples.

This repository must not disclose or request disclosure of:

- deception logic or operational deployment methods
- telemetry pipelines, enrichment flows, or detection rules
- client environments, infrastructure names, customer data, or internal network details
- token generation methods, credential workflows, API keys, secrets, or private configuration
- private playbooks, internal prompts, commercial implementation details, or restricted research

## Supported Scope

Security reports are welcome for issues affecting public repository materials, including:

- accidental exposure of secrets or sensitive data
- unsafe public documentation that could enable misuse
- vulnerable public demo code, if present
- dependency, supply-chain, or build configuration concerns, if such files are later added
- repository configuration issues that create meaningful security or integrity risk

## Out of Scope

The following are generally out of scope unless they expose sensitive data or create direct risk:

- generic best-practice requests without a specific risk
- social engineering, phishing, or physical security testing
- denial-of-service testing or traffic flooding
- scanning infrastructure not owned or explicitly authorized by the maintainer
- automated reports with no exploitability explanation
- issues in third-party platforms outside this repository owner's control
- requests for private enterprise architecture, detection logic, telemetry design, or implementation details

## Reporting Process

Please report security issues privately and with minimal sensitive detail.

Preferred process:

1. Use GitHub private vulnerability reporting if it is enabled for this repository.
2. If private vulnerability reporting is unavailable, contact the maintainer through the public GitHub profile or the commercial contact path listed in SUPPORT.md.
3. Do not open a public issue containing secrets, exploit details, private infrastructure references, or implementation-sensitive information.
4. Include a concise description, affected file or area, reproduction notes where safe, and your recommended remediation.

## Response Timeline

The maintainer will make a reasonable effort to follow this timeline:

- Acknowledgement: within 5 business days
- Initial triage: within 10 business days
- Remediation decision: based on severity, exploitability, and public safety impact
- Public disclosure: only after remediation or explicit maintainer approval

This repository is maintained as a public product and governance surface. Response times may vary for non-critical documentation findings.

## Safe Harbor

Good-faith research is welcome when it is defensive, limited, and respectful of the boundaries above. The maintainer will not pursue action against researchers who:

- act in good faith and avoid privacy violations
- do not access, modify, delete, or exfiltrate data
- do not disrupt services or third-party systems
- avoid public disclosure before coordination
- stop testing and report promptly after identifying a potential issue

Safe harbor does not apply to activity involving unauthorized access, credential misuse, persistence, lateral movement, extortion, data theft, or attempts to obtain private enterprise materials.

## Public Disclosure

Public disclosure should be coordinated with the maintainer. Reports may be acknowledged in release notes or changelog entries when doing so does not reveal sensitive security information.

## Responsible Use

THE HOOK is defensive-security only. Reports, issues, pull requests, or discussions that introduce offensive capability, unsafe operational detail, or misuse-enabling instructions may be closed or removed.
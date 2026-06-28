# SecuredMe License Family

> **Development status.** This school tool is currently tagged **pre-alpha / in development**. External PRs are not evaluated for merge until the maintained tool reaches a stable, fully functional 100% classroom release after the pre-alpha phase. Issues and forks remain allowed, but official PR review is paused until that stability gate is met.


This repository is the canonical home for the SecuredMe educational license
family.

The family has two current custom license identifiers:

- **SEL-2.0**: Secured Educational License, for general educational tools.
- **SECL-2.0**: Secured Educational Cybersecurity License, for cybersecurity,
  fraud-awareness, safety, and abuse-prevention training tools.

Use these source headers:

```text
SPDX-License-Identifier: LicenseRef-SEL-2.0
SPDX-License-Identifier: LicenseRef-SECL-2.0
```

`LicenseRef-SEL-2.0` and `LicenseRef-SECL-2.0` are custom license
identifiers. They are not currently OSI-approved licenses and are not currently
listed in the SPDX License List. SPDX-compatible tooling may still reference
them as `LicenseRef-*` identifiers when the full license text is included with
the project.

## Maintainer Identity

Primary author and maintainer:

Jean-Sebastien Beaulieu  
ORCID: https://orcid.org/0009-0007-2904-0443  
SecuredMe

The ORCID is included for attribution, provenance, and maintainer identity. It does not create an endorsement by ORCID, OpenAI, Google, or any other third party.

## Purpose

SEL-2.0 is intended for educational software, classroom tooling, research
scaffolds, simulation tools, and student/teacher learning environments.

SECL-2.0 is intended for educational cybersecurity, fraud-awareness,
algorithm-safety, abuse-prevention, and defensive training environments. It is
not a license for attack tooling.

The license and accompanying policy documents are designed to keep three things visible:

- the software is open for learning, review, sharing, and improvement;
- the maintained school version is supported only through reviewed official changes;
- misuse remains the responsibility of the person or organization misusing the software.

## Important Boundaries

SEL does not authorize harmful use. Do not use SEL-covered projects for attack, theft, fraud, impersonation, bypass, unsafe surveillance, criminal automation, or unsupervised safety-critical decisions.

SEL does not make Jean-Sebastien Beaulieu, SecuredMe, OpenAI/Codex, Google/Gemini/Antigravity, contributors, schools, or reviewers responsible for misuse, broken private forks, illegal deployments, or unsafe modifications.

SEL is not legal advice. Schools, organizations, and commercial users should obtain qualified legal review before adopting it in production.

## Files

- `LICENSE` - family index and default repository notice.
- `LICENSE-SEL-2.0` - Secured Educational License 2.0.
- `LICENSE-SECL-2.0` - Secured Educational Cybersecurity License 2.0.
- `NOTICE` - attribution and maintainer identity.
- `DISCLAIMER` - no warranty, no misuse responsibility, and third-party boundary.
- `SAFETY.md` - forbidden misuse and educational-use guardrails.
- `USAGE.md` - how to apply the license identifiers.
- `SEL_ADOPTION_CHECKLIST.md` - repo adoption checklist.

## Relationship To SPDX

This repository began from SPDX license-list material as a reference point for license structure and naming conventions. SEL is not a replacement for the SPDX License List and does not claim SPDX approval.

For SPDX-compatible projects, include the full selected license text in
`LICENSE` and use one of:

```text
SPDX-License-Identifier: LicenseRef-SEL-2.0
SPDX-License-Identifier: LicenseRef-SECL-2.0
```



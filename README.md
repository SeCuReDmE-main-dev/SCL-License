# SEL-License

SEL means **Secured Educational License**.

This repository is the canonical home for the SecuredMe educational license family. It replaces the earlier SCL naming intent with a clearer school-centered name: **SEL-2.0**, identified in source headers as:

```text
SPDX-License-Identifier: LicenseRef-SEL-2.0
```

`LicenseRef-SEL-2.0` is a custom license identifier. It is not currently an OSI-approved license and is not currently listed in the SPDX License List. SPDX-compatible tooling may still reference it as a `LicenseRef-*` identifier when the full license text is included with the project.

## Maintainer Identity

Primary author and maintainer:

Jean-Sebastien Beaulieu  
ORCID: https://orcid.org/0009-0007-2904-0443  
SecuredMe

The ORCID is included for attribution, provenance, and maintainer identity. It does not create an endorsement by ORCID, OpenAI, Google, or any other third party.

## Purpose

SEL-2.0 is intended for educational software, classroom tooling, research scaffolds, simulation tools, and student/teacher learning environments.

The license and accompanying policy documents are designed to keep three things visible:

- the software is open for learning, review, sharing, and improvement;
- the maintained school version is supported only through reviewed official changes;
- misuse remains the responsibility of the person or organization misusing the software.

## Important Boundaries

SEL does not authorize harmful use. Do not use SEL-covered projects for attack, theft, fraud, impersonation, bypass, unsafe surveillance, criminal automation, or unsupervised safety-critical decisions.

SEL does not make Jean-Sebastien Beaulieu, SecuredMe, OpenAI/Codex, Google/Gemini/Antigravity, contributors, schools, or reviewers responsible for misuse, broken private forks, illegal deployments, or unsafe modifications.

SEL is not legal advice. Schools, organizations, and commercial users should obtain qualified legal review before adopting it in production.

## Files

- `LICENSE` - the Secured Educational License 2.0 text.
- `NOTICE` - attribution and maintainer identity.
- `DISCLAIMER` - no warranty, no misuse responsibility, and third-party boundary.
- `SAFETY.md` - forbidden misuse and educational-use guardrails.
- `USAGE.md` - how to apply `LicenseRef-SEL-2.0`.
- `SEL_ADOPTION_CHECKLIST.md` - repo adoption checklist.

## Relationship To SPDX

This repository began from SPDX license-list material as a reference point for license structure and naming conventions. SEL is not a replacement for the SPDX License List and does not claim SPDX approval.

For SPDX-compatible projects, include the full SEL license text in `LICENSE` and use:

```text
SPDX-License-Identifier: LicenseRef-SEL-2.0
```

# SecuredMe License Family

[![SecuredMe Education Suite public calendar](https://img.shields.io/badge/SecuredMe%20Education%20Suite-public%20calendar%20%7C%20alpha%20Aug%203%202026-5484ED?style=for-the-badge&logo=googlecalendar&logoColor=white)](https://calendrier.securedme.ca)

**Attribution:** Jean-Sebastien Beaulieu · [ORCID 0009-0007-2904-0443](https://orcid.org/0009-0007-2904-0443) · [SecuredMe](https://securedme.ca) · [SecuredMe License Family](https://licenses.securedme.ca)


## School Authentication And Secret Boundary
This repository is a small SecuredMe school tool. Official classroom use must not require `.env` files, API keys, raw tokens, or local model secrets. Student and teacher workflows must use Codex/OpenAI or Antigravity/Gemini through browser WebAuth, fingerprinted session approval, and encrypted local session records when authentication is needed.

The reason for excluding generic local AI routes from official school mode is student and teacher safety: education accounts, provider-side account controls, browser login, and governed AI refusal behavior are safer than unguided local model endpoints for classroom cybersecurity and algorithm-building tools.

> **Development status.** This school tool is currently tagged **pre-alpha / in development**. External PRs are not evaluated for merge until the maintained tool reaches a stable, fully functional 100% classroom release after the pre-alpha phase. Issues and forks remain allowed, but official PR review is paused until that stability gate is met.

> **SecuredMe Education visual reference.** This repository carries the shared SecuredMe Education visual package as a reference for the tool suite, not as a separate student-facing product identity. See [assets/securedme/education](assets/securedme/education).


This repository is the canonical home for the SecuredMe educational license
family.

The family has two current public license names:

- **SEL-2.0**: Secured Educational License, for general educational tools.
- **SECL-2.0**: Secured Educational Cybersecurity License, for cybersecurity,
  fraud-awareness, safety, and abuse-prevention training tools.

When a tool requires SPDX-compatible metadata, use these local technical
references only if the full license text is shipped in the repository:

```text
LicenseRef-SEL-2.0
LicenseRef-SECL-2.0
```

Do not present SEL-2.0 or SECL-2.0 as OSI-approved or SPDX-listed licenses.
The public-facing license name is SEL-2.0 or SECL-2.0. `LicenseRef-*` is only a
local metadata bridge for tools that understand custom license references.

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
`LICENSE`. If local custom license references are needed by tooling, use one of
these metadata references and point it back to the full text:

```text
LicenseRef-SEL-2.0
LicenseRef-SECL-2.0
```




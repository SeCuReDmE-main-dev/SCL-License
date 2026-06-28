# Upstream SPDX Reference

This repository originally used the SPDX license-list XML repository as a
reference for license identifier conventions and `LicenseRef-*` usage.

SEL/SECL are not part of the SPDX License List and are not OSI-approved at this
time. The correct current public names are:

```text
SEL-2.0
SECL-2.0
```

Use `LicenseRef-SEL-2.0` and `LicenseRef-SECL-2.0` only as local metadata
references when tooling requires custom license keys and the full selected
license text is included with the project.

Useful primary references:

- https://github.com/spdx/license-list-XML
- https://spdx.org/ids/

# SecuredMe School Suite Governance Audit

Current audit state after SEL/SECL consolidation.

| Repo | License | Official school AI route | Validation | Known exception |
| --- | --- | --- | --- | --- |
| `SCL-License` | `LicenseRef-SEL-2.0` / `LicenseRef-SECL-2.0` family | Codex/OpenAI + Antigravity/Gemini wording only | Documentation scan | Custom licenses are not SPDX/OSI approved |
| `Synthia` | MIT | Codex/OpenAI + Antigravity/Gemini | `python -m pytest -q` | NOTICE/DISCLAIMER companion added without changing MIT |
| `FNP-QNN-MVP` | Existing project license | Codex/OpenAI + Antigravity/Gemini | `python -m pytest tests/test_cli_tui_doctor.py -q` | Two pre-existing untracked asset folders |
| `fnpqnn_gateway_MVP` | MIT | Codex/OpenAI + Antigravity/Gemini | `python -m pytest tests/test_gateway_cli.py -q` | Unsupported providers remain only as rejection paths |
| `securedme-scholarium` | `LicenseRef-SEL-2.0` | Codex/OpenAI + Antigravity/Gemini | Governance scan | Docs-oriented repo |
| `tesla-resonance-recovery-workbench` | MIT | Codex/OpenAI + Antigravity/Gemini | Prior `pytest` passed | NOTICE/DISCLAIMER companion added without changing MIT |
| `market-guardian-retailguard` | `LicenseRef-SECL-2.0` | Codex/OpenAI + Antigravity/Gemini | Governance scan | Functional review deferred |
| `FfeD-QLC-MVP` | MIT | Codex/OpenAI + Antigravity/Gemini | `python -m pytest -q` | NOTICE/DISCLAIMER companion added without changing MIT |
| `VisualAlgorithmDesigner` | `LicenseRef-SEL-2.0` | Codex/OpenAI + Antigravity/Gemini | Governance scan | Node build deferred if deps absent |
| `algorithm-builder-app` | `LicenseRef-SEL-2.0` | Codex/OpenAI + Antigravity/Gemini | `npm test` smoke | Build deferred if deps absent |
| `QuaNThoR` | Apache-2.0 | Codex/OpenAI + Antigravity/Gemini | `python -m pytest -q` | Legacy model shims are non-official |
| `V.O.T-Guardian` | `LicenseRef-SECL-2.0` | Codex/OpenAI + Antigravity/Gemini | Governance scan | Functional review deferred |
| `algoquest-ams-discovry-labs-module-` | `LicenseRef-SEL-2.0` | Codex/OpenAI + Antigravity/Gemini | Governance scan | Node build deferred if deps absent |

Suite invariant:

- school tools are training/review support only;
- unsupported AI routes are not official classroom providers;
- private modified copies are not the maintained school version;
- cybersecurity tools are defensive education only.

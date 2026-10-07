# Documentation Migration Register

**Editorial revision:** 7 October 2026.  
**Processed sources:** 2.

| Entry | Original path | Destination | Treatment |
| --- | --- | --- | --- |
| 1 | `docs/An Open Architecture Modular.txt` | [Open-architecture modular GCS drone trailer](architecture/modular-gcs-drone-trailer.md) | Already English; structured and indexed; source claims qualified; TXT removed from branch and retained in Git history |

| 2 | `docs/En el Perú la regulación.txt` | [Peru RPAS pilot accreditation](training/peru-rpas-pilot-accreditation.md) | Spanish translated to English; all six questions, 24 choices, six answers and four requirement statements retained; editorial verification notes added; TXT retained in Git history |

## Source snapshot and coverage

Source commit: `ca8c38485a58d1f9553f1e6e07c92a4bd308753d`.

The destination preserves the introductory scope and all four table rows: MOSA/open architecture, modular workstations/radios, deployable antennas, and environmental/power resilience. It retains MAVLink, STANAG-4586, ROS, plugins, edge AI, Silvus, Wave Relay, SATCOM and MANET RF, plus the source's 30+ datalinks, 8+ meters and up-to-35-kW claims.

Numerical and compatibility claims remain unverified. Generator capacity scope and “MIL-spec” wording are explicitly unresolved. Digital-twin integration, the Mermaid workflow and scenario descriptions are editorial additions linked to the existing concept image; no engineering or operational validation was performed.

## RPAS source snapshot and coverage

Source commit: `a59942030e2aa26418a5056241627e6e59a66e1e`. Source blob: `e8369747df0e7fc91fcbaa310bd778402a0be84d`.

The migration preserves the DGAC/MTC and FAP context, both cited NTC identifiers, the full quiz, answer order B/C/B/B/B/B, and training, examination, medical and aircraft-registration statements. Source claims are separated from editorial notes: official examination attribution, NTC 001-2023, FAP scope, Class 3 medical certification and training-provider requirements remain unverified. The 75% threshold is supported by indexed MTC information; direct retrieval of that page failed. A link to Supreme Decree No. 012-2026-MTC records newer regulatory context without asserting a complete applicability assessment. The loss-of-visual-contact question includes a separate contingency-procedure qualification.

No software, official examination or flight validation was performed.

[Documentation index](README.md) · [Project overview](../README.md)

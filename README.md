# Bengkalis Immigration: MILES Process Analysis

A business analysis case study built from one public document: the 2025 SOP package of
Kantor Imigrasi Kelas II TPI Bengkalis. It maps the mobile passport service (MILES),
identifies pain points, and proposes digitization improvements.

**Live page:** https://cloudbv.github.io/ba-passport-process-analysis/

## What this is (and isn't)
Built only from the published SOPs. It shows process mapping, requirements writing and
honest handling of evidence. It is not an evaluation of how the office actually performs.

## Contents
| File | What it holds |
|---|---|
| [docs/SOURCES.md](docs/SOURCES.md) | Sources, handling, limitations |
| [docs/facts.md](docs/facts.md) | What the SOPs say, with page numbers |
| [docs/pain-points.md](docs/pain-points.md) | P1 to P5, with evidence type |
| [docs/BRD.md](docs/BRD.md) | Business requirements (REQ-01 to REQ-05) |
| [docs/user-stories.md](docs/user-stories.md) | User stories with acceptance criteria |
| [diagrams/as-is-process.png](diagrams/as-is-process.png) | As-is swimlane diagram of the 17-step MILES slide |
| [diagrams/to-be-process.png](diagrams/to-be-process.png) | Proposed to-be diagram with changes tagged by requirement |
| [index.html](index.html) | Source of the live page |

## Key findings
- MILES begins with a written request, and the SOP does not say whether it is paper.
- The slide shows the team traveling before verification and the cekal check.
- Nothing describes tracking after the passport goes to the post office.
- The SOP document is inconsistent in several places (details in pain-points.md).

## Proposed requirements
| ID | Summary | Priority |
|---|---|---|
| REQ-01 | Online MILES request with confirmation, replacing the written request | Must |
| REQ-02 | Review registrations before the visit and deploy only when enough are complete | Must |
| REQ-03 | One status page through to dispatch, including the PT Pos tracking number | Should |
| REQ-04 | Tell applicants why documents were rejected and how to reschedule | Could |
| REQ-05 | Document control for the SOP package (version, owner, consistency check) | Should |

REQ-02 and REQ-03 rest on stated assumptions, and REQ-04 is inferred. See the BRD.

## How to check my work
Every fact cites a page of SOP-INOVASI. Open the link in
[docs/SOURCES.md](docs/SOURCES.md), then go to that page. Anything not from a source is
labeled Inferred or Assumption.

## Limitations
The SOPs show the intended process, not observed practice, and nothing was confirmed with
staff. See [docs/SOURCES.md](docs/SOURCES.md) for the full list.

## Author
Yosef Setiawan, [github.com/cloudBV](https://github.com/cloudBV)
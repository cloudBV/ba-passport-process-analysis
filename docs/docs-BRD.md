# BRD: Improving the Bengkalis MILES Process

## 1. Background
Kantor Imigrasi Kelas II TPI Bengkalis runs MILES, a mobile service where officers take
photos and conduct interviews for passport applicants at schools, cafes, malls and
companies (SOP-INOVASI p.6-7). The text SOP describes 4 to 5 steps. The slide shows 17
(p.9). The process starts with a written request from the institution and ends with the
post office delivering the passport. The SOP package also contains internal
inconsistencies (see P5 in pain-points.md).

## 2. Objective
Reduce manual handoffs and wasted mobile trips in MILES, give applicants visibility after
dispatch, and make the SOP documents consistent, all within the office's own control.

## 3. Scope
**In scope:** Recommendations for the Bengkalis local innovation stack (website,
WhatsApp channel, internal procedures) and SOP document control.
**Out of scope:** Changes to the national M-Paspor app, Simponi payment, the SIMKIM
server, the cekal check, or passport printing. Where a proposal needs one of these, it is
written as an assumption or a request to the directorate.
**Won't do this round:** Moving payment before verification (payment follows the cekal
check at slide step 10-11, which probably avoids refunds) and replacing on-site biometrics.

## 4. Stakeholders
| Stakeholder | Interest | Source |
|---|---|---|
| Applicant | Fewer trips, clear status, no surprise rejection | Assumption |
| Institution representative (school head, cafe owner, mall or company manager) | Request MILES with little effort | SOP-INOVASI p.6-7 |
| Loket officer | Complete documents | SOP-INOVASI p.9 |
| Mobile team | Travel only when the trip is worthwhile | Assumption |
| Office head | Efficient use of staff, consistent SOPs | SOP-INOVASI p.2 (approver) |
| PT Pos | Clear handover and tracking data | SOP-INOVASI p.6-7 |

## 5. Current process and problems
- As-is diagram: diagrams/as-is-process.png (to be added)
- Problems: [pain-points.md](pain-points.md), P1 to P5

## 6. Requirements
Only 5, because the source is one SOP package. More would be invented.

| ID | The solution shall... | Priority | Why this priority | Basis |
|---|---|---|---|---|
| REQ-01 | Let an institution submit a MILES request online and receive a confirmation, instead of a written request | Must | Entry point of the whole service and fully within local control | P1; SOP-INOVASI p.6 step 1 |
| REQ-02 | Have the office review M-Paspor registrations before the MILES date and deploy only when a minimum number of applicants have complete documents | Must | Directly targets possible wasted trips | P2; **Assumption**: sources do not say officers can see registrations early |
| REQ-03 | Show one status page from application to dispatch, including the PT Pos tracking number | Should | Useful, but depends on PT Pos data | P3; **Assumption**: PT Pos can supply tracking data |
| REQ-04 | Tell an applicant why documents were rejected or incomplete and how to reschedule | Could | Inferred need, not evidenced for MILES | P4 (**Inferred**); model: Sipentri "approved or postponed" (p.15) |
| REQ-05 | Apply document control to the SOP package: version number, one named owner, and a consistency check of text against slide before publishing | Should | Cheap, needs no system, and fixes problems observed in the document | P5; SOP-INOVASI pp.4, 6, 14-16, 22-23 |

## 7. Constraints, assumptions and limitations
- **Limitation:** Built from the published SOPs, not from observation or interviews. They
  show the intended process only.
- **Constraint:** Pre-review (REQ-02) covers completeness only. The cekal check and final
  verification happen on site in the immigration system (slide step 10).
- **Assumption:** Officers can see M-Paspor registrations before the visit.
- **Assumption:** PT Pos can provide tracking data in a usable form.
- **Open question:** The text says applicants register in M-Paspor (p.6), while the slide
  shows collective files going to the Loket (p.9 step 4). I have not resolved which is
  current practice.
- **Risk:** Applicants with low digital skills may be excluded. A manual or assisted
  channel must remain.

## 8. Success measures
Baselines come from the SOP standards. Targets are illustrative and need real data.

| Measure | Baseline | Illustrative target |
|---|---|---|
| MILES standard processing time | 4 working days
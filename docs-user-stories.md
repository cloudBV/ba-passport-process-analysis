# User Stories

Each story traces to a requirement and a pain point. US-04 is inferred, and US-02 and
US-03 rest on stated assumptions.

## US-01: Online MILES request (REQ-01, P1)
As an institution representative, I want to request a MILES visit online, so that I do
not have to prepare and deliver a written request.

Acceptance criteria:
- Given I open the request form on the office website, when I submit my institution's
  details and preferred dates, then I receive a confirmation that the request was received.
- Given the office has decided on my request, when I check or am notified, then I see the
  approved schedule or the reason it was declined.

## US-02: Review before the visit (REQ-02, P2, assumption)
As a Loket officer, I want to review applicants' registrations before the MILES date, so
that the mobile team only travels when enough applicants are ready.

Acceptance criteria:
- Given a MILES date is set and applicants have registered, when I open the list, then I
  can mark each registration Complete or Incomplete.
- Given the review cutoff has passed, when fewer than the minimum number (set by the
  office, value to be decided) are Complete, then the office is alerted to decide whether
  to reschedule.
- Note: the cekal check and final verification still happen on site (slide step 10).
- Assumes officers can see registrations early (not stated in the sources).

## US-03: One status page (REQ-03, P3, assumption)
As an applicant, I want one place to see my passport status through to delivery, so that
I know when to expect it.

Acceptance criteria:
- Given I enter my application number, when I open the status page, then I see the current
  stage (registered, printed, dispatched).
- Given my passport has been handed to PT Pos, when tracking data is available, then the
  page shows the tracking number.
- Assumes PT Pos can supply tracking data.

## US-04: Clear rejection reasons (REQ-04, P4, inferred)
As an applicant, I want to know why my documents were rejected or incomplete, so that I
can fix them without starting over.

Acceptance criteria:
- Given an officer marks my documents Incomplete or rejected, when the status changes, then
  I am notified of the reason.
- Given I have been notified, when I open the message, then I can see how to resubmit or
  reschedule.

## US-05: Consistent SOPs (REQ-05, P5)
As the office head, I want every SOP checked for consistency before it is published, so
that staff and the public are not given conflicting steps or times.

Acceptance criteria:
- Given a new or changed SOP, when it is reviewed, then a checklist confirms that the step
  count, time standards and table headings match between text and slide.
- Given an SOP is published, when anyone opens it, then it shows a version number, a date
  and a named owner.
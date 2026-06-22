# TOJ Advisory / SubjectSkillz — AI Maturity Assessment
**Review cadence:** weekly
**Reference:** see `SUBJECT-OS-MASTER.md` (`Groundfloorsports/trail-of-joy/`) for the full ladder definition

## How to use this file

Each week, answer the question at the current level honestly. Don't round up.

## Current Assessment

| Level | Name | Question | Status | Evidence |
|---|---|---|---|---|
| 1 | Anticipation | Can we predict mentorship/NIL/creator-education trends before competitors? | 🔴 No | No documented trend-tracking process |
| 2 | Question Mastery | Are we asking better questions than competitors? | 🟢 Yes | The Model A/Model B distinction (scalable course portal vs. 1-on-1 mentorship, coexisting rather than one replacing the other) and the deliberate "family office, not sports agency" register are genuinely differentiated thinking in a market that mostly treats mentorship and curriculum as substitutes for each other |
| 3 | Asset Creation | What assets exist? | 🟡 Partial | Strong legal/structural assets exist — `mentorship-agreement-template.md`, `education-delivery-architecture.md`, `mentor-assignment-matching-sop.md` — but there is **no `goals/`, no `workflows/`, no `skills/`, no `feedback/` folder at all**. This repo is currently a document library, not yet an operating loop |
| 4 | Automation | What repetitive work has AI removed? | 🔴 No | Nothing yet — no daily/weekly workflow exists to automate against |
| 5 | Agents | What tasks have become named agents? | 🔴 No | No `agents/` folder |
| 6 | Agent Ecosystem | Can agents manage other agents? | 🔴 No | N/A until Level 5 |
| 7 | Custom AI | What proprietary intelligence can only TOJ Advisory provide? | 🟡 Partial | The mentor-matching logic (Crew Hub primary source, XpandSports revenue-share administration, mandatory re-vetting even for already-trusted Crew Hub contractors) is a real proprietary process, but it lives in a static SOP document, not a queryable or repeatable agent-run system yet |

## This Week's Single Highest-Leverage Move

**This week:** This repo needs the basic scaffold the other two OS repos already have — `goals/goals.md`, `workflows/daily.md`, `feedback/feedback-log.md` — before maturity-ladder progress is even measurable session-to-session. Right now an agent reading this repo gets excellent *context* (what SubjectSkillz is, the brand line, the two education models) but no instruction for *what to do today*. That's the actual Level 2→3 gap here: the documents exist, but they're not yet wired into a cadence.

## Notes

- This repo is structurally different from Subject-report-os and Subject-medias-os: it holds legal/program documents (an agreement template, an architecture explainer, a matching SOP) rather than a running marketing/sales operation. That's appropriate to what SubjectSkillz actually is right now — a program being designed, not yet a daily-output engine. Don't force the daily.md pattern to look identical to SubjectReport's 48hr-SLA-guard style; TOJ Advisory's daily workflow should center on mentor-matching status, agreement signature tracking, and the minor-safety vetting checklist instead.
- Per `CLAUDE.md`, this repo deliberately does NOT duplicate `TWO-TRACK-ATHLETE-MODEL.md`, `CONTRACTOR-MINOR-FOOTAGE-OVERLAP-RULE.md`, `MASTER-BUILD-PIPELINE.md`, or `INDEX.md` — those stay in `Groundfloorsports/trail-of-joy/`. Keep that discipline when building out `goals/` and `workflows/` here: reference, don't copy.

## Revision History
- v1.0 — Initial assessment, June 2026.

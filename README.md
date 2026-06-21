# TOJ-advisory-os

The dedicated operating-agent repo for SubjectSkillz mentorship — brand 03 of the Subject/Ecosystem (TOJ Advisory: counsel · NIL · brand strategy, champagne gold `#D4A853`).

## Why this repo is shaped differently from Subject-report-os / Subject-medias-os

SubjectReport and Subject Media were clean splits — their operating-brain content had zero real cross-references to anything else, so it could be moved wholesale. SubjectSkillz is different: it's deeply interwoven with shared governance/safety documents that also apply to Groundfloorsports-filmed athletes (Track B) and Subject Media's adult contractors. Moving those shared documents here would recreate the exact "blur between tracks" problem they were written to prevent.

So this repo holds **only** the documents that are genuinely SubjectSkillz-exclusive. Everything shared stays in `Groundfloorsports/trail-of-joy/` and is referenced, not duplicated.

```
TOJ-advisory-os/
├── CLAUDE.md                                  ← identity + operating context (auto-loaded)
├── workflows/
│   └── daily.md                               ← mentor capacity check, intake, assignment workflow
└── docs/
    ├── mentorship-agreement-template.md       ← the mentor↔mentee contract (TEMPLATE — needs legal review)
    ├── education-delivery-architecture.md     ← Model A (course) vs Model B (1-on-1 mentorship)
    └── mentor-assignment-matching-sop.md       ← mentor sourcing, vetting, matching, compensation
```

## What stays in Groundfloorsports (read, don't duplicate)

- `trail-of-joy/TWO-TRACK-ATHLETE-MODEL.md` — Track A vs Track B, the document preventing the two from blurring
- `trail-of-joy/CONTRACTOR-MINOR-FOOTAGE-OVERLAP-RULE.md` — governs Subject Media contractor footage of Track A/B minors
- `trail-of-joy/MASTER-BUILD-PIPELINE.md` — general company-build pipeline + minor-safety hard gate, used across all Trail of Joy companies
- `trail-of-joy/INDEX.md` — the map of everything in `trail-of-joy/`, including legal-review status

## Relationship to other repos

- **`Groundfloorsports`** — paperwork/policy architecture for the whole Trail of Joy ecosystem; still holds the shared Track A/B governance docs this repo references.
- **`Subject-report-os`** — SubjectReport's operating agent (brand 01, electric blue).
- **`Subject-medias-os`** — Subject Media's operating agent (brand 02, coral).

Every session: read `CLAUDE.md` first, then `workflows/daily.md`. If a task touches Track B, contractor overlap, or the general build pipeline, fetch the relevant doc from `Groundfloorsports` rather than relying on a stale local copy.

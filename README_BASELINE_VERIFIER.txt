Engineer Pay Log — Crew Book Revision Verifier
BASELINE PRODUCTION

Purpose
-------
This is the baseline production tool for future Crew Book revisions.

Workflow
--------
1. User supplies a revision PDF/cover.
2. Revised / Added / Abolished crews are identified.
3. Official assignment scans/crops are attached to the corresponding job cards.
4. Assistant pre-fills every structured record to the best of its ability.
5. User reviews EVERY job against the pinned official Crew Book source.
6. If a prefilled item is wrong, the user edits only that field/line.
7. User certifies each job as either:
   - Certified Correct
   - Corrected & Certified
8. Any edit after certification automatically returns the record to Needs Review.
9. Exported JSON becomes the human-verified structured source used to create the revision patch.

Crew Equipment Move Notes
-------------------------
These are stored as structured data on each train line in `equipmentMoveCode`.

c = Unless otherwise directed, train will originate or terminate in Penn Station C Yard.
t = Unless otherwise directed, train will originate or terminate in GCM Tail Track.
v = Unless otherwise directed, train will originate or terminate in Flatbush Ave. VD Yard.
w = Unless otherwise directed, train will originate or terminate in J. D. Caemmerer West Side Yard.
y = Unless otherwise directed, train will originate or terminate in Jamaica Yard.

This structured field is intentionally separate from free-text notes so Crew Book Assistance and Time Slip Assistance can use the yard/origin/termination information programmatically later.

Mobile UX
---------
- Official source remains pinned while the form scrolls.
- Verification/certification controls scroll with the form, not the pinned source.
- Source image supports zoom, fit, scroll, and hide.
- Desktop/tablet becomes side-by-side automatically.

Structured data
---------------
- Regular crews
- Added crews
- Abolished crews
- Extra crews
- Relief crews
- Independent relief-day coverage
- Mon-Fri and Sat-Sun base assignments
- Ordered Train / Deadhead / Note movement lines
- Structured Crew Equipment Move Notes (c/t/v/w/y)
- Day/date-specific exceptions
- Footnotes and special date ranges
- Reviewer notes
- Local autosave
- JSON import/export
- Human certification metadata

The included Job 277 remains a working example of the hybrid verification workflow.

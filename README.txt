Engineer Pay Log — Crew Book Revision Verifier
FINAL HYBRID WORKFLOW CONCEPT

This standalone tool does not modify Engineer Pay Log.

Purpose
-------
Future Crew Book revisions use a hybrid assistant + human verification workflow.

1. User supplies the revision PDF/cover.
2. Revised / Added / Abolished crews are identified.
3. Source images/crops are attached to each job.
4. Assistant pre-fills every structured job record to the best of its ability.
5. User reviews EVERY job against the pinned official source image.
6. If prefilled data is wrong, user edits only the applicable field/line.
7. User certifies each job as:
   - Certified Correct
   - Corrected & Certified
8. Certified cards can be filtered separately.
9. If a certified record is edited later, it automatically returns to Needs Review.
10. JSON export includes:
   - complete structured assignments
   - certification state
   - certification timestamp
   - whether human corrections were made
   - revision-wide certification summary
11. The returned fully certified JSON is treated as the human-verified structured source for creating the app revision patch.

Mobile design
-------------
- Source image remains pinned while the form scrolls.
- Verification controls are NOT part of the pinned source area.
- Source can be zoomed, scrolled, fit, or hidden.
- Desktop/tablet becomes side-by-side automatically.

Structured assignment support
-----------------------------
- Regular crews
- Added crews
- Abolished crews
- Extra crews
- Relief crews
- Two independent relief days and covering job/Extra Crew
- Mon-Fri and Sat-Sun base assignments
- Ordered Train / Deadhead / Note movement lines
- Day/date-specific exceptions
- Footnotes and special date ranges
- Reviewer notes
- Local autosave
- JSON import/export

The included Job 277 is prefilled as a working demonstration of the hybrid verification workflow.

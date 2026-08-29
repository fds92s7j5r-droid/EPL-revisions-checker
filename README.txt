Engineer Pay Log — Crew Book Revision Builder (Keeper Concept)

Standalone tool. Does not modify Engineer Pay Log.

Purpose:
A reusable mobile-first workflow for future Crew Book revisions.

Finalized design principles:
1. User transcribes the COMPLETE new assignment. The user is not responsible for identifying every difference.
2. Each revised job can have its scanned Crew Book assignment pinned on screen while the form scrolls.
3. Source viewer is collapsible and zoomable. On desktop/tablet it becomes side-by-side automatically.
4. Regular crews include:
   - terminal/location
   - pays meal period
   - BOTH relief days
   - each relief day covered by Extra Crew or a specific job number
   - Mon–Fri base report/release
   - Sat–Sun base report/release
   - ordered line-by-line movement builder
   - day/date-specific exceptions
   - footnotes/date restrictions
   - notes for reviewer
5. Movement builder:
   - Train
   - Deadhead
   - Note
   - reordering supported
6. Dedicated Extra Crew form.
7. Dedicated Relief Crew Monday–Sunday table.
8. Verification checklist travels with each job:
   - Report
   - Relief coverage
   - Mon–Fri lines
   - Sat–Sun lines
   - Exceptions
   - Footnotes
9. Autosaves locally.
10. JSON export/import allows stopping and resuming, including on another device/browser.

This demo includes an actual cropped source image for Job 277 from the Sept. 8, 2026 GO 202 Crew Book so the pinned-source workflow can be tested on a phone.

Future revision workflow:
- Supply new revision PDF/cover.
- Revised/added/abolished crews are identified from the revision notice.
- Source crops are prepared and attached to their job cards.
- User transcribes/verifies each job while viewing its pinned source.
- User exports JSON progress or final handoff.
- Finished JSON is independently verified against the same official source before an app patch is produced.

ENGINEER PAY LOG — GO 201 REVISION 6 EXCEPTION RE-CERTIFICATION VERIFIER
Generated 2026-08-29

Purpose
-------
This audit package is built from the production Crew Book Revision Verifier and the official GO 201 Revision 6 passenger Crew Book supplied by the user.

Scope
-----
56 standard passenger jobs currently containing custom Rev. 6 resolver logic in Engineer Pay Log.

The first 9 cards are explicit Friday-only source cases:
9, 12, 51, 134, 161, 200, 216, 293, 358.

Workflow
--------
1. Open index.html in the same way you normally test the Revision Verifier.
2. Open one card at a time.
3. Use the pinned official source page.
4. Verify report/release, relief coverage, weekday/weekend schedules, exceptions, footnotes/stars, AND train-number/day consistency.
5. The tool will not allow certification until every verification checkbox is checked.
6. Correct only fields that are wrong.
7. Use Certified Correct or Corrected & Certified.
8. Export JSON at any handoff point. Autosave remains local to the browser.

KNOWN DEFECT ALREADY PRE-CORRECTED
----------------------------------
Job 200:
- Mon-Thu report 4:20 PM, release 1:07 AM.
- Friday report 4:20 PM, release 12:25 AM.
The old app resolver had those release branches reversed.
The official page shows the starred "Friday Report Only" branch, and Train 2804 is a weekday train.

Important
---------
This verifier does NOT modify production Engineer Pay Log. The exported JSON becomes the human-certified source for the Rev. 6 correction patch.

Source pages
------------
Each job card is linked to a rendered image of the official source page from the supplied 470-page Crew Book.

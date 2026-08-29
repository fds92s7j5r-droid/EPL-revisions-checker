Engineer Pay Log — Crew Book Revision Builder Prototype 3

Standalone prototype. It does NOT modify Engineer Pay Log.

Prototype 3 adds the Time-Slip-style movement builder requested during mobile testing.

Workflow:
- Enter the complete revised assignment rather than manually identifying changes.
- Regular crews retain:
  * terminal/location
  * meal-period status
  * both relief days
  * each relief day covered by Extra Crew or a specific job number
  * separate Mon–Fri and Sat–Sun sections
  * base report/release
  * day-specific/date-specific exceptions
  * published footnotes
  * job-specific Notes for Review
- Each Mon–Fri and Sat–Sun section is now built one line at a time:
  * + Train
  * + Deadhead
  * + Note
- Train lines include:
  * train number
  * origin
  * departure
  * destination
  * arrival
  * optional line note
- Deadhead lines include:
  * from/to
  * optional start/end time
  * optional note
- Lines can be reordered with up/down buttons or removed.
- Extra Crews use the same ordered movement builder.
- Relief Crews retain a Mon–Sun table.
- Local autosave remains enabled.
- JSON Export and JSON Import allow stopping and resuming later or on another device/browser.
- Automatic comparison remains available against the prior verified revision when loaded.

Demo sample cards:
- Regular Crew 277
- Added Regular Crew 203
- Extra Crew 61
- Relief Crew 474
- Abolished Crew 18

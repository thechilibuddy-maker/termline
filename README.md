# Termline

A free, standalone browser tool for building a workload-weighted assignment schedule for any course, in any subject. No login, no account, no data storage. Everything runs in your browser.

## What it does

Termline takes a course's assignment or module breakdown and turns it into a schedule of due dates, weighted by how much work each assignment actually involves.

You give it:

- A start date and a target finish date
- Each assignment or module, with a topic or unit count
- Any dates already submitted
- Any blackout periods (holidays, travel, or other stretches with no work expected)

It works out:

- A pace baseline from work you have already submitted, in usable days per topic
- How many usable weekdays remain before the deadline, once blackout periods and a buffer are subtracted
- A due date for each remaining assignment, weighted by its topic count against that pace
- A pacing risk flag on any assignment where its allotted pace falls meaningfully below your baseline

The result is a table of scheduled due dates plus a visual timeline (a ruler showing the term, blackout bands, and each assignment plotted by date).

## Subject-agnostic by design

Termline has no subject-specific logic built in. It only needs a course that breaks down into countable units per assignment, whether that is topics in a Geography module, lessons in a grammar workbook, or chapters in a literature unit. If you can say "this assignment covers N units of work," Termline can schedule it.

## How to use it

Open the tool in any modern browser. No installation required.

1. Enter the course name, start date, target finish date, and buffer (usable days reserved before the deadline).
2. Add any blackout periods.
3. Add each assignment: name, topic count, and a submitted date if it is already done.
4. Click "Build schedule."

Everything recalculates from what you have entered. If an assignment gets submitted early or late partway through the year, update its submitted date and rebuild, the remaining schedule adjusts automatically.

## Privacy

Termline runs entirely in your browser. Nothing you enter is sent to any external server, stored, or logged. Closing the tab clears everything.

## Licence

AGPL-3.0. You are free to use, adapt, and build on this tool. Any modified versions must be published under the same licence with changes disclosed.

## Built by

[Ly-ann Tan Low](https://www.linkedin.com/in/ly-ann-tan-902b6822/), founder of LitLens Studio. Singapore, 2026.

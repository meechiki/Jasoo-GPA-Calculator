# Jasoo GPA Calculator

A simple, unofficial tool for calculating GPA with per-subject credit weighting.
Built as a reference for students preparing scholarship applications (e.g. JASSO
and other Japan-bound programs), but usable by anyone who needs a weighted GPA.

**Note:** This is not an official JASSO tool or calculator. Always double-check
against your program's official announcement for the exact GPA scale and minimum
required.

## Usage

Open `jasso-gpa-calculator.html` in any browser — no install, no server needed.

1. Choose a grading scale from the dropdown:
   - Thai 4-level (A–F)
   - Thai 4-level with +/- grades
   - US / international 4.00 scale
   - Japanese 5-level (秀優良可不可)
2. Add a row for each subject with **+ เพิ่มวิชา**.
3. For each subject, enter the subject name, select its grade, and set its
   credit hours (defaults to 3, editable per row).
4. GPA updates automatically, weighted by credit hours across all subjects with
   both a grade and credit entered.

## What it does not do (yet)

- No bulk-paste input for grades (entry is row-by-row).
- No pass/fail threshold indicator against a specific minimum GPA.
- No export to PDF/print layout.

Let me know if you'd like any of these added.

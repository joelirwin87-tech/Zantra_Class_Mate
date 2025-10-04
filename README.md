Zantra Class Mate – User Guide

A lightweight classroom management tool that runs entirely offline in your browser.

1. Getting Started

Open the Zantra Class Mate.html file in Chrome, Edge, or Firefox.

All data is stored locally in your browser (IndexedDB). No internet or cloud account is required.

2. Interface Overview

Header: School logo, title, active class selector, export/backup buttons.

Navigation Tabs:

Overview – Class snapshot and attendance charts.

Students – Add, edit, and search student profiles.

Attendance – Record and review attendance.

Notes & Progress – Capture progress notes for students.

Reports & Settings – Performance summaries and school settings.

3. Classes

Select Active Class: Use the dropdown in the header.

Manage Classes: Click “Manage Classes” to add, rename, or delete classes.

At least one class must always exist. Classes with students/records cannot be deleted until emptied.

4. Students

Go to Students tab.

Add Student: Fill in form (ID, name, grade, DOB, email, guardian contact, notes). Required fields are Student ID and Name.

Search: Use the search bar to filter by any field.

Edit/Delete: Use the actions in the Student Directory table. Deleting removes linked notes and attendance.

5. Attendance

Go to Attendance tab.

Record Attendance: Select a date, mark each student as Present/Late/Absent, then save.

History: Previous sessions appear on the right with counts and details.

6. Notes & Progress

Go to Notes & Progress tab.

Add Note: Select a student, set category and progress status, and enter notes.

Filter Archive: View notes for all students or a single student.

Edit/Delete: Modify or remove notes using the archive panel.

7. Reports & Settings

Reports: Shows total sessions, average attendance, and notes logged. Charts display attendance distribution.

School Settings: Enter school name, teacher, academic year, brand color, and upload a logo.

Save changes to apply branding instantly.

8. Export & Backup

Export PDF: Generates a printable summary report.

Export CSV: Exports raw student and attendance data for spreadsheets.

Download Backup: Saves all data as JSON.

Restore Backup: Upload a JSON file to restore.

9. Notifications & Confirmations

All actions trigger toast notifications (success/error/info).

Deleting students, notes, or classes requires confirmation dialogs.

10. Data Storage

Data is saved in IndexedDB in your browser.

If IndexedDB is unavailable, it falls back to localStorage.

Data stays local to your computer. To transfer to another device, use Download Backup and Restore Backup.

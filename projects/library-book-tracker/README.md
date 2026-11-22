# Library Book Borrowing Tracker

## Overview
A library workflow that checks a Google Sheet for a requested book and student, then routes the request to the appropriate outcome and sends an email notification when a match cannot be found.

## Intended workflow
1. Receive a book title and student name.
2. Validate that both fields are present.
3. Search the library records for the requested book and student.
4. If the record matches and the book is available, continue the borrowing workflow.
5. If the book is not found, notify the librarian.
6. If the student or borrowing record does not match, send an appropriate alert.
7. Log the result for traceability.

## Potential technology
- n8n
- Google Sheets
- Gmail or another email provider

## Test cases
- [ ] Existing book and valid student
- [ ] Book not found
- [ ] Student not found
- [ ] Book exists but is unavailable
- [ ] Empty book title or student name
- [ ] Multiple matching rows
- [ ] Google Sheets or email service error

## Status
**In Progress / documentation starter.** Document the exact sheet columns and node mapping after the workflow is finalized.

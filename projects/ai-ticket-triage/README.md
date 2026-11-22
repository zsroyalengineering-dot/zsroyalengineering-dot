# AI Ticket Triage Agent

## Overview
An AI-assisted ticket workflow that classifies incoming support requests, selects an appropriate team or assignee, and updates ticket status according to defined rules.

## Intended workflow
1. Trigger when a new support ticket is created or received.
2. Extract the ticket title, description, team, and current status.
3. Classify the request (for example, technical support, product guidance, or business question).
4. Apply explicit assignment rules.
5. Update the ticket status and assignee in the ticketing platform.
6. Add a note or notify the relevant person when needed.
7. Handle uncertain classifications through a manual-review route.

## Potential technology
- Make.com
- Linear
- An LLM provider for classification

## Reliability checklist
- [ ] Test each ticket category
- [ ] Verify exact team and status names
- [ ] Confirm assignee mapping
- [ ] Handle missing or ambiguous ticket descriptions
- [ ] Prevent duplicate updates
- [ ] Log API failures and route them for review

## Status
**In Progress / documentation starter.** Keep assignment names and status values in configuration rather than hard-coding them in public documentation.

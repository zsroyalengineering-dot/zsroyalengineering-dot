# AI Lead Qualification & CRM Automation

## Overview
An AI-assisted workflow for analyzing incoming training or business inquiries, generating a summary, assigning a lead score, and routing the lead for follow-up.

## Intended workflow
1. Trigger when a new form response arrives.
2. Extract the lead's name, email, company, job title, budget, and message.
3. Ask an LLM for structured JSON containing a summary, intent, score (1–10), category, and recommended next action.
4. Validate the JSON and score range before routing.
5. Route high-, medium-, and low-priority leads according to documented business rules.
6. Log every processed lead and record failures for manual review.

## Potential technology
- Make.com
- Google Forms and Google Sheets
- Gemini or another configured LLM provider
- Slack or email for notifications

## Reliability checklist
- [ ] Validate required form fields
- [ ] Enforce score range 1–10
- [ ] Test high, medium, and low score boundaries
- [ ] Handle invalid JSON and model errors
- [ ] Add a fallback/manual-review route
- [ ] Prevent duplicate processing
- [ ] Log success and failure outcomes

## Security
Use platform-managed credentials. Do not publish real lead names, email addresses, form response IDs, or API keys.

## Status
**In Progress / documentation starter.** Replace this with Tested or Deployed only after verifying the complete scenario.

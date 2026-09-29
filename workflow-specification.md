# Workflow Specification

## Trigger
New customer inquiry received.

## Step 1 — Capture
Fields:
- Customer name
- Company
- Date
- Inquiry
- Account owner

## Step 2 — AI Analysis
Prompt:
"Review the customer inquiry below. Return:
1. A one-sentence summary
2. The customer's primary need
3. Desired outcome
4. Urgency: Low, Medium, or High
5. Sentiment: Positive, Neutral, Frustrated, or At Risk
6. Recommended next action
7. One follow-up question if additional information is needed.

Do not invent facts."

## Step 3 — Human Review
Customer Success professional reviews the AI analysis and edits anything necessary.

## Step 4 — Response Draft
Prompt:
"Using the approved analysis, draft a concise, empathetic customer response. Do not promise anything that has not been confirmed. Keep the tone helpful and professional."

## Step 5 — Follow-Up Task
Create:
- Owner
- Action
- Due date
- Priority
- Customer
- Expected outcome

## Step 6 — Outcome
Record:
- Resolved
- Follow-up required
- Escalated
- Customer training completed
- Customer feedback

## Success Measures
- Time to first response
- Time to resolution
- Follow-up completion rate
- Customer satisfaction
- Repeat issues

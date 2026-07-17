# AI Email Assistant Pro v1

## Overview

AI Email Assistant Pro is an intelligent email automation workflow built with n8n, OpenAI, Gmail, and Google Sheets.

It automatically receives incoming emails, analyzes them using AI, updates a CRM dashboard, and generates professional email replies.

---

## Features

- Gmail Trigger
- AI Email Classification
- Automatic Category Routing
- Priority Detection
- AI Summary Generation
- Lead Score (0–100)
- Estimated Deal Value
- Closing Probability
- Sentiment Analysis
- Recommended Action
- Status Tracking
- Google Sheets CRM
- AI Email Reply

---

## Tech Stack

- n8n
- OpenAI API
- Gmail API
- Google Sheets API
- JavaScript
- JSON

---

## Workflow

1. Gmail receives a new email.
2. AI classifies the email.
3. The workflow determines:
   - Category
   - Priority
   - Summary
   - Lead Score
   - Deal Value
   - Closing Probability
   - Sentiment
   - Recommended Action
   - Status
4. The information is stored in Google Sheets.
5. AI generates a professional reply.
6. Gmail sends the reply automatically.

---

## Example Output

- Category: New Lead
- Priority: High
- Lead Score: 92
- Deal Value: $3,000–$5,000
- Sentiment: Positive
- Recommended Action: Schedule a Call
- Status: New

---

## Future Improvements

## Future Improvements

- RAG knowledge base
- Telegram notifications
- CRM integration
- multi-language replies

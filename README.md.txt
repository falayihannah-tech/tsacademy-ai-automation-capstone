 AI-Powered Customer Feedback and Escalation System

 Project Overview
This capstone project focuses on automating customer feedback collection, sentiment analysis, complaint escalation, and feedback management for a multi-location car care and auto repair business.

The system is designed to collect feedback after completed jobs, assess the sentiment and severity of customer replies, check customer complaint history, and route feedback to the appropriate team or manager.

  Problem Statement
The business relies on inconsistent manual follow-ups, making it difficult to collect customer feedback promptly and identify serious complaints before they become public reviews.

 Project Objectives
- Automatically request feedback after a completed service.
- Analyse customer replies for sentiment, severity, and confidence.
- Check whether customers have previously submitted negative feedback.
- Save positive feedback in a human-reviewed, ready-to-post queue.
- Route negative feedback to a private queue.
- Escalate severe complaints and repeat negative feedback to a manager.
- Generate personalised draft responses for negative feedback.
- Provide a central dashboard with location-based filtering and alert tracking.
- Flag unclear or low-confidence feedback for human review.

Workflow Overview
1. A service job is marked complete.
2. The customer receives a feedback request.
3. The customer submits a reply.
4. AI analyses sentiment, severity, and confidence.
5. The system checks the customer's previous negative feedback history.
6. Feedback is routed to the appropriate queue or escalated.
7. Negative feedback receives an AI-generated draft response for human review.
8. Feedback, routing outcomes, responses, and alerts appear on a central dashboard.

Main Routing Rules
- Positive feedback:** Save for human review before public posting.
- First-time or lower-severity negative feedback:** Add to the private queue and generate a draft response.
- Severe negative feedback:** Alert a manager immediately and generate a draft response.
- Repeat negative feedback:** Escalate to a manager regardless of the current complaint's severity.
- Unclear or low-confidence feedback:** Flag for human review.

 Human Oversight
No public review is posted automatically, and no response is sent to a customer automatically. Team members review and approve all public content and customer response drafts.

 Tools and Technologies
To be completed after confirming the actual tools used in the n8n workflow.

  Testing and Results
The required demonstration scenarios are:
1. Positive feedback.
2. First-time negative feedback.
3. Repeat negative feedback.

The workflow should also be tested for severe complaints and unclear or low-confidence replies.

  Project Status
TS Academy AI Automation capstone. Portfolio documentation in progress.

 Assessment
Capstone score: 80/100.

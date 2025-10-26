# Day 1 – n8n Setup & Webhook→Slack Automation

## Overview
Built a working automation pipeline:
Google Forms / external inputs → n8n Webhook → Slack Notifications

## Workflow Details
- **Trigger:** Webhook (`POST /webhook/slack-test`)
- **Transform:** Set Node (formats data with expressions)
- **Action:** HTTP Request (Slack Incoming Webhook)

## Example Output
    New Lead Received:
    Name: Varun
    Email: varun@example.com
    Message: Running full test before export!


## Files
- `day1_webhook_slack.json`
- `day1_canvas.png`
- `day1_execution_success.png`
- `day1_slack_output.png`
# Anonymous Feedback System

A simple and automated web-based system that allows students to submit anonymous feedback to staff.

The system uses **n8n automation** to process submitted feedback, filter inappropriate content, and send valid feedback directly to the concerned staff member through email.

## Features

* Anonymous student feedback submission
* Staff-wise feedback routing
* Automatic inappropriate-word filtering
* Automated email notification
* Simple and user-friendly interface
* n8n workflow automation
* No need for manual feedback forwarding

## Workflow
Student
   ↓
Feedback Form
   ↓
n8n Webhook
   ↓
Content Validation
   ↓
Bad-Word Filtering
   ↓
Staff Email
   ↓
Feedback Received

## Technologies Used

* HTML
* CSS
* JavaScript
* n8n
* Webhooks
* Email Automation

## How It Works

1. The student opens the feedback system.
2. The student selects the required staff/subject and submits feedback anonymously.
3. The feedback is sent to an **n8n webhook**.
4. n8n checks the submitted feedback for inappropriate words.
5. Valid feedback is automatically forwarded to the respective staff member through email.
6. Inappropriate feedback is rejected instead of being forwarded.


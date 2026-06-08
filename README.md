# Whatsapp_reminder_automation_n8n

Problem Statement

Many teams forget to:

Check in 
Check out at the end of the day
Attend scheduled meetings

Manual reminders waste time and require constant follow-up.
This project automates reminders using WhatsApp groups and AI-generated messages.

Solution

Built an automated notification system using n8n that:

Reads schedules from Google Sheets
Calculates reminder timings automatically
Generates professional reminder messages using AI
Sends reminders to WhatsApp groups using WAHA
Runs completely automatically using scheduled workflows

Architecture:

Schedule Trigger
        ->
Google Sheets
        ->
IF Condition
        ->
AI Agent
        ->
WAHA API
        ->
WhatsApp Group

Features:

Check-In Reminder
Sends automated check-in reminders.

Check-Out Reminder
Sends automated check-out reminders.

Meeting Reminder
Automatically sends reminders before meeting time.

Daily AI Insight
Shares AI news and insights with teams.

Dynamic Scheduling
Reminder timing is controlled from Google Sheets.

Technologies Used:

Technology	    |     Purpose
n8n	Workflow    |   Automation
Docker	        |   Deployment
WAHA API	      |   WhatsApp Messaging
Google Sheets	  |   Data Storage
Azure OpenAI	  |   AI Message Generation

Workflow Types:

Workflow 1
Check-In Reminder

Workflow 2
Check-Out Reminder

Workflow 3
Meeting Reminder

Workflow 4
Daily AI Insight

Learning Outcomes

Through building this project, I gained hands-on experience with:

Workflow Automation
Designing end-to-end automation workflows using n8n
Trigger-based and scheduled execution

API Integration
Integrating WAHA API with n8n
Handling authentication and API requests

Docker
Running and managing Docker containers
Debugging container and networking issues

WhatsApp Automation
Sending automated group notifications
Managing WhatsApp sessions through WAHA

Google Sheets Integration
Using Google Sheets as a lightweight database
Reading and processing dynamic schedule data

AI Integration
Generating dynamic reminder messages using Azure OpenAI
Prompt engineering for structured outputs

Problem Solving
Debugging workflow execution issues
Handling scheduling logic for meeting reminders
Working with loops, conditions, and data transformations

Setup Instructions: 
Install Docker
Deploy WAHA
Import workflow JSON into n8n
Configure Google Sheets credentials
Configure Azure OpenAI credentials
Add WAHA API key
Activate workflow

Author:

Nomika 
B.Tech Computer Science Student

Interests:
AI
Automation
Machine Learning
Workflow Engineering
Agentic Systems

# CAPSTONE 32 — AI Email Triage and Reply Draft Workflow

## Project Overview

The AI Email Triage and Reply Draft Workflow is an automation project designed to classify incoming emails, identify their priority, recommend suitable actions, and generate draft replies using AI.

The main objective is to evaluate whether AI can help manage emails efficiently while reducing the risk of incorrect replies and exposing sensitive information.

## Problem Statement

Handling emails manually can be time-consuming. Important messages may be overlooked, and replying without proper verification can lead to inaccurate or unsafe communication.

This project explores how AI-assisted email classification and reply drafting can improve email management while keeping humans responsible for reviewing replies.

## Objectives

- Automatically capture incoming test emails.
- Classify emails into appropriate categories.
- Identify email priority.
- Recommend the next action.
- Generate draft replies.
- Verify drafts for tone, factual accuracy, and safety.
- Compare manual email handling time with AI-assisted handling time.
- Follow responsible AI and privacy practices.

## Tools Used

- **Gmail:** Test email source.
- **Google Sheets:** Email dataset, rules, prompts, time analysis, and privacy documentation.
- **Zapier:** Workflow automation.
- **AI by Zapier:** Email classification and reply draft generation.
- **ChatGPT:** Project planning, prompt development, and documentation support.
- **GitHub:** Project documentation and version sharing.

## Workflow

1. A fictional test email arrives in the Gmail test mailbox.
2. Zapier detects the incoming email.
3. Email details are added to Google Sheets.
4. AI analyses the email and generates a category, priority, recommended action, safety rule, and reply draft.
5. The workflow updates the corresponding spreadsheet row.
6. A human reviews the classification and draft before any reply is sent.

## Spreadsheet Structure

The workbook contains five tabs:

1. **Email Inbox:** Fictional emails, AI outputs, and human-review fields.
2. **Rules:** Email classification and priority guidelines.
3. **Prompt Library:** Prompts used for AI processing.
4. **Time Analysis:** Manual and AI-assisted handling time.
5. **Privacy Rules:** Data protection and responsible AI guidelines.

## Safety and Privacy

- Only fictional or synthetic test emails should be used.
- Real confidential emails must not be processed.
- Suspicious links and attachments must not be opened.
- AI-generated content must be reviewed by a human.
- Replies must not be sent automatically without human approval.
- Passwords, API keys, and private account information must not be published.

## Evaluation

The workflow will be evaluated using email classification accuracy, priority assignment, reply quality, safety checks, and measured handling time.

Actual performance results will be reported after testing and human verification.

## Limitations

AI may misclassify emails, misunderstand context, or generate unsupported information. Human review remains necessary, especially for financial, security-related, and sensitive messages.

## Conclusion

This project demonstrates an AI-assisted email management workflow that combines automation with human oversight. It aims to improve productivity while maintaining accuracy, privacy, and responsible AI use.

## Project Status

The Gmail-to-Google-Sheets automation has been tested. Further verification, actual time measurements, and final evaluation should be documented as testing is completed.
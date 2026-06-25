# AI-Powered Daily News Curator 📰

An automated system built with **n8n** that curates, summarizes, and emails tech news to your inbox.

## Tech Stack
*   **n8n**: Workflow automation.
*   **Groq (Llama-3)**: AI model for intelligent summarization.
*   **Gmail API**: For automated email delivery.

## Features
*   **Automated RSS Fetching**: Fetches the latest updates from Reuters and other tech sources.
*   **Scheduled Delivery**: The workflow is scheduled to automatically run every morning at 8:00 AM PKT, ensuring your news is ready for your morning routine.
*   **AI Summarization**: Generates clean, professional summaries using Groq.
*   **HTML Email Delivery**: Delivers formatted newsletters directly to Gmail.

## Setup Instructions
1.  Import the `workflow.json` file into your n8n instance.
2.  Configure your **Gmail** and **Groq** credentials in the nodes.
3.  Activate the workflow to start receiving daily updates.

## Workflow Overview

<img width="1446" height="716" alt="ai-newsletter-curator" src="https://github.com/user-attachments/assets/86bbe277-1a69-41c3-9c3c-294c56b89fe5" />
<img width="1641" height="852" alt="ai-newsletter-curatorr" src="https://github.com/user-attachments/assets/da7ac664-6884-4edd-8072-0383d38a7fba" />



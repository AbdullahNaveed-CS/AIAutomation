# Healthcare & Clinical AI Automation

Automated patient intake, neurological assessment logging, and clinical appointment scheduling built with **n8n**.

## Included Workflows
* **`BrainGuard AI — Patient Assessment Records.json`:** Automates neurological patient screening intake, structures diagnostic assessment records, and logs patient metrics for clinical review.
* **`Doctor's appointment agent real.json`:** Conversational AI scheduling agent that checks clinic availability, books patient appointments, and sends automated confirmations.
* **`Doctor's appointment agent.json`:** Core appointment routing prototype.

## Setup
1. Import the `.json` file into n8n (**Workflows → Import from File**).
2. Connect your LLM provider (OpenAI / Gemini), Google Calendar, and database/Sheets credentials.

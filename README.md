# AI Content Repurposing Engine

An AI-powered content automation workflow built with n8n and Google Gemini.

The workflow takes a topic or rough draft, generates platform-specific content for LinkedIn and X, transforms the AI output using JavaScript, routes the content based on platform, and stores the results automatically in Google Sheets.

## Workflow

Manual Trigger
↓
AI Agent (Google Gemini)
↓
JavaScript Data Transformation
↓
Switch (Platform Routing)
↓
Google Sheets

## Features

- Generates LinkedIn posts using Google Gemini
- Generates concise X posts
- Uses JavaScript to transform AI output into structured data
- Routes content based on platform
- Stores generated content in Google Sheets
- Uses OAuth 2.0 for Google Sheets integration

## Technologies

- n8n
- Google Gemini
- JavaScript
- Google Sheets
- OAuth 2.0

## Example

### Input

AI automation using n8n to connect different applications and automate repetitive business tasks.

### Output

The workflow generates:

- A professional LinkedIn post
- A concise X post

Both outputs are automatically stored in Google Sheets.

## What I Learned

Through this project, I gained hands-on experience with:

- AI workflow automation
- API and application integration
- Data transformation using JavaScript
- Conditional routing
- Google Sheets integration
- OAuth 2.0 authentication
- Building automated data pipelines with n8n

## Project Structure

```text
ai-content-repurposing-engine/
├── README.md
├── ai-content-repurposing-engine.json
└── screenshots/
    ├── workflow.png
    └── google-sheets-output.png

## Demo

The workflow can be executed manually in n8n. It generates the content and stores the results automatically in Google Sheets.

## Author

Aashika Sheik

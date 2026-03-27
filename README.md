# n8n Workflows

A collection of my automation workflows built with n8n.

## Infographic Generator
This workflow takes a YouTube URL, scrapes the transcript using Apify, summarizes the content with GPT-4o-mini, and generates a sketchnote-style infographic using DALL-E 3.

### Setup
1. Import the `.json` file into n8n.
2. Configure your credentials for:
   - **Apify:** (Query Auth with `token` key)
   - **OpenAI:** (Official OpenAI node)

# AI-Powered CV and Job Match Automation

This project is a low-code automation workflow built with [n8n](https://n8n.io/), integrated with OpenAI's ChatGPT, Notion, and Google Docs. It helps automate the process of matching job descriptions with resumes and generating improved resume suggestions.

## Features

- Compares job descriptions with your resume using ChatGPT
- Returns a match percentage and improvement tips
- Updates Notion databases with results
- Creates and stores resume drafts in Google Docs
- Manages flows using n8n's visual workflow editor

## Stack

- n8n (self-hosted)
- OpenAI GPT-4 API
- Notion API
- Google Docs API

## Getting Started

1. Clone this repository:

	git clone https://github.com/yuladp1/n8n-CV-builder.git
	cd n8n-CV-builder

2. In your local n8n, go to **Credentials** and connect:
   - OpenAI API key
   - Google account (for Google Docs)
   - Notion integration (token and database ID)
3. Import the workflow `.json` file into your local n8n instance.
4. Run n8n locally via Docker or in your environment.

## License

MIT

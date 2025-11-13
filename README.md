# n8n-automation-projects
Collection of automation projects for personal use and client

# YouTube Transcription Workflow (n8n + OpenAI Whisper)

This workflow automates YouTube video transcription using **n8n**, **OpenAI Whisper API**, and **Google Docs**.

## Features
- Download audio from YouTube
- Chunk audio for large files
- Transcribe with Whisper API
- Combine all text and save to Google Docs
- (Optional) Extract YouTube comments into a separate document

## Tools & APIs
- n8n (workflow automation)
- OpenAI API (Whisper for transcription)
- Google Drive API
- YouTube Data API

## Files
| File | Description |
|------|--------------|
| `YouTube_Transcription_Workflow.json` | Import this workflow into n8n |
| `YouTube_Transcription_Documentation.docx` | Full setup guide and explanation |

## Usage
1. Import the `.json` file into your n8n instance.
2. Add your OpenAI and Google API credentials.
3. Adjust Google Drive folder and file names.
4. Run the workflow!

👨‍💻 **Created by:** Mark Rellama  

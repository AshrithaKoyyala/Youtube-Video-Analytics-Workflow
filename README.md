# Youtube-Video-Analytics-Workflow(n8n)

This project demonstrates an automated n8n workflow that processes YouTube videos for content analysis.

## What this workflow does
- Accepts a YouTube video URL
- Fetches the transcript using an external API
- Uses AI to summarize the content
- Identifies important video sections with timestamps
- Iterates through segments to prepare data for clip generation

## What worked
- Transcript extraction for supported URLs
- AI-based summarization
- Clip timestamp detection
- End-to-end analysis pipeline

## What did not fully work
- Clip generation using the no-code-architects-toolkit
- Issues were related to FFmpeg processing and missing cloud storage configuration

## Key learnings
- Handling real API limitations and rate limits
- Debugging FFmpeg and media pipelines
- Understanding production-level workflow failures
- Structuring AI output for automation

## Tech stack
- n8n
- HTTP APIs
- JavaScript (data processing)
- AI tools for summarization

## Status
This project is functional for transcript and analysis stages and is ready for further extension.


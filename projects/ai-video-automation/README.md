# AI Video Generation Automation

## Overview
An automation workflow concept for coordinating AI-assisted script generation and media production, including image, video, and voice assets.

## Intended workflow
1. Accept a topic or content brief.
2. Generate a structured script and scene prompts.
3. Split the script into timed scenes or clips.
4. Generate or retrieve visual assets.
5. Generate narration using a configured text-to-speech service.
6. Submit video-generation tasks and poll for completion.
7. Merge audio and video when supported by the selected service.
8. Save final assets to cloud storage and report the result.

## Potential technology
- n8n
- Google Gemini for script and prompt generation
- Kling or another video-generation API
- ElevenLabs or another text-to-speech service
- Google Drive for storage
- A media-processing API for merging assets

## Reliability checklist
- [ ] Validate prompt and clip duration limits
- [ ] Check uploaded asset URLs before submission
- [ ] Handle asynchronous task polling and timeouts
- [ ] Validate binary audio/video outputs
- [ ] Handle failed generation and merge tasks
- [ ] Confirm final file is saved and accessible

## Status
**In Progress / documentation starter.** Keep provider names and configuration aligned with the services actually used in the final workflow.

# Feature: Bidirectional Text Transfer

**Product:** [AI Terminal](../product-vision--ai-terminal.md)

## Description
Allows the technical user to highlight text in either the terminal window and copy it to the clipboard and immediately paste it into the open AI chat input field and submit it for AI analysis — or highlight text like a command in the AI chat result and copy it to the clipboard and immediately paste it into the open terminal session prompt and submit it so the terminal can run the command.

## Target Users
- Technical User — can highlight text and immediately send it from the AI chat to the terminal prompt (to run a command), or from the terminal to the AI chat input (for analysis), and submit it quickly

## Pains & Gains Addressed
*Ordered by priority. Drawn from product vision personas.*

1. Speed up sending highlighted command advice from the AI chat into the terminal prompt and submitting it
2. Speed up sending highlighted terminal results into the AI chat input and submitting it for analysis

## Acceptance Criteria

### Intended Outcomes
- The technical user can quickly send commands from the AI chat into the open terminal session and submit it to make system changes
- The technical user can quickly send results from the terminal session into the open AI chat input and submit it for AI analysis

### Service Boundaries
**In scope**
- Sending highlighted text in the terminal session to the clipboard
- Sending highlighted text in the AI chat session to the clipboard
- Pasting text from the clipboard into the terminal prompt
- Pasting text from the clipboard into the AI chat form input field after locating it
- Submitting the AI chat form automatically
- Submitting the terminal prompt command automatically

**Out of scope**
- Altering traditional copy and paste behavior — standard copy/paste should remain unchanged; this feature only automates additional uses of it

### Functional Expectations
- Provide traditional menus to "run" text highlighted in the focused terminal session using the automation behavior
- Provide traditional menus to "run" text highlighted in the focused AI chat session using the automation behavior
- Provide right-click context menus to "run" text highlighted in the focused terminal session using the automation behavior
- Provide right-click context menus to "run" text highlighted in the focused AI chat session using the automation behavior

### Non-Functional Expectations
- None identified

## Stories
*Populated after feature-stories are defined. Ordered by delivery priority.*

1. [Send Highlighted Text from the AI Chat to the Terminal Prompt and Submit It](feature--ai-terminal--bidirectional-text-transfer/story--send-highlighted-text-from-the-AI-chat-to-the-terminal-prompt-and-submit-it.md)
2. [Send Highlighted Text from a Terminal Session to the AI Chat Input and Submit It](feature--ai-terminal--bidirectional-text-transfer/story--send-highlighted-text-from-a-terminal-session-to-the-AI-chat-input-and-submit-it.md)

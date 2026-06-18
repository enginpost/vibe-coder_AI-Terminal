# Feature: AI Chat Management

**Product:** [AI Terminal](../product-vision--ai-terminal.md)

## Description
Allows the technical user to set up one or more AI chat integrations and open them — individually or simultaneously — within the application.

## Target Users
- Technical User — can configure one or more AI chat sessions, set a default chat to open front-and-center at launch, and set additional chats to open concurrently at startup

## Pains & Gains Addressed
*Ordered by priority. Drawn from product vision personas.*

1. Easily consult with one or more AI in a chat format
2. Speed up highlighting and copying text from within active chat sessions
3. Speed up identifying the chat input prompt in the UI for pasting from the clipboard

## Acceptance Criteria

### Intended Outcomes
- The technical user can add AIs configured for the app
- The technical user can remove AIs configured for the app
- The technical user can open an AI that is configured but not yet open, and cannot open multiple sessions with the same AI
- The technical user can open multiple AI sessions concurrently in the UI as long as they are not the same AI
- The technical user can denote a single AI as the default that opens when the app starts
- The technical user can help the app determine the input form field in the AI session UI so the app can know where to paste results from the clipboard
- The technical user can highlight text and commands recommended by the AI session for copying to the clipboard

### Service Boundaries
**In scope**
- Managing AI chat configuration URLs (adding and removing)
- Managing AI chat default selection
- Managing AI chat session UI form input field finding criteria
- Managing presentation of one or more concurrent AI chat sessions in the UI

**Out of scope**
- Opening multiple AIs automatically when the app starts (only the default opens at launch)
- Using APIs for chat directly — the feature should use existing chat URLs only
- Hardcoding chat AI session input form IDs — the app should find them based on other search criteria, as web UI IDs can change

### Functional Expectations
- Provide menus for managing AIs (add, remove, and set as default)
- Provide menus for opening AIs that are not already open
- Provide right-click context menus for copy and paste within the AI chat session
- UI elements that let the user close a specific open chat session

### Non-Functional Expectations
- None identified

## Stories
*Populated after feature-stories are defined. Ordered by delivery priority.*

1. [Add an AI Chat Configuration](feature--ai-terminal--ai-chat-management/story--add-an-AI-chat-configuration-to-the-app.md)
2. [Remove an AI Chat Configuration](feature--ai-terminal--ai-chat-management/story--remove-an-AI-chat-configuration-from-the-app.md)
3. [Open a Configured AI Chat Session](feature--ai-terminal--ai-chat-management/story--open-a-configured-AI-chat-session.md)
4. [Run Concurrent Chat Sessions with Multiple Different AIs](feature--ai-terminal--ai-chat-management/story--run-concurrent-chat-sessions-with-multiple-different-AIs.md)
5. [Set a Default AI Chat that Opens at App Launch](feature--ai-terminal--ai-chat-management/story--set-a-default-AI-chat-that-opens-at-app-launch.md)
6. [Define the Chat Input Field Locator](feature--ai-terminal--ai-chat-management/story--define-how-the-app-identifies-the-input-field-in-an-AI-chat-session.md)
7. [Highlight and Copy Text from an AI Chat Session](feature--ai-terminal--ai-chat-management/story--highlight-and-copy-text-from-an-AI-chat-session.md)
8. [Save Content Shared by an AI in a Chat Session](feature--ai-terminal--ai-chat-management/story--save-content-shared-by-an-AI-in-a-chat-session.md)

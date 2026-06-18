# Story: Open a Configured AI Chat Session

**Statement:** As a technical user, I need to open a configured AI chat session, so that I can start consulting with it as an active singleton session.

**Parent Feature:** [AI Chat Management](../../feature--ai-terminal--ai-chat-management.md)

## Story Title
open a configured AI chat session

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Add an AI Chat Configuration](story--add-an-AI-chat-configuration-to-the-app.md) — at least one AI configuration must exist before a session can be opened.

## Successor Stories
*Stories that depend on this story's outcome.*

- [Define the Chat Input Field Locator](story--define-how-the-app-identifies-the-input-field-in-an-AI-chat-session.md) — a session must be open before the input field locator can be defined.
- [Highlight and Copy Text from an AI Chat Session](story--highlight-and-copy-text-from-an-AI-chat-session.md) — a session must be open before text can be highlighted and copied.
- [Save Content Shared by an AI in a Chat Session](story--save-content-shared-by-an-AI-in-a-chat-session.md) — a session must be open before content can be saved.
- [Send Highlighted Text from the AI Chat to the Terminal Prompt and Submit It](../feature--ai-terminal--bidirectional-text-transfer/story--send-highlighted-text-from-the-AI-chat-to-the-terminal-prompt-and-submit-it.md) — an AI chat session must be open before text can be highlighted from it.
- [Send Highlighted Text from a Terminal Session to the AI Chat Input and Submit It](../feature--ai-terminal--bidirectional-text-transfer/story--send-highlighted-text-from-a-terminal-session-to-the-AI-chat-input-and-submit-it.md) — an AI chat session must be open to receive and submit the highlighted text.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN the technical user has opened the app and at least one AI chat configuration exists and that AI is not currently open, WHEN the technical user selects the AI to open a session, THEN a new AI chat session is presented within the app.
- GIVEN the technical user has opened the app and at least one AI chat configuration exists and that AI is currently open, WHEN the technical user selects the AI to open a session, THEN the existing session is brought into focus rather than opening a duplicate.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V1 - AI Chat Management](../../../epics/epic--ai-terminal--v1-ai-chat-management.md)

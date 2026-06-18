# Story: Highlight and Copy Text from an AI Chat Session

**Statement:** As a technical user, I need to highlight and copy text recommended by an AI, so that I can quickly capture commands or content without manual selection.

**Parent Feature:** [AI Chat Management](../../feature--ai-terminal--ai-chat-management.md)

## Story Title
highlight and copy text from an AI chat session

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open a Configured AI Chat Session](story--open-a-configured-AI-chat-session.md) — a session must be open before text can be highlighted and copied.

## Successor Stories
*Stories that depend on this story's outcome.*

- [Paste a Command from the Clipboard into the Active Terminal Prompt](../feature--ai-terminal--terminal-session-management/story--paste-a-command-from-the-clipboard-into-the-active-terminal-prompt.md) — text must have been copied to the clipboard before it can be pasted into a terminal prompt.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN an AI chat session is open and the AI displays text, WHEN the technical user highlights the text and selects the option to copy, THEN the selected text is placed on the clipboard.
- GIVEN an AI chat session is open, WHEN the technical user selects the option to copy without having highlighted any text, THEN nothing is copied to the clipboard.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V1 - AI Chat Management](../../../epics/epic--ai-terminal--v1-ai-chat-management.md)

# Story: Paste a Command from the Clipboard into the Active Terminal Prompt

**Statement:** As a technical user, I need to paste a command from the clipboard into the active terminal prompt, so I can submit it to quickly run commands I've copied from elsewhere.

**Parent Feature:** [Terminal Session Management](../../feature--ai-terminal--terminal-session-management.md)

## Story Title
Paste a command from the clipboard into the active terminal prompt

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open One or More Terminal Sessions](story--open-one-or-more-terminal-sessions.md) — a terminal session must be open before a command can be pasted into its prompt.
- [Highlight and Copy Text from an AI Chat Session](../feature--ai-terminal--ai-chat-management/story--highlight-and-copy-text-from-an-AI-chat-session.md) — text must have been copied to the clipboard before it can be pasted.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN a terminal session is open and there is a command on the clipboard, WHEN the technical user pastes into the terminal prompt, THEN the command appears in the terminal prompt ready to be submitted.
- GIVEN a terminal session is open and the clipboard is empty, WHEN the technical user pastes into the terminal prompt, THEN nothing is added to the terminal prompt.
- GIVEN a terminal session is open and there is a command on the clipboard and the terminal prompt already contains text, WHEN the technical user pastes into the terminal prompt, THEN the app warns the technical user that the existing prompt text will be replaced and allows them to confirm or cancel before any replacement occurs.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V2 - Terminal Management](../../../epics/epic--ai-terminal--v2-terminal-management.md)

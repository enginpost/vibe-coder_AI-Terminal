# Story: Open One or More Terminal Sessions

**Statement:** As a technical user, I need to open one or more terminal sessions, so that I can run commands across different contexts simultaneously.

**Parent Feature:** [Terminal Session Management](../../feature--ai-terminal--terminal-session-management.md)

## Story Title
Open one or more terminal sessions

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

> None identified.

## Successor Stories
*Stories that depend on this story's outcome.*

- [Close an Existing Terminal Session](story--close-an-existing-terminal-session.md) — a session must exist before one can be closed.
- [Label an Open Terminal Session](story--label-an-open-terminal-session.md) — a session must be open before it can be labelled.
- [Paste a Command from the Clipboard into the Active Terminal Prompt](story--paste-a-command-from-the-clipboard-into-the-active-terminal-prompt.md) — a terminal session must be open before a command can be pasted into its prompt.
- [Highlight Text from a Terminal Session to Save a Copy](story--highlight-text-from-a-terminal-session-to-save-a-copy.md) — a terminal session must be open before text can be highlighted from it.
- [Highlight and Copy Text from a Terminal Session](story--highlight-and-copy-text-from-a-terminal-session.md) — a terminal session must be open before text can be highlighted and copied from it.
- [Send Highlighted Text from the AI Chat to the Terminal Prompt and Submit It](../feature--ai-terminal--bidirectional-text-transfer/story--send-highlighted-text-from-the-AI-chat-to-the-terminal-prompt-and-submit-it.md) — a terminal session must be open before text can be sent to its prompt.
- [Send Highlighted Text from a Terminal Session to the AI Chat Input and Submit It](../feature--ai-terminal--bidirectional-text-transfer/story--send-highlighted-text-from-a-terminal-session-to-the-AI-chat-input-and-submit-it.md) — a terminal session must be open before text can be highlighted from it.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN zero or more terminal sessions are open, WHEN the technical user opens a new terminal session, THEN a new terminal session is presented within the app alongside any other open sessions.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V2 - Terminal Management](../../../epics/epic--ai-terminal--v2-terminal-management.md)

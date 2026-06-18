# Story: Send Highlighted Text from a Terminal Session to the AI Chat Input and Submit It

**Statement:** As a technical user, I need to send highlighted text from a terminal session to the AI chat input and submit it, so that I can quickly get AI analysis of terminal results without manually copying-pasting-submitting.

**Parent Feature:** [Bidirectional Text Transfer](../../feature--ai-terminal--bidirectional-text-transfer.md)

## Story Title
Send highlighted text from a terminal session to the AI chat input and submit it

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open a Configured AI Chat Session](../feature--ai-terminal--ai-chat-management/story--open-a-configured-AI-chat-session.md) — an AI chat session must be open to receive and submit the highlighted text.
- [Open One or More Terminal Sessions](../feature--ai-terminal--terminal-session-management/story--open-one-or-more-terminal-sessions.md) — a terminal session must be open before text can be highlighted from it.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN at least one terminal session is open with text highlighted and in focus, and at least one AI chat session is open and selected as the destination, WHEN the technical user selects the option to run the highlighted text, THEN the highlighted text is sent to the destination AI chat input and automatically submitted.
- GIVEN at least one terminal session is open with text highlighted and in focus, and no AI chat sessions are open, WHEN the technical user selects the option to run the highlighted text and confirms opening a new specific configured AI chat session from a list of configured AI Chats, THEN the selected AI chat is opened in a new session and the highlighted text is sent to its input and automatically submitted once the session is available.
- GIVEN at least one terminal session is open with text highlighted and in focus, and no AI chat sessions are open, WHEN the technical user selects the option to run the highlighted text and cancels selecting a configured AI chat session, THEN no AI chat session is opened and nothing is submitted.
- GIVEN at least one terminal session is open and in focus with no text highlighted, and zero or more AI chat sessions are open, WHEN the technical user selects the option to run the highlighted text, THEN nothing is sent to an AI chat session and the app informs the technical user that text must be selected in the focused terminal session.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V3 - Command Runner](../../../epics/epic--ai-terminal--v3-command-runner.md)

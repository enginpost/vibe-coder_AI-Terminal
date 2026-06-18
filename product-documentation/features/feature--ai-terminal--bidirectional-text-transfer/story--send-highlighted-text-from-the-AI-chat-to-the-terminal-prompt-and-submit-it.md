# Story: Send Highlighted Text from the AI Chat to the Terminal Prompt and Submit It

**Statement:** As a technical user, I need to send highlighted text from the AI chat to the terminal prompt and submit it, so that I can quickly run command advice from the AI without manually copying-pasting-submitting.

**Parent Feature:** [Bidirectional Text Transfer](../../feature--ai-terminal--bidirectional-text-transfer.md)

## Story Title
Send highlighted text from the AI chat to the terminal prompt and submit it

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open a Configured AI Chat Session](../feature--ai-terminal--ai-chat-management/story--open-a-configured-AI-chat-session.md) — an AI chat session must be open before text can be highlighted from it.
- [Open One or More Terminal Sessions](../feature--ai-terminal--terminal-session-management/story--open-one-or-more-terminal-sessions.md) — a terminal session must be open before text can be sent to its prompt.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN at least one AI chat session is open with text highlighted and in focus, and at least one terminal session is open and selected as the destination, WHEN the technical user selects the option to run the highlighted text, THEN the highlighted text is sent to the destination terminal session prompt and automatically submitted.
- GIVEN at least one AI chat session is open with text highlighted and in focus, and no terminal sessions are open, WHEN the technical user selects the option to run the highlighted text and confirms opening a new terminal session, THEN a new terminal session is opened and the highlighted text is sent to its prompt and automatically submitted once the session is available.
- GIVEN at least one AI chat session is open with text highlighted and in focus, and no terminal sessions are open, WHEN the technical user selects the option to run the highlighted text and cancels opening a new terminal session, THEN no terminal session is opened and nothing is submitted.
- GIVEN at least one AI chat session is open and in focus with no text highlighted, and zero or more terminal sessions are open, WHEN the technical user selects the option to run the highlighted text, THEN nothing is sent to a terminal and the app informs the technical user that text must be selected in the focused AI chat session.
- GIVEN at least one AI chat session is open and in focus with an image highlighted, and zero or more terminal sessions are open, WHEN the technical user selects the option to run the highlighted content, THEN nothing is sent to a terminal and the app informs the technical user that an image cannot be run as a terminal command and that text must be selected instead.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V3 - Command Runner](../../../epics/epic--ai-terminal--v3-command-runner.md)

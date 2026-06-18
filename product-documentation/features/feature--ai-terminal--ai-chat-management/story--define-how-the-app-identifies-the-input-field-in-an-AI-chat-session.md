# Story: Define the Chat Input Field Locator

**Statement:** As a technical user, I need to define how the app identifies the input field in an AI chat session, so that the app can paste clipboard content to the correct place.

**Parent Feature:** [AI Chat Management](../../feature--ai-terminal--ai-chat-management.md)

## Story Title
define how the app identifies the input field in an AI chat session

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open a Configured AI Chat Session](story--open-a-configured-AI-chat-session.md) — a session must be open before the input field locator can be defined.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN an AI chat session is open and the technical user has focused the chat input field, WHEN the technical user selects the option to set the AI chat input, THEN the app captures enough information about that element to reliably locate it in future sessions.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V1 - AI Chat Management](../../../epics/epic--ai-terminal--v1-ai-chat-management.md)

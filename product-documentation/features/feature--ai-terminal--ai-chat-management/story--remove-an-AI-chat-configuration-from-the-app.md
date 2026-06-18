# Story: Remove an AI Chat Configuration

**Statement:** As a technical user, I need to remove an AI chat configuration from the app, so that I can keep my configured AIs relevant.

**Parent Feature:** [AI Chat Management](../../feature--ai-terminal--ai-chat-management.md)

## Story Title
remove an AI chat configuration from the app

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Add an AI Chat Configuration](story--add-an-AI-chat-configuration-to-the-app.md) — at least one AI configuration must exist before one can be removed.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN the technical user has opened the app and at least one AI chat configuration exists, WHEN the technical user selects the option to remove an AI and confirms the removal, THEN the AI configuration is removed and any open chat session for that AI is closed.
- GIVEN the technical user has opened the app and at least one AI chat configuration exists, WHEN the technical user selects the option to remove an AI and cancels the removal, THEN the AI configuration remains saved and any open chat session for that AI remains open.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V1 - AI Chat Management](../../../epics/epic--ai-terminal--v1-ai-chat-management.md)

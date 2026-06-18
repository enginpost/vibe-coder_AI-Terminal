# Story: Set a Default AI Chat that Opens at App Launch

**Statement:** As a technical user, I need to set a default AI chat that opens at app launch, so that my primary AI is immediately available when I start the app.

**Parent Feature:** [AI Chat Management](../../feature--ai-terminal--ai-chat-management.md)

## Story Title
set a default AI chat that opens at app launch

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Add an AI Chat Configuration](story--add-an-AI-chat-configuration-to-the-app.md) — at least one AI configuration must exist before one can be set as the default.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN at least one AI has been configured, WHEN the technical user sets that AI as the default, THEN the default AI is visually distinguishable from other configured AIs in the list, and a session with that AI is opened automatically when the app launches.
- GIVEN at least two AIs are configured and one is set as the default, WHEN the technical user sets a different AI as the new default, THEN the previously default AI is no longer marked as the default and only the newly selected AI is visually denoted as default.
- GIVEN no AIs are configured, WHEN the app launches, THEN no AI session is opened and the technical user is informed that they need to configure an AI.
- GIVEN at least one AI is configured but none is set as the default, WHEN the app launches, THEN no AI session is opened and the technical user is informed that they need to set a configured AI as the default.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V1 - AI Chat Management](../../../epics/epic--ai-terminal--v1-ai-chat-management.md)

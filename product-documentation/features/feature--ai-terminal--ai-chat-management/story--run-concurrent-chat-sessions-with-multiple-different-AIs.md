# Story: Run Concurrent Chat Sessions with Multiple Different AIs

**Statement:** As a technical user, I need to run concurrent chat sessions with multiple different AIs, so that I can consult more than one AI at the same time.

**Parent Feature:** [AI Chat Management](../../feature--ai-terminal--ai-chat-management.md)

## Story Title
run concurrent chat sessions with multiple different AIs

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Add an AI Chat Configuration](story--add-an-AI-chat-configuration-to-the-app.md) — at least two AI configurations must exist before multiple concurrent sessions can be opened.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN the technical user has opened the app and at least two AI chat configurations exist and one AI session is already open, WHEN the technical user opens a session for a second different AI, THEN the second AI chat session is presented within the app while the first session remains open.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V1 - AI Chat Management](../../../epics/epic--ai-terminal--v1-ai-chat-management.md)

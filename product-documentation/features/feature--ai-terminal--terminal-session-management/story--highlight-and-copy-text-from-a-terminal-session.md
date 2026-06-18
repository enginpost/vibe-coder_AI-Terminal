# Story: Highlight and Copy Text from a Terminal Session

**Statement:** As a technical user, I need to highlight and copy text from a terminal session, so that I can share it from the clipboard.

**Parent Feature:** [Terminal Session Management](../../feature--ai-terminal--terminal-session-management.md)

## Story Title
Highlight and copy text from a terminal session

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open One or More Terminal Sessions](story--open-one-or-more-terminal-sessions.md) — a terminal session must be open before text can be highlighted and copied from it.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN a terminal session is open and terminal content is highlighted, WHEN the technical user selects to copy the content, THEN the content is copied to the clipboard.
- GIVEN a terminal session is open and no content is highlighted, WHEN the technical user selects to copy the content, THEN nothing is copied to the clipboard.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V2 - Terminal Management](../../../epics/epic--ai-terminal--v2-terminal-management.md)

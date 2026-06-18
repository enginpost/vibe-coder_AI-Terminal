# Story: Label an Open Terminal Session

**Statement:** As a technical user, I need to label an open terminal session, so that I can identify its purpose when multiple sessions are open.

**Parent Feature:** [Terminal Session Management](../../feature--ai-terminal--terminal-session-management.md)

## Story Title
Label an open terminal session

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open One or More Terminal Sessions](story--open-one-or-more-terminal-sessions.md) — a session must be open before it can be labelled.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN at least one terminal session is open, WHEN the technical user assigns a label to a terminal session, THEN the label is associated with that session and visible to the technical user.
- GIVEN at least two terminal sessions are open and at least one has a label, WHEN the technical user attempts to assign that same label to a different terminal session, THEN the app does not apply the label and informs the technical user that the label is already in use.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V2 - Terminal Management](../../../epics/epic--ai-terminal--v2-terminal-management.md)

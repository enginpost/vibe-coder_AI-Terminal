# Story: Close an Existing Terminal Session

**Statement:** As a technical user, I need to close an existing terminal session, so that I can remove sessions I no longer need.

**Parent Feature:** [Terminal Session Management](../../feature--ai-terminal--terminal-session-management.md)

## Story Title
Close an existing terminal session

## Predecessor Stories
*Stories whose outcome this story depends on as a precondition.*

- [Open One or More Terminal Sessions](story--open-one-or-more-terminal-sessions.md) — a session must exist before one can be closed.

## Successor Stories
*Stories that depend on this story's outcome.*

> None identified.

## Acceptance Criteria
*Written in Gherkin format. Each criterion describes a need and a verifiable outcome — not a solution.*

- GIVEN at least one terminal session is open, WHEN the technical user closes that terminal session, THEN the session ends and is no longer present in the app.
- GIVEN exactly one terminal session is open, WHEN the technical user closes that terminal session, THEN no terminal sessions are open and the app does not present a terminal area.

## Story Size
> [not yet estimated]

## Solution Hypothesis
> [not yet defined]

## Epic Association
**Epic:** [AI Terminal V2 - Terminal Management](../../../epics/epic--ai-terminal--v2-terminal-management.md)

# Product Vision: AI Terminal

## Problem Statement
System administrators and technical users who use AI to help execute tasks face a repetitive, high-friction workflow: they must manually copy commands from AI chat into a terminal, run them, then copy results back into chat for next steps. The constant context-switching between separate tools slows down operations and increases the chance of errors. An integrated experience that connects one or more AI chats directly with a terminal — with easy bidirectional movement of selected text — would significantly speed up AI-assisted workflows. This matters now as AI-assisted CLI work is becoming common but tooling hasn't caught up.

## Target Users

### Technical User
**Differentiators**
- Reasonably technical
- Performs lots of web research to find answers
- Prefers working with AI to research and determine next steps

**Pains & Gains** *(ordered by priority)*
1. Easily consult with one or more AI in a chat format
2. Easily manage one or more terminal session
3. Speed up copying and pasting command advice from AI into a terminal session and results in the terminal copy and pasted back into the AI chat for result analysis

## Value Proposition
AI Terminal gives technical users a unified workspace that combines AI chat and terminal sessions in one place, eliminating the friction of switching between tools. By making it easy to consult multiple AIs, manage terminal sessions, and move command advice and results between them with minimal effort, it dramatically speeds up AI-assisted research and system administration workflows.

## Success Metrics
- **Chat-to-Terminal Speed:** Time (in minutes and seconds) from initiating an AI chat to getting a recommended command into the terminal window ready to submit
- **Terminal-Result-to-Chat-Analysis Speed:** Time to move a terminal result from the terminal window into the AI chat and submit it for result analysis

## Scope

*Ordered by anticipated priority. Each item represents a potential feature area.*

1. **[AI Chat Management](features/feature--ai-terminal--ai-chat-management.md)** — Start, view, and switch between one or more AI chat sessions
2. **[Terminal Session Management](features/feature--ai-terminal--terminal-session-management.md)** — Create and manage one or more terminal sessions
3. **[Bidirectional Text Transfer](features/feature--ai-terminal--bidirectional-text-transfer.md)** — Quickly move selected text from AI chat to terminal and terminal output back to AI chat

## Assumptions & Risks

**Assumptions**
- AI chat UIs (one or more) can be embedded into the application
- AI chat advice can be copy and pasted into terminal prompts to be submitted
- Terminal session UIs (one or more) can be embedded into the application
- Terminal results can be copy and pasted into AI chat input fields to be submitted

**Risks**
- Not all AIs can be embedded and how to handle those errors
- Difficulty identifying the AI chat input field in the chat UI to paste terminal session results for analysis by the AI

## Stakeholders
- Steve McDonald — technical user, sole stakeholder

## Roadmap
> See: [Roadmap](../product-documentation/roadmap--ai-terminal.md)

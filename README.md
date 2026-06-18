# AI Terminal

AI Terminal is a unified workspace that combines AI chat sessions and terminal sessions in a single application, eliminating the friction of switching between separate tools during AI-assisted system administration workflows.

## Problem

Technical users who rely on AI to help execute tasks face a repetitive, high-friction workflow: manually copying commands from an AI chat into a terminal, running them, then copying results back into the chat for analysis. The constant context-switching slows down operations and increases the chance of errors.

## What It Does

AI Terminal brings together AI chat and terminal sessions in one place, with three core capabilities:

- **AI Chat Management** — Add, open, and manage one or more AI chat sessions within the app. Consult multiple AIs simultaneously, set a default AI that opens at launch, and copy highlighted chat text to the clipboard for use in the terminal.

- **Terminal Session Management** — Open and manage one or more terminal sessions within the app. Label sessions for clarity, paste clipboard commands directly into the terminal prompt, and copy or save terminal output.

- **Command Runner** — Execute a single click-command to send highlighted text from an AI chat directly to the terminal prompt and submit it as a command — or send terminal results back to the AI chat for analysis — without any manual copy-paste steps.

## Who It's For

**Technical users** who perform system administration tasks and use AI to research and determine next steps. AI Terminal is designed for those who prefer working with AI in a chat format and want to move faster between AI advice and terminal execution.

## Success Metrics

- **Chat-to-Terminal Speed** — Time from initiating an AI chat to getting a recommended command into the terminal window ready to submit.
- **Terminal-Result-to-Chat-Analysis Speed** — Time to move a terminal result from the terminal window into the AI chat and submit it for analysis.

## Roadmap

| Release | Description | Size |
|---------|-------------|------|
| V1 — AI Chat Management | Deliver integrated AI chat session management within the app | m |
| V2 — Terminal Management | Deliver integrated terminal session management within the app | m |
| V3 — Command Runner | Deliver single-click bidirectional text transfer between AI chat and terminal | s |

## Documentation

Full product documentation is in [`product-documentation/`](product-documentation/).

- [Product Vision](product-documentation/product-vision--ai-terminal.md)
- [Roadmap](product-documentation/roadmap--ai-terminal.md)
- [Features](product-documentation/features/)
- [Epics](product-documentation/epics/)

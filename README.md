# Thesis chatbot and classification prompts

This repository provides the system prompts, activity instructions and classification prompts available in the thesis source. The Markdown files reproduce their content for reading; placeholders such as `{context}` are runtime inputs. Line breaks and formatting have been adapted from LaTeX, and the files are not executable implementations.

- Penny: [persona system prompt](penny/persona-system-prompt.md), [system prompt and guidelines](penny/system-prompt-guidelines.md), and [feedback classification prompts](penny/feedback-classification.md).
- ARCHIE: [system prompt and activity instructions](archie/system-prompt-and-activities.md) and [student message classification prompt](archie/student-message-classification.md).
- TAMMY: [system prompt](tammy/system-prompt.md), [response validity classification](tammy/interaction-classification.md), [translation success classification](tammy/translation-success-classification.md), and [user intent classification](tammy/user-intent-classification.md).
- Personalisation: [experimental prompt injection](personalisation/prompt-injection.md).

The two Penny system-prompt files are distinct thesis source appendices; their presence here does not establish that they are interchangeable or identify which version was used in each study. The ARCHIE student-message prompt lists more categories than the final analysis scheme; see the thesis chapter for the final coding scheme.

The source workspace did not contain the full classification pipeline, Penny uptake classifier prompt, ARCHIE response-classification prompt, or learner-model classification implementations. This repository does not contain learner interaction data or model weights and is not a complete executable replication package.

For a stable reference, cite a specific commit or an archived release of this repository with the thesis.

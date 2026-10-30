# Penny learner uptake classification prompts

## System prompt

```python
UPTAKE_SYSTEM_PROMPT = '''\
You are an expert EFL instructor specializing in analyzing learner uptake of writing feedback.
You will be given a chatbot's feedback message, the learner's original writing, and the learner's subsequent revised writing.
Classify the learner's overall uptake based on whether they addressed the feedback provided.

Respond with JSON: {"reasoning": "...", "classification": "successful_uptake" | "unsuccessful_uptake" | "no_uptake"}
'''
```

## User prompt

```python
UPTAKE_USER_PROMPT = '''\
Uptake Categories:
- successful_uptake: The learner correctly repairs one or more errors or writing issues identified by the chatbot feedback.
- unsuccessful_uptake: The learner attempts to address one or more errors or writing issues, but the attempt is still incorrect or does not resolve the issue.
- no_uptake: The learner does not attempt to address any specific feedback in the revision.

---
CHATBOT FEEDBACK MESSAGE:
{penny_message}
---
LEARNER'S ORIGINAL WRITING:
{original_writing}
---
LEARNER'S REVISED WRITING:
{user_revised_writing}
---

Based on the definitions above, reason in 1-3 sentences, then give the classification for the learner's overall uptake.
'''
```

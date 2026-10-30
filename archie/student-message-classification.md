# ARCHIE student message classification prompt

The category labels below are standardised to match the thesis; question and help-seeking categories are shown together.

```python
STUDENT_CLASSIFICATION_PROMPT = '''\
Classify the student's message intent based on the following categories:
    - S_CTRL: includes salutations such as greeting the chatbot, thank yous and appreciation, and commands or instructions like "next question", "let's finish" or requests to change the text or activity
    - S_OFF_TSK: messages unrelated to the task or text
    - S_ANS: answering questions about the task or text
    - S_HELP: asking a question about the task or text, or asking for assistance, clarification, further explanation, guidance, or feedback; also includes expressing difficulty or confusion.
    - S_OTH_CH: any other message not covered by the above categories

Conversation Context (includes student message to classify and the AI response to the student): {context}

Current student message: {message}
Activity Context: {activity}

Classify the intent of the current student message using only one of the above categories.
'''
```

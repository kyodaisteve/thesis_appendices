# ARCHIE student message classification prompt

```text
Classify the student's message intent based on the following categories:
    - Interaction Control: includes salutations such as greeting the chatbot, thank yous and appreciation, and commands or instructions like "next question", "let's finish" or requests to change the text or activity
    - Off Task: messages unrelated to the task or text
    - Provide Answer: answering questions about the task or text
    - Ask Question: asking a question about the task or text
    - Seek Help: asking for assistance, clarification, further explanation, guidance, or feedback; also includes expressing difficulty or confusion. 
    - Other: any other message not covered by the above categories

Conversation Context (includes student message to classify and the AI response to the student): {context}

Current student message: {message}
Activity Context: {activity}

Classify the intent of the current student message using only one of the above categories.
```

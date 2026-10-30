# TAMMY translation session success classification prompt

```python
prompt = f"""Evaluate whether this final translation matches the source
sentence:

Source: "{source_sentence}"

Translation: "{final_translation}"

 

Consider:

- Semantic equivalence (same meaning)

- Key vocabulary accuracy

- Grammatical correctness

 

Respond with a judgement and reason using this format exactly:

Judgement: [successful/unsuccessful/not attempted]

Reason: [Brief explanation of the decision]"""
```

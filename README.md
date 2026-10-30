# Thesis appendices: prompts and classification materials

This repository contains copies of the prompt and classification materials included in the LaTeX appendices of the thesis on the Kōrero English-learning chatbot framework. The files preserve the thesis source, including LaTeX formatting and placeholders, rather than presenting executable implementations. They are intended to be read alongside the thesis; they are not standalone LaTeX documents.

## Contents

- [Penny daily writing prompts](penny/penny_appendix.tex)
- [Penny persona system prompt](penny/penny_persona_appendix.tex)
- [Penny system prompt and guidelines](penny/penny_prompt_appendix.tex)
- [Penny feedback classification definitions and prompts](penny/penny_coding_appendix.tex)
- [ARCHIE system prompt, activity instructions, student-message classification prompt and aggregate coding table](archie/archie_appendix.tex)
- [TAMMY chatbot and classification prompts](tammy/tammy_appendix.tex)
- [Personalisation prompt injection](personalisation/jla_prompt_appendix.tex)

The two Penny system-prompt files are distinct thesis appendices; their presence here does not establish that they are interchangeable or identify which version was used in each study. The ARCHIE file includes an aggregate results table in addition to the prompt materials.

## Scope and limitations

These files reproduce the materials available in the thesis workspace. They do not include the classification pipeline source code, learner interaction data, or model weights. In particular, the Penny uptake classifier prompt, the ARCHIE response-classification prompt, and learner-model classification implementations are described in the thesis but were not found as standalone materials in the workspace. The repository should not be treated as a complete executable replication package. Dynamic fields in braces are placeholders, not actual participant data.

For a stable reference, cite a specific commit or a versioned release of this repository along with the thesis. A DOI can be obtained by archiving a release through a repository service such as Zenodo.

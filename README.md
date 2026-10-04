# Using and Evaluating LLMs for Social Sciences

A two-hour tutorial on querying large language models as research instruments, and checking what they measure.
Siyu Liang, Department of Linguistics, Rice University.

**Open the companion notebook in Colab:**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/siyuliang/llm-social-science-tutorial/blob/main/llm_social_science_tutorial.ipynb)

First move once it opens: **File → Save a copy in Drive**.

## Files

| file | what it is |
|---|---|
| `llm_social_science_tutorial.ipynb` | the hands-on notebook: change one thing in a prompt and compare; open answers coded by the model; then your own study |

## Running the notebook

You need an Anthropic API key (one is provided during the tutorial). In Colab, store it in the Secrets pane (🔑, left edge) under the name `ANTHROPIC_API_KEY` and switch on notebook access; otherwise the setup cell asks you to type it.

The notebook ships with outputs from a real run, so you can read the prompts, the raw answers, and the analysis before running anything. Each part has a few variables in CAPITALS (`CONDITIONS`, `PERSONAS`, `CODEBOOK`, `N`); change those to make it your own study.

## Acknowledgments

Much of the material on prompting, benchmark design, and evaluation metrics is adapted from Bolei Ma's (LMU Munich) lecture series *Benchmarking AI Models Using Surveys* (2026).

© 2026 Siyu Liang · [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

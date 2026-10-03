# Using and Evaluating LLMs for Social Sciences

A two-hour tutorial on querying large language models as research instruments, and checking what they measure.
Siyu Liang, Department of Linguistics, Rice University.

**Open the companion notebook in Colab:**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/siyuliang/llm-social-science-tutorial/blob/main/llm_social_science_tutorial.ipynb)

First move once it opens: **File → Save a copy in Drive**.

## Files

| file | what it is |
|---|---|
| `llm_social_science_tutorial.ipynb` | the hands-on notebook (API mode, or paste answers from any chatbot) |

## Running the notebook

- **With an Anthropic API key**: set `MODE = "api"` in the setup cell. In Colab, store the key in the Secrets pane (🔑, left edge) as `ANTHROPIC_API_KEY`, or type it when prompted.
- **Without a key**: set `MODE = "paste"` and paste answers from a chat window into the `PASTED` dictionary where indicated.

## Acknowledgments

Much of the material on prompting, benchmark design, and evaluation metrics is adapted from Bolei Ma's (LMU Munich) lecture series *Benchmarking AI Models Using Surveys* (2026).

© 2026 Siyu Liang · [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

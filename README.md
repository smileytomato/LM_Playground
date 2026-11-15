# LM_Playground - A Local LLM Research Project

```
The playground for local LLM prompt engineering ✍️🔥
```

This project aims to revisit **GotYouAI**, a hackathon project developed in February 2026. GotYouAI is an AI-powered *rizz agent* designed to suggest natural and engaging replies to Instagram DMs.

The original hackathon version is available in my [GitHub repository](https://github.com/smileytomato/GotYouAI)

Beyond GotYouAI, this repository will also explore future LLM applications in finance.

## Getting Started

### Requirements

To run the experiments, we use **Python 3.11** and the following packages:

```bash
pip install llama-cpp-python
pip install -U huggingface_hub
pip install jupyterlab
pip install ipykernel
pip install -U ipywidgets jupyter
pip install pandas
```

### Research Approach

The initial experiments focus on prompt engineering, response generation, and evaluating the quality and consistency of LLM outputs.

Future experiments may explore fine-tuning or other topics of local LLM.

## Inference Parameters

### Temperature

Temperature controls the randomness of token sampling during inference. Lower values generally produce more predictable responses, while higher values encourage diversity and creativity.

| Temperature | Level | Typical Use Cases |
|---|---|---|
| 0.0–0.3 | Low / Deterministic | Code generation, data extraction, mathematics, factual Q&A |
| 0.4–0.7 | Medium / Balanced | General conversations, everyday writing, summarization, RAG |
| 0.7–1.0 | High / Creative | Brainstorming, storytelling, poetry, marketing |
| 1.2–1.5+ | Very High / Experimental | Highly diverse, unpredictable, or potentially incoherent outputs |

These ranges are approximate and may vary depending on the model and sampling configuration.

For now, we use **temperature = 0.7** as the baseline for our experiments.



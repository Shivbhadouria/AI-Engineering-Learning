# Shiv's LLM Engineering Journey

A hands-on learning portfolio documenting my journey into **Generative AI, LLM Engineering, and Agentic AI**.

I'm learning by building small experiments, understanding the APIs behind modern language models, and gradually combining those building blocks into useful applications.

## Notebooks

| Notebook | Focus |
|---|---|
| `day1.ipynb` | First LLM lab, prompts, messages, website content |
| `day2.ipynb` | Chat Completions, HTTP endpoints, Python clients, compatible APIs |
| `day4.ipynb` | Tokenization, conversation memory, message handling |
| `day5.ipynb` | Multi-step LLM workflow and business brochure generation |
| `week1 EXERCISE.ipynb` | Streaming technical explanation assistant |

> The supplied learning files include examples from different model providers. Some cells have been adapted to Google Gemini; other cells intentionally retain provider-comparison material from the original exercises. Review the configuration in each notebook before running it.

## Tech and concepts

- Python and Jupyter Notebook
- LLM APIs and OpenAI-compatible client interfaces
- Google Gemini API
- Prompt engineering and chat messages
- JSON-based structured responses
- Streaming model responses
- Multi-step LLM workflows and early Agentic AI patterns

## Getting started

1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the dependencies used by the notebooks:

   ```bash
   pip install openai python-dotenv requests tiktoken jupyter
   ```

4. Create a `.env` file in the project root:

   ```env
   GOOGLE_API_KEY=your_google_ai_studio_api_key
   ```

5. Start Jupyter:

   ```bash
   jupyter lab
   ```

6. Open a notebook and run its cells in order. Some exercises may require additional project files or helper modules from the original course materials.

## API key safety

- Never commit `.env` files, API keys, tokens, or credentials.
- Keep `.env` in `.gitignore`.
- If a key is exposed, revoke it and generate a replacement.
- Check the provider's current model availability, quotas, and pricing before use.

## Learning approach

This repository is a work in progress. I’m keeping the notebooks as a record of what I learn, what I build, and how my understanding improves over time. I plan to share future milestones and practical takeaways on LinkedIn.

---

**Created by Shiv Bhadouria**  
*Learning in public — one experiment at a time.*

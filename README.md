# LLM Learning Lab

A collection of hands-on LLM projects and notebook experiments. Each numbered folder contains one focused project, so more LLM experiments can be added cleanly over time.

## Project Structure

- `01-llm-website-summarization/` - website summarization experiments with hosted Gemini models and local Ollama models.
- `01-llm-website-summarization/gemini_api_quickstart.ipynb` - first Gemini API request using the OpenAI-compatible endpoint.
- `01-llm-website-summarization/gemini_website_summarizer.ipynb` - website summarization with Gemini.
- `01-llm-website-summarization/ollama_website_summarizer.ipynb` - website summarization with a local Ollama model.
- `01-llm-website-summarization/website_scraper.py` - helper functions for fetching website text and links.
- `setup_steps.txt` - original setup commands for recreating the environment.

## Setup

```bash
uv venv
uv sync
```

Add API keys to `.env` when using hosted models. The `.env` file is ignored by Git.

# Token Counting and Cost Analysis

This folder contains [`counting_tokens.ipynb`](counting_tokens.ipynb), a notebook that explores tokenization and estimates the input-token cost of prompts.

## What the notebook does

- Loads the `tiktoken` encoding associated with `gpt-4.1-mini`.
- Compares short, medium, and long sample prompts by character, word, and token count.
- Estimates input cost using a configured price per million tokens.
- Plots token counts for the sample prompts.
- Provides an interactive prompt analyzer that displays counts, estimated cost, a token ID breakdown, and a composition chart.

## Run it

Open `counting_tokens.ipynb` in Jupyter or another notebook environment. The notebook uses `tiktoken`, `pandas`, `matplotlib`, and `ipywidgets`.

## Pricing note

The notebook sets `INPUT_PRICE_PER_MILLION` to `$0.40` as an example. Update this value to match the pricing you want to estimate. The calculation covers input tokens only; actual API charges can also depend on the provider's current rates, model, cached tokens, output tokens, and other usage charges.

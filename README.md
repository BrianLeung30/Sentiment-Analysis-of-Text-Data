# Sentiment140 BERTweet Fine-Tuning Benchmark

Compare various fine-tuning methods on BERTweet-based models for binary sentiment analysis on Sentiment140.

**Models (seeds 1, 2, 3):**

- [`BrianLeung/bertweet-sentiment140-full-finetune`](https://huggingface.co/BrianLeung/bertweet-sentiment140-full-finetune)
- [`BrianLeung/bertweet-sentiment140-lora`](https://huggingface.co/BrianLeung/bertweet-sentiment140-lora) (`r32`, `r8`, `r4`)
- [`BrianLeung/bertweet-sentiment140-prompt-tuning`](https://huggingface.co/BrianLeung/bertweet-sentiment140-prompt-tuning)
- [`BrianLeung/bertweet-sentiment140-classifier-only`](https://huggingface.co/BrianLeung/bertweet-sentiment140-classifier-only)

**Dataset:** [`BrianLeung/sentiment140-csv`](https://huggingface.co/datasets/BrianLeung/sentiment140-csv)

## Running Demo

1. Open `Demo.ipynb` and run all cells.
2. Results: Accuracy, F1, recall, precision for each model.
3. Try your own custom text at the end.

## Running Fine-Tuning Sripts

1. Open `training scripts` folder.
2. Select a notebook and run all cells.
3. Models will be save to google drive.

## Structure

- `Demo.ipynb` — Loads models, evaluates, and predicts.
- `training scripts/` — Notebooks for each fine-tuning method.

## Notes

- All models: see subfolders for seed variants.
- LoRA models: see subfolders for rank variants.

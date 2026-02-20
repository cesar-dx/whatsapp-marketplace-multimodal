# Predicting Prices on MIT’s WhatsApp Marketplace (Multimodal)

**TL;DR:** Built a multimodal model that combines image and text features to predict resale prices, with an end-to-end training + evaluation pipeline.

## Goal
Predict the price of items listed in WhatsApp marketplace chats using information available at listing time, leveraging both:
- images (product photos)
- text (listing title/description/chat context)

## Approach
- Preprocessed dataset into aligned (image, text, target price) examples.
- Trained baseline models (text-only, image-only) and a multimodal fusion model.
- Evaluated performance with appropriate error metrics for prices and compared modality contributions.

## Outcome
- Delivered a working multimodal prototype and analysis showing when images add signal beyond text.
- Summarized methods and results in the project report.

## Report
- Portfolio PDF: https://cesar-dx.github.io/assets/reports/deep-learning.pdf

## Repo structure (planned)
- `src/` data loading, training, evaluation
- `notebooks/` exploration and experiments
- `configs/` hyperparameters
- `assets/` figures
- `data/` (not included) + instructions

## Notes on data
Raw data is not included in this repository. See `data/README.md` for expected format and how to reproduce preprocessing.

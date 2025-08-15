# Sarcasm Detection in Game Reviews Using Transformers

This repository contains the codebase for my Master's thesis on detecting sarcasm in video game reviews using transformer-based models. The project uses review data scraped from Steam for two games — *Battlefield 2042* and *Barotrauma* — and explores the performance of both base and feature-enhanced transformer models.

The thesis also includes a helpfulness classification component for sarcastic reviews and tests generalizability across different games.

---

## Project Structure

The code is organized into clearly named folders by stage:

- `1_scraping_cleaning_sampling/` – Data scraping, cleaning, and sampling
- `2_preprocessing/` – Label cleaning and review preprocessing
- `3_model_baseline/` – Base RoBERTa model training
- `4_fine_tuning/` – Hyperparameter tuning
- `5_best_model_evaluation/` – Best model testing and confusion matrix
- `6_cross_game_testing/` – Generalisability testing on Barotrauma
- `7_feature_enhanced_model/` – Feature-augmented RoBERTa model
- `8_feature_model_evaluation/` – Feature model testing and evaluation
- `9_helpfulness_classifier/` – Helpfulness classification for sarcastic reviews
- `10_combined_dataset/` – Combined model trained on both games

---

## Notes

- The data files used for this project are not included in the public repository.
- Each folder is self-contained for clarity and traceability.


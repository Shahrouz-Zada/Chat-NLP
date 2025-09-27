# Chat NLP

This project builds a hybrid NLP pipeline to analyze Bloomberg-style chat messages in real time. It combines regex, spaCy, and transformer models for entity extraction and intent detection, deployed via FastAPI.

## Structure

- `src/app/`: FastAPI app and NLP logic
- `data/`: Synthetic chat messages
- `tests/`: Unit tests
- `docs/`: Documentation
- `scripts/`: Utilities (e.g., data generation)

## Setup

```bash
pip install -r requirements.txt
uvicorn src.app.main:app --reload

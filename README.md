# Local Personality Chatbot

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)

A small offline chatbot that combines intent classification with a configurable response style. It uses local JSON data and does not call a hosted language-model API.

## Run locally

Install the listed dependencies, train the intent model, and start the chatbot:

```bash
pip install -r requirements.txt
python train_model.py
python main.py
```

The chatbot reads its intents, sample responses, and vocabulary from the JSON files in the repository root. Type `exit`, `quit`, or `sair` to close the session.

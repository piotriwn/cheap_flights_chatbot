# Cheap Flight Chatbot

## Features
- Human-language interface to finding cheap flights.
- Uses tools calls to obtain data.

## How to run

You have to create a file called `.env` in the project's root.
Its content should be like:
```
OPENAI_API_KEY=sk-proj-...
```
(OpenAI key)


Create an environment (one time action):
```
conda env create -f environment.yaml 
```
Activate it:

```
conda activate llm-flight-bot
```

Run jupyter lab:
```
jupyter lab
```

## Disclaimers
This is PoC-type project. Its sole purpose is education.
Please adhere to the license agreements/terms of use when scraping websites. The one chosen here is just an example and one should be aware of terms of use before using it.

## Inspirations
LLM wrappers: 
https://github.com/ed-donner/llm_engineering/blob/main/week2/community-contributions/day1_class_definition-botChat.ipynb

Notebook structure: 
https://github.com/ed-donner/llm_engineering/blob/main/week2/community-contributions/day4-airlines-project-fullyCustomize.ipynb

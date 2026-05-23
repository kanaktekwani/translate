# Language Translator

Streamlit application for translating text between languages and generating
downloadable text-to-speech audio for the translated output.

## What It Does

- Accepts free-form text input from the user.
- Supports a broad set of source and target languages.
- Translates text through `google-trans-new`.
- Generates translated speech audio with `gTTS`.
- Presents the workflow in a simple Streamlit UI.

## Tech Stack

- Python
- Streamlit
- google-trans-new
- gTTS

## Run Locally

```bash
cd LanguageTranslator-main
pip install -r requirements.txt
streamlit run main.py
```

## Project Notes

The application source lives in `LanguageTranslator-main/`. This was an early
Python/Streamlit project focused on rapid UI prototyping, language APIs, and
audio generation.

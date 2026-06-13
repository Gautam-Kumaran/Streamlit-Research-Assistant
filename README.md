# Streamlit Research Assistant

This is a small Streamlit application built as a research assistant.

The app provides a simple interface for asking questions, summarising text and working with research material using a language model.

## Main File

```text
app.py
```

## Features

The app can be used for:

- Asking research-related questions
- Summarising text
- Explaining concepts
- Organising notes
- Generating structured responses

## Running the App

```bash
streamlit run app.py
```

The app will open in a browser, usually at:

```text
http://localhost:8501
```

## Notes

If the app uses an API key, it should be stored in Streamlit secrets or an environment variable and not written directly into the code.

The output from the model should always be checked against the original source, especially for technical or academic work.

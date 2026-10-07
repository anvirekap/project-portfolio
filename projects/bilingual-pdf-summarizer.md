# Bilingual PDF Summarizer

[Source repository](https://github.com/anvirekap/bilingual-pdf-summarizer)

A study tool that turns text-based course PDFs into concise English or French study summaries.

## Implemented features

- Upload a PDF through Streamlit.
- Extract text page by page using pypdf.
- Generate a five-bullet study summary through the Groq API.
- Choose English output or translate the summary into French using deep-translator.
- Preview extracted text.
- Show warnings for a missing API key, PDFs without extractable text, and summary-generation errors.

## Stack

Python, Streamlit, pypdf, Groq API, deep-translator.

## Scope

The current implementation sends the first 8,000 extracted characters for summarization. Image-only scanned PDFs require OCR, which this version does not implement.

## Run it

Install the dependencies from requirements.txt and run `streamlit run app.py`. Enter your own Groq API key in the app's password field.

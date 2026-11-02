# Conchita AI 🐚

My first generative-AI app: a small Streamlit chat assistant powered by Google's Gemini 2.5 Flash.

You paste your own Gemini API key in the sidebar (it's only kept for the session, never stored), ask a question, and Conchita answers.

## Run it

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

Get an API key at [Google AI Studio](https://aistudio.google.com/).

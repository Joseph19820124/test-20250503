# Google AI Function Calling Demo (Weather Agent) in Colab

This notebook demonstrates how to use the Function Calling feature of the Google AI SDK (Gemini API) within Google Colab.

**Objective:** Create a simple AI agent that can answer questions about weather by calling a defined Python function.

**⚠️ Important Setup:**
1.  **API Key:** You need a Google AI API Key. Get one from [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  **Colab Secrets:** For security, store your API Key using Colab's Secrets manager:
    * Click the **🔑 Key icon** in the left sidebar.
    * Click **"+ Add a new secret"**.
    * Enter the name `GOOGLE_API_KEY`.
    * Paste your actual API key into the value field.
    * Toggle the switch to make it available to this notebook.
3.  **Run Cells:** Run the cells below in order.
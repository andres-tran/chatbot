# 💬 Chatbot template

A simple Streamlit app that shows how to build a chatbot using OpenAI's GPT-3.5.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://chatbot-template.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Add your OpenAI API key

   Create a file called `.streamlit/secrets.toml` with the following contents or enter
   the key in the app when prompted:

   ```toml
   openai_api_key = "YOUR_KEY_HERE"
   ```

3. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```


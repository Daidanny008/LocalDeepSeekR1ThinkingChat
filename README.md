# LocalDeepSeekR1ThinkingChat

This project uses deepseek-r1 via Ollama and Streamlit to locally host a AI thinking-mode chat interface.

## Installation and setup

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama
   ```

**Setup Ollama**:
   ```bash
   # if not ollama app or running 
   ollama serve
   # pull the DeepSeek-R1 model, only need to do this once
   ollama pull deepseek-r1 
   ```

**Run the app**:

   Run the streamlit app as follows:
   ```bash
   # in one terminal
   ollama serve
   # in another terminal
   streamlit run app.py
   ```
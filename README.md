# TAD workshop
This repository contains the Text as Data workshop in Fall 2025. 

**How to use this repository**
1. Clone the repository to your local machine.
2. The .ipynb file contains the code for the workshop; the .html file is the rendered version of the notebook for easier reading. 
3. Create a `.env` file in the repository root (same folder as this README) and add your LLM API key in the format `OPENAI_API_KEY=your-key-here`. This is required for the LangChain examples that call OpenAI models. 
4. To execute the code, open the Jupyter notebook file and run the code cells sequentially. 

**Managing your API key**
- The `.env` file should stay local; do not commit it to version control. 
- Replace `your-key-here` with a valid OpenAI key that has access to the `gpt-4o` model (or adjust the notebook to use a different model and key name if needed). 
- If you are using a different LLM provider, update both the `.env` entry and the notebook configuration accordingly. 

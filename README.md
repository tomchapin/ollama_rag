# Ollama Langchain RAG Example - as a Jupyter Notebook

Based on the document here: https://python.langchain.com/docs/integrations/llms/ollama

Requirements:
- Python 3.11.5
- Jupyter (`pip install jupyterlab notebook`)
- Ollama (https://ollama.ai/)

Installation:
- Clone this repo to a local folder on your computer.
- Run `pip install -r requirements.txt`
- Run `jupyter notebook ollama_rag.ipynb`
- Hit the play button to run through each step.

## Troubleshooting:

If you run into any issues with Langchain modules, try this:
1. `pip install 'langchain[all]'` (to install all sub-modules)
2. `pip uninstall langchain` (and press Y to confirm)
3. `pip install langchain` (to reinstall the base langchain)
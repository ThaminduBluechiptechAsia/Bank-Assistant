# Bank-Assistant-
Bank Assistant chat bot using LLM and AstraDB
It is using OpenAI to build embeddings and Astra to store the data.

- Python 3.6+
- Launch an [AstraDB](https://astra.datastax.com/) vector database
- Run `loader.py` to import fake clients data in your Astra db collection from `resources/clients-dataset.csv`
- Run `main.py` using the command `streamlit run main.py`
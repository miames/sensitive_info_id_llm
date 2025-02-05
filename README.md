# sensitive_info_id_llm
This Jupyter Notebook demos how an LLM can be used to identify sensitive data in an data warehouse or database. In our case we use **Gemini-1.5-pro** for the LLM and **BigQuery** for the warehouse.  Feel free to clone this repo and experiment yourself.

Additional improvements that can be made are:
- Chunking official documents that define these classes, storing the chunks in a vector database, and making them available to the LLM. The chunking process is demonstrated nicely here: https://github.com/dharantej1/Google_L400_Labs_Solutions you can use Google Agent Space to automate the chunking and RAG implementation.

- Add an extra column to classified_data table that provides the LLM reasoning for the classification
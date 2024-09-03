# install the below dependencies
-----------------
* install postgresql
* create database named "testdb" install pgvector and PL/Python extensions
* run process_files_in_directory.sql and augmented_response.sql to create PL/Python functions on testdb
* python3
* pip
* psycopg2 (pip install psycopg2)

	https://pypi.org/project/psycopg2/

* langchain (pip install langchain)

	https://pypi.org/project/langchain/

* langchain_text_splitters (pip install langchain-text-splitters)

	https://pypi.org/project/langchain-text-splitters/

* tiktoken (pip install tiktoken)

	https://pypi.org/project/tiktoken/

* ollama

	>* Ollama Python Library: https://pypi.org/project/ollama/

	>* ollama service: https://ollama.com/download and/or https://github.com/ollama/ollama

	>* models to pull

	>>* mxbai-embed-large: ollama pull mxbai-embed-large
	
	>>* llama3.1: ollama pull llama3.1



* change the db password in the rag.py and uploaded_files.py

* streamlit

	https://docs.streamlit.io/get-started/installation

	>* streamlit run rag2.py
	>* streamlit run upload_files2.py
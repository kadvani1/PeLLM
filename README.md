# PeLLM 🏦 - Private Equity AI Agent

# What is this repo?
PeLLM is an AI agent for private equity.

Features:
- Generative legals: Generate and query legal private fund documents
- Generative research: Generate and query investment memos
- Generative compliance: Generate and query regulatory filings

![PeLLM Logo](https://i.ibb.co/ryRCKvc/Screenshot-2023-10-07-at-16-52-49.png)

This README provides an overview of the PELLM project and can be added to the project's GitHub repository to provide information to visitors and potential collaborators.

# User Guide
To run, first add your OpenAI API key and Pinecone API key to your environment and install the requirements. To run the streamlit demo run: streamlit run st_pellm_demo.py

llm = OpenAI(model="gpt-3.5-turbo")
openai.api_key = os.environ.get("OPENAI_API_KEY")
pinecone_api_key =  os.environ.get("PINECONE_API_KEY")
api_key = ""
environment = "gcp-starter"
index_name = "pellm"

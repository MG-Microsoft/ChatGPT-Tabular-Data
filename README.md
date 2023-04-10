# Use ChatGPT to Chat with Tabular/SQL Data

## installation
To get started, before running the notebook in this repo, install LangChain with the following command:

pip install langchain

## Environment Setup

Using LangChain will usually require integrations with one or more model providers, data stores, apis, etc.

For this example, we will be using OpenAI’s APIs, so we will first need to install their SDK:

pip install openai

We will then need to set the environment variable in the terminal.

export OPENAI_API_KEY="..."

Alternatively, you could do this from inside the Jupyter notebook (or Python script):

import os
os.environ["OPENAI_API_KEY"] = "..."

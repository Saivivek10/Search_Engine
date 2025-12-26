# 🔎 LangChain - Chat with Search

This project is an interactive chatbot application built using **LangChain** and **Streamlit**. The chatbot integrates tools like Wikipedia, Arxiv, and DuckDuckGo to provide intelligent search capabilities. It is designed to answer user queries by leveraging large language models (LLMs) and various search tools.

## Features

- **Wikipedia Search**: Fetch concise information from Wikipedia.
- **Arxiv Search**: Retrieve research papers and summaries from Arxiv.
- **DuckDuckGo Search**: Perform general web searches.
- **Interactive Chat Interface**: Built with Streamlit for a user-friendly experience.
- **Customizable LLM**: Uses the `ChatGroq` model for natural language understanding.

## How It Works

The chatbot uses the following tools and components:
- **LangChain**: A framework for building applications powered by language models.
- **Streamlit**: A Python library for creating interactive web apps.
- **ChatGroq**: A large language model used for generating responses.
- **Search Tools**:
  - `WikipediaQueryRun`: Fetches information from Wikipedia.
  - `ArxivQueryRun`: Retrieves research papers from Arxiv.
  - `DuckDuckGoSearchRun`: Performs web searches using DuckDuckGo.

The app is designed to display the thoughts and actions of the agent in real-time using `StreamlitCallbackHandler`.

## Screenshots

<img width="1512" height="982" alt="Chat search engine" src="https://github.com/user-attachments/assets/e50eb0a3-facc-420c-9c36-da2206e3e689" />



## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

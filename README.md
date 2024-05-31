# Multi-Tool Agent for Information Retrieval

This repository contains a Jupyter Notebook that demonstrates the setup and usage of various tools for information retrieval using the LangChain framework. The tools include a Wikipedia query tool, a Tavily search tool, and a web page retrieval tool.

## Overview

The notebook is designed to:
1. Set up and configure different tools for information retrieval.
2. Demonstrate the usage of APIs for accessing information from Wikipedia, Tavily, and web pages.
3. Utilize LangChain utilities for handling and processing retrieved information.

## Contents

- `multi_tool_agent.ipynb`: The main Jupyter Notebook containing all the code and explanations.
- `.env`: A file to store API keys (not included in this repository).

## Getting Started

### Prerequisites

- Python 3.7 or later
- Jupyter Notebook
- LangChain
- dotenv

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/multi-tool-agent.git
   cd multi-tool-agent
   ```

2. Install the required packages:
  ```bash
  pip install -r requirements.txt
  ```
3. Create a .env file in the root directory and add your API keys:
   ```bash
   TAVILY_API_KEY=your_tavily_api_key
   ```

## Project Structure

- **Imports and Setup**: Import necessary libraries and load environment variables.
- **Wikipedia Tool**: Configure and use a tool to query information from Wikipedia.
- **Tavily Tool**: Set up a search tool using the Tavily API.
- **Web Page Retrieval**: Retrieve and process content from web pages using LangChain utilities.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.



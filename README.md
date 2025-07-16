# LLM Flow Notebook

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4%2FGPT--3-412991?style=flat-square&logo=openai&logoColor=white)](https://openai.com/)
[![Anthropic](https://img.shields.io/badge/Anthropic-Claude-FF6F61?style=flat-square&logo=anthropic&logoColor=white)](https://anthropic.com/)
[![Mistral](https://img.shields.io/badge/Mistral-AI-6A5ACD?style=flat-square)](https://mistral.ai/)
[![AsyncIO](https://img.shields.io/badge/AsyncIO-Enabled-green.svg)](https://docs.python.org/3/library/asyncio.html)
[![Semantic Search](https://img.shields.io/badge/Semantic%20Search-FAISS%2BScikit--learn-blue.svg)](https://github.com/facebookresearch/faiss)
[![GitHub Issues](https://img.shields.io/github/issues/simonpierreboucher02/llm_flow_notebook-main)](https://github.com/simonpierreboucher02/llm_flow_notebook-main/issues)
[![GitHub Forks](https://img.shields.io/github/forks/simonpierreboucher02/llm_flow_notebook-main)](https://github.com/simonpierreboucher02/llm_flow_notebook-main/network)
[![GitHub Stars](https://img.shields.io/github/stars/simonpierreboucher02/llm_flow_notebook-main)](https://github.com/simonpierreboucher02/llm_flow_notebook-main/stargazers)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/simonpierreboucher02/llm_flow_notebook-main)](https://github.com/simonpierreboucher02/llm_flow_notebook-main/commits/main)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/simonpierreboucher02/llm_flow_notebook-main)](https://github.com/simonpierreboucher02/llm_flow_notebook-main)
[![GitHub Language](https://img.shields.io/github/languages/top/simonpierreboucher02/llm_flow_notebook-main)](https://github.com/simonpierreboucher02/llm_flow_notebook-main)

This repository provides a modular framework for interacting with multiple language model APIs (OpenAI, Anthropic, and Mistral). It enables text generation, embedding retrieval, semantic search, and multi-step prompt flows, allowing users to leverage various models in a structured workflow.

## 🚀 Features

- **🤖 Multi-Model Support**: Seamlessly switch between OpenAI GPT-4/GPT-3, Anthropic Claude, and Mistral AI
- **🔍 Semantic Search**: Advanced embedding-based search using FAISS and scikit-learn
- **⚡ Async Processing**: High-performance asynchronous operations for better throughput
- **🔄 Multi-Step Flows**: Design complex workflows with chained prompts and data processing
- **📊 Visualization**: Built-in flow visualization using Graphviz
- **🔐 Secure**: Environment variable management for API keys
- **📝 Token Management**: Intelligent token counting and text splitting

## 📁 Repository Structure

- **[LLM_FLOW_1.ipynb](https://github.com/simonpierreboucher02/llm_flow_notebook-main/blob/main/LLM_FLOW_1.ipynb)**: Introduces the modular framework, including setup for different language model APIs and initial examples of text generation and embedding retrieval.
- **[LLM_FLOW_2.ipynb](https://github.com/simonpierreboucher02/llm_flow_notebook-main/blob/main/LLM_FLOW_2.ipynb)**: Expands on the framework to include multi-step prompt flows and complex workflows, demonstrating semantic search, text processing, and advanced interactions.

## 🎯 Overview

The notebooks implement a flexible and dynamic workflow for:
- **Text Generation**: Generate responses and creative content with various LLMs.
- **Embedding Retrieval**: Retrieve embeddings for documents and perform similarity searches.
- **Semantic Search**: Use embeddings and cosine similarity to find relevant information.
- **Multi-Step Prompt Flows**: Design custom workflows that chain multiple prompts and processes together.

This setup enables efficient text generation and data processing with multiple models in a single, cohesive workflow.

## 🛠️ Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Python 3.8+**
- **Jupyter Notebook**
- API keys for each language model service (OpenAI, Anthropic, Mistral)
- Required dependencies as listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher02/llm_flow_notebook-main.git
   cd llm_flow_notebook-main
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**: Open Jupyter by navigating to the repository folder and running:
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**: Open either `LLM_FLOW_1.ipynb` or `LLM_FLOW_2.ipynb` to explore the modular framework and interact with the LLM APIs.
3. **Follow Instructions**: Each notebook includes code and setup instructions for different API interactions and use cases.

## 💡 Use Cases

- **Modular Text Generation**: Use different LLMs interchangeably for text creation tasks.
- **Cross-Model Embedding and Semantic Search**: Retrieve embeddings from various models and apply semantic search techniques.
- **Custom Prompt Workflows**: Design and implement complex multi-step workflows that chain prompts across different models and APIs.

## 🤝 Contributing

We welcome contributions! Feel free to submit issues or pull requests to add features, fix bugs, or improve the framework.

## 📄 License

This repository is licensed under the MIT License.

---

**Author**: [Simon-Pierre Boucher](https://github.com/simonpierreboucher02)  
**Repository**: [https://github.com/simonpierreboucher02/llm_flow_notebook-main](https://github.com/simonpierreboucher02/llm_flow_notebook-main)


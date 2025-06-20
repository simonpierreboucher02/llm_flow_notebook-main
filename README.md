# LLM Flow Notebook
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![GitHub Issues](https://img.shields.io/github/issues/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/issues)
[![GitHub Forks](https://img.shields.io/github/forks/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/network)
[![GitHub Stars](https://img.shields.io/github/stars/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/stargazers)

This repository provides a modular framework for interacting with multiple language model APIs (OpenAI, Anthropic, and Mistral). It enables text generation, embedding retrieval, semantic search, and multi-step prompt flows, allowing users to leverage various models in a structured workflow.

## Repository Structure

- **[LLM_FLOW_1.ipynb](https://github.com/simonpierreboucher/llm_flow_notebook/blob/main/LLM_FLOW_1.ipynb)**: Introduces the modular framework, including setup for different language model APIs and initial examples of text generation and embedding retrieval.
- **[LLM_FLOW_2.ipynb](https://github.com/simonpierreboucher/llm_flow_notebook/blob/main/LLM_FLOW_2.ipynb)**: Expands on the framework to include multi-step prompt flows and complex workflows, demonstrating semantic search, text processing, and advanced interactions.

## Overview

The notebooks implement a flexible and dynamic workflow for:
- **Text Generation**: Generate responses and creative content with various LLMs.
- **Embedding Retrieval**: Retrieve embeddings for documents and perform similarity searches.
- **Semantic Search**: Use embeddings and cosine similarity to find relevant information.
- **Multi-Step Prompt Flows**: Design custom workflows that chain multiple prompts and processes together.

This setup enables efficient text generation and data processing with multiple models in a single, cohesive workflow.

## Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Python 3.8+**
- **Jupyter Notebook**
- API keys for each language model service (OpenAI, Anthropic, Mistral)
- Required dependencies as listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher/llm_flow_notebook.git
   cd llm_flow_notebook
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

## Use Cases

- **Modular Text Generation**: Use different LLMs interchangeably for text creation tasks.
- **Cross-Model Embedding and Semantic Search**: Retrieve embeddings from various models and apply semantic search techniques.
- **Custom Prompt Workflows**: Design and implement complex multi-step workflows that chain prompts across different models and APIs.

## Contributing

We welcome contributions! Feel free to submit issues or pull requests to add features, fix bugs, or improve the framework.

## License

This repository is licensed under the MIT License.


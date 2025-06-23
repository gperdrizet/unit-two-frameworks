# Unit two: frameworks for AI agents

HuggingFace Agents Course - Unit 2: Introduction to Agentic Frameworks demonstration notebooks.

- My main GitHub repository for the course: [HuggingFace agents course](https://github.com/gperdrizet/hf-agents-course).
- Unit two introduction page on HuggingFace: [Introduction to Agentic Frameworks](https://huggingface.co/learn/agents-course/unit2/introduction)

## Running

To run the notebooks, you need to provide the following credentials via environment variables. The method to do so will depend on the environment in which you are running (see below).

1. `HF_TOKEN`: A HuggingFace access token with repository read/write and inference permission
2. `LANGFUSE_PUBLIC_KEY`: A Langfuse public key
3. `LANGFUSE_SECRET_KEY`: A Langfuse secret key
4. `OPENAI_API_KEY`: An OpenAI API key

All of these can be generated using a free-tier account from the respective providers.

There are two options to run the notebooks:

### 1. GitHub codespace (recommended)

Fork a copy of the repository, then add the credentials mentioned above as codespace secrets: settings → Secrets and variables → Codespaces → New repository secret. Start a new codespace on main.

### 2. Local

Clone the repository, create a virtual environment and install requirements.txt via pip. Provide the credentials mentioned above as environment variables. Note: for the vision agent to work, you need to have Chromium installed and chromium-webdriver configured properly.

## Notebooks

### 2.1. smolagents

1. [Code Agents](https://github.com/gperdrizet/unit-two-frameworks/blob/main/2.1-smolagents/code_agents.ipynb)
2. [Tool Calling Agents](https://github.com/gperdrizet/unit-two-frameworks/blob/main/2.1-smolagents/tool_calling_agents.ipynb)
3. [Tools](https://github.com/gperdrizet/unit-two-frameworks/blob/main/2.1-smolagents/tools.ipynb)
4. [Retrieval Agents](https://github.com/gperdrizet/unit-two-frameworks/blob/main/2.1-smolagents/retrieval_agents.ipynb)
5. [Multiagents](https://github.com/gperdrizet/unit-two-frameworks/blob/main/2.1-smolagents/multiagent_notebook.ipynb)
6. [Vision Agents](https://github.com/gperdrizet/unit-two-frameworks/blob/main/2.1-smolagents/vision_agents.ipynb)

### 2.2. LLamaIndex

### 2.3. LangGraph

# Intro: GEN-AI Playground
This is a repository in which I aim to cluster/document the various experiments and labs in the GEN-AI space. 

The sections below cover what was already tried or worked on. Also, the idea is to structure the quite extensive domain a bit in manageable pieces. Where applicable, specific explanations are to be found in the respective markdown-files. 


# Ollama
Ollama is a runner for LLM models. It allows the local execution of LLM models, in the case used here this is done inside a docker container. 
* https://github.com/ollama/ollama
* Official Docker Image: https://hub.docker.com/r/ollama/ollama
* List of models: https://ollama.com/search

Refer to the respective cheatsheet markdown for specific instructions. 


# Open WebUI
Web Interface that can be used for prompting, and many more things. 
Open WebUI provides a user-friendly interface for interacting with large language models and managing prompts. When running in a local Docker container using the `open-webui` image, the UI is accessible by default at [http://localhost:3000](http://localhost:3000).
* GitHub: https://github.com/open-webui/open-webui
* Open WebUI Docs: https://docs.openwebui.com/
* Ollama / Open WebUI Docker Compose example: https://github.com/open-webui/open-webui/blob/main/docker-compose.yaml


# Langflow
Langflow is a visual programming interface for building, testing, and deploying LLM-powered workflows. It enables users to design and connect components such as prompts, models, and tools using a drag-and-drop interface. In this lab, Langflow was deployed in a Docker container named `langflow`. Once the container is running, Langflow can be accessed via a web browser at [http://localhost:7860](http://localhost:7860) by default. For lab environments, ensure that the container's port is properly mapped and that access controls are in place if the environment is shared.
* Docs: https://docs.langflow.org/about-langflow
* Docker-specific Deployment topics: https://docs.langflow.org/deployment-docker
* Ollama-specific Components: https://docs.langflow.org/bundles-ollama


# Vast.AI
* Docs: https://docs.vast.ai/
* Templates provided: https://cloud.vast.ai/templates/
* Langflow + Ollama Container: https://cloud.vast.ai/template/readme/a6c0d99e368382d2f3cfdc217c0c7204


# Next steps

* Deployment on Vast.AI (Bigger hardware)
    - Read through docs
    - Find out how Volumes work
    - Find out what the CLI Tool does
    - Find out how to get data in/out efficiently. (re-deployments)

* LLM Model Understanding in General 
    - Context Size, Benchmarks, Capabilities
    - How exactly does Reasoning Work? 
    - Understand what Fine-Tuning is, How training works, Training Strategies
    - Understand what model-alignment is
    - Understand Tool usage in LLM's (example, background, etc.)
    - How to measure quality in LLM Use cases? 
    - How to estimate costs, impact of token size
    - Can an llm understand a chart (i.e. bcg matrix, drawings of models and frameworks, drawings of data models)
    - Legal Issues, Business Model, …?
    - Categorize, Understand Information Sources to follow, track

* Embeddings: 
    - Understand embeddings, and portability of embeddings. 
    - Understand the different models that are used for Embeddings. What are the differences? 
    - What are the techniques used to generate embeddings from complex file types (pdf, word, web pages, ...)

* Vector Databases, Knowledge Graphs
    - Implement a working example. 
    - How does one browse, maintain the content of a knowledge graph? 
    - What are the differences of the available products? What are differentiating aspects? 
    - How does one implement a knowledge graph? i.e. Neo4j?
    - How can Knowledge Graphs be viewed? 

* Multi-Agent Settings
    - List / Unterstand differences of the different frameworks. 
        - Microsoft AutoGen
    - Context Handling: How are Agents collectively working on a topic? 
    - Design patterns? There are multiple strategies or patterns that are usually followed.
    - Welchen "Führungsstil" benötigen AI Agenten?

* Technical Topics, Bolts and Pieces, Service Providers, "Facilitator"-Topics: 
    - Huggingface: https://huggingface.co/
        - Offering ?
        - How to find a model for a specific use case
    - Task mining, ui path, automate ui interactions
    - Understand Components with which Langflow was built
    - Understand Components with which Ollama was built
    - MCP Server Protocol
    - Protocols for agent to agent communication (a2a)
    - How to run/implement scraping (state of the art, what is realistic)
    - API Calls, API Integration into Agents, LLm usage (Tools)

* Potential Use Cases
    - Ideas: 
        - Optimize/Automate my own research
        - Learn a language
        - Generate Software (Apps, Codebases, …)
        - A simple company use case in CH / z.B. Vereinsverwaltung, Onlineshop, …
        - Online Dating?
        - Corporate Training, Teambuilding, MA Rating, etc.
        - Backwards-calculation of a business case (not only as text, but in knowledge graph, or in excel)
        - LLM, welches policies, guidelines etc. zugänglicher formuliert.
    - Meta-Level: find a use case that ...
        - Has a potential user base
        - Can be used as demonstrator
        - Maybe is a bit provocant…?
        - These: Es soll möglich werden das eine 1 personen firma 1 bn USD umsatz macht -> Interesting…
        - Guideline: Do not place agents in existing structures, or re-model what humans are doing today. Instead, re-think the process (how would one build it, based on the agents possibilities? 








# Example: 3-Level Bullet Points

- Level 1
    - Level 2
        - Level 3
- Another Level 1
    - Another Level 2
        - Another Level 3
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
* Embeddings
* Tool usage in LLM's (example, background, etc.)
* Huggingface: https://huggingface.co/


# Example: 3-Level Bullet Points

- Level 1
    - Level 2
        - Level 3
- Another Level 1
    - Another Level 2
        - Another Level 3
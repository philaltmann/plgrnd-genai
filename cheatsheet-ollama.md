## Usage and Examples

Ollama provides a command-line interface for managing and running LLM models locally. By default, Ollama's API is accessible at `http://localhost:11434`. When running inside a Docker container, models are typically stored in `/root/.ollama/models`. Below are common usage patterns and maintenance commands.

### Pulling Models

To download a model for local use:
```sh
ollama pull llama2
ollama pull mistral
```

### Starting a Model

To start serving a model (the server will listen on port 11434 by default):
```sh
ollama run llama2
```

### Stopping a Model

To stop a running model:
```sh
ollama stop llama2
```

### Listing Available Models

To see all models currently available locally:
```sh
ollama list
```

### Removing a Model

To delete a model from local storage:
```sh
ollama rm llama2
```

### Running in Docker

When using the official Docker image, mount a volume to persist models:
```sh
docker run -d -p 11434:11434 -v ollama_models:/root/.ollama/models ollama/ollama
```

Refer to the [Ollama documentation](https://github.com/ollama/ollama) for more advanced usage and API details.


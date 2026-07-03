# AI Coding Agent

A command-line AI agent built with Python that can read, write, and execute code within a controlled working directory. Powered by the OpenRouter API.

## Setup

1. Clone the repo and install dependencies:
```bash
uv sync
```

2. Create a `.env` file with your OpenRouter API key: OPENROUTER_API_KEY='your_api_key_here'
   
## Usage

```bash
uv run main.py "your prompt here" --verbose
```

Built as part of the [Boot.dev](https://boot.dev) AI Agent course.

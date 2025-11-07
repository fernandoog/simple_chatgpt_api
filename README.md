# Simple ChatGPT API

A simple command-line interface to interact with OpenAI's ChatGPT API.

## Description

This is a lightweight Python script that allows you to interact with ChatGPT from the command line. It uses OpenAI's API to generate text responses based on prompts you provide.

## Features

- Simple command-line interface
- Direct integration with OpenAI's GPT API
- Easy to use and configure

## Requirements

- Python 3
- OpenAI API key
- `openai` Python package

## Installation

1. Install the OpenAI Python package:
```bash
pip install openai
```

2. Get your API key from [OpenAI Platform](https://platform.openai.com/account/api-keys)

3. Edit `chatgpt_api.py` and replace the empty string with your API key:
```python
openai.api_key = "your-api-key-here"
```

## Usage

Run the script with a prompt as an argument:

```bash
python chatgpt_api.py "say hello world"
```

Or with any other prompt:

```bash
python chatgpt_api.py "Explain quantum computing in simple terms"
```

## Configuration

The script uses the following default settings:
- Engine: `davinci`
- Max tokens: 1024
- Temperature: 0.5

You can modify these settings in the `generar_respuesta()` function.

## Author

Fernando Ortega Gorrita (@fernandoog)

## License

See LICENSE file for details.

## Note

This project uses an older version of the OpenAI API. For newer implementations, consider using the `openai` Python library with the updated API endpoints.

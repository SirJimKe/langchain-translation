# LangChain Translation Example

This is a simple Python script that uses **LangChain** with **OpenAI's GPT-4o-mini** to translate text from English into any language.  
It demonstrates how to use **ChatPromptTemplate** to structure prompts dynamically.

## Features
- Uses environment variables for API keys (no hardcoding secrets).
- Demonstrates LangChain's `ChatPromptTemplate` for dynamic prompt creation.
- Simple CLI input for language and text.
- Clean separation between prompt creation and model invocation.

## Requirements
- Python 3.9+
- An OpenAI API key (get one at [platform.openai.com](https://platform.openai.com/))

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SirJimKe/langchain-translation.git
   cd langchain-translation

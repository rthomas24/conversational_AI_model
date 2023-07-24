# Simplified Conversational AI model

Sophisticated Conversational AI model, leveraging the power of Langchain and OpenAI's cutting-edge language model. This model is uniquely designed to operate on custom imported data, enabling personalized and context-aware interactions. By integrating Langchain, it efficiently manages conversation flows, ensuring coherent, natural language exchanges. The use of OpenAI's language model allows the system to generate remarkably human-like responses.

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai chromadb
```
Modify `constants.py` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys)

Place your own data into `data/data.txt`.

## Example
Test reading `data/data.txt` file.
```
> python simplegpt.py
Question: "Who had the most blocks"
Kentavious Caldwell Pope of the Denver Nuggets had the most blocks with 3
```

# Simplified Conversational AI model ready for use

This Script will use ChatGPT to answer questions about data you upload.

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai
```
Modify `constants.py` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys)

Place your own data into `data/data.txt`.

## Example
Test reading `data/data.txt` file.
```
> python simplegpt.py
Question: "Who had the most blocks"
Kentavious Caldwell Pope of the Denver Nuggets had the most blocks with 3..
```

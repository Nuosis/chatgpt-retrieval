# chatgpt-retrieval

Simple script to use ChatGPT on your own files.

Here's the [YouTube Video](https://youtu.be/9AXP7tCI9PI).

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured
```
Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

Place your own data into `data/data.txt`.

## Test Implementation
Test reading `data/data.txt` file.
```
> python3 chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
```

Test reading `data/cat.pdf` file.
```
> python3 chatgpt.py "what is my cat's name"
Your cat's name is Muffy.
```
## LOAD MODEL
python3 chatgpt.py

## QUIT
quite, exit or q

## USAGE
1 create xml of FileMake file (DDR or Create XML copy) 
2 move this file into the data directory
3 start model and query
# Building Systems with the ChatGPT API
This repository is a part of Building Systems with the ChatGPT API course from [deeplearning.ai](https://deeplearning.ai). You can access the course [here](https://learn.deeplearning.ai/chatgpt-building-system/lesson/1/introduction).<br>
The repository contains the jupyter notebook files from the course.<br>
You can go through the notebooks to:<br>
- Level up your use of LLMs.
- Learn to break down complex tasks, automate workflows, chain LLM calls, and get better outputs.
- Efficiently build multi-step systems using large language models.
- Learn to split complex tasks into a pipeline of subtasks using multistage prompts.
- Evaluate your LLM inputs and outputs for safety, accuracy, and relevance.<br>
<br>
In all of these notebooks, I have used the following method/format to setup my OpenAI API key:<br><br>

```python
import openai
import os

from dotenv import load_dotenv, find_dotenv
_ = load_dotenv(find_dotenv()) # read local .env file

openai.api_key  = os.getenv('OPENAI_API_KEY')
```
<br>
This is a recommended method as in this way there is no chance of exposing your OpenAI API key to the world.<br><br>
An alternate way is to directly configure the key as:<br><br>

```python
import openai
openai.api_key = "sk-..."
```

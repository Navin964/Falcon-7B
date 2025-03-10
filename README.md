## Chatbot using TII Falcon-7B-instruct LLM

This repository contains code to create a chatbot using `Falcon-7B-instruct` LLM (Language Model) and deploy it with a Gradio interface for easy interaction. Falcon-7B is an open-source Language Model that can generate text based on input prompts (link: https://huggingface.co/tiiuae/falcon-7b-instruct )

### Installation ⚙️
Before running the chatbot, you need to install the necessary dependencies.

Install the required packages using pip:
* pip install -q -U bitsandbytes
* pip install -q -U git+https://github.com/huggingface/transformers.git
* pip install -q -U git+https://github.com/huggingface/peft.git
* pip install -q -U git+https://github.com/huggingface/accelerate.git
* pip install -q -U einops
* pip install -q -U safetensors
* pip install xformers
* pip install langchain
* pip install gradio

Here, we install the necessary libraries to work with the `Falcon-7B LLM` and Gradio to build the user interface.
The Falcon-7B model and tokenizer is loaded with `4-bit quantization`, making it efficient for low RAM environments by using NF4 dtype, which stands for Normal Float 4, which is introduced in the QLoRA paper: https://huggingface.co/blog/4bit-transformers-bitsandbytes


### Usage 🪄
To use the Falcon-7B LLM chatbot:
* Install the required dependencies as mentioned above.
* Run the code provided in the Jupyter Notebook.
* The Gradio interface will open in your default web browser.
* Enter a text prompt in the provided input box and press Enter to get the chatbot's response.

![image](https://github.com/Navin964/Falcon-7B/assets/73225962/219465d0-0d6f-45d2-805c-3bd67e6e156f)

Enjoy chatting with your Falcon-7B LLM-powered chatbot! 😉

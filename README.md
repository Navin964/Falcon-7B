## Chatbot using Falcon-7B LLM
This repository contains code to create a chatbot using Falcon-7B LLM (Language Model) and deploy it with a Gradio interface for easy interaction. Falcon-7B is an open-source Language Model that can generate text based on input prompts.

### Installation ⚙️
Before running the chatbot, you need to install the necessary dependencies. The following instructions are for Python:

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
 
Here we install the necessary libraries to work with the `Falcon-7B LLM`, along with Gradio for building the user interface.
The Falcon-7B model and tokenizer is loaded with `4-bit quantization`, making it efficient for low RAM environments by using NF4 dtype stands for Normal Float 4 which is introduced in the QLoRA paper: https://huggingface.co/blog/4bit-transformers-bitsandbytes


### Usage 🪄
To use the Falcon-7B LLM chatbot:
* Install the required dependencies as mentioned above.
* Run the code provided in the main script or Jupyter notebook.
* The Gradio interface will open in your default web browser.
* Enter a text prompt in the provided input box and press Enter to get the chatbot's response.
* Please note that the Falcon-7B LLM might take some time to respond, depending on the complexity of the prompt and the model's size.

Enjoy chatting with your Falcon-7B LLM-powered chatbot! 😉

# Intel-Unnati-GenAI-Chatbot

## Introduction to GenAI and Simple LLM Inference on CPU and fine-tuning of LLM Model to create a Custom Chatbot

### Description:
This problem statement is designed to introduce beginners to the exciting field of Generative Artificial
Intelligence (GenAI) through a series of hands-on exercises. Participants will learn the basics of GenAI,
perform simple Large Language Model (LLM) inference on a CPU, and explore the process of fine-tuning
an LLM model to create a custom Chatbots.

### Major Challenges:

1. Pre-trained Language Models can have large file sizes, which may require significant storage space
and memory to load and run.
2. Learn LLM inference on CPU.
3. Understanding the concept of fine-tuning and its importance in customizing LLMs.
4. Create a Custom Chatbot with fine-tuned pre-trained Large Language Models (LLMs) using Intel AI
Tools.

### Outcomes:

1. Participants will gain a foundational understanding of Generative AI and its applications.
2. Participants will be able to perform simple LLM inference on a CPU and understand the process of
fine-tuning LLMs for custom applications.
3. Participants will have to create a 5-page report on Problem, Technical Approach and Results. 

### Creation of environment

1. Creation of environment and activating it
```bash
conda create -n itrex python=3.10 -y
conda activate itrex
```
2. Installing intel-extention-for-transformers
```bash
pip install intel-extension-for-transformers
```
3. Cloning Github repo
```bash
git clone https://github.com/intel/intel-extension-for-transformers.git
cd ./intel-extension-for-transformers/intel_extension_for_transformers/neural_chat/
```
4. Install Requirements
```bash
pip install -r requirements_cpu.txt
pip install -r requirements.txt
```
5. Logging into huggingface and providing access tokens
```bash
huggingface-cli login
```
6. Installing jupyter and creating a kernel
```bash
python3 -m pip install jupyter ipykernel
python3 -m ipykernel install --name neural-chat-1 --user
```

### Dataset
We use the Alpaca dataset [https://github.com/tatsu-lab/stanford_alpaca] from Stanford University as the general domain dataset to fine-tune the model. This dataset is provided in the form of a JSON file, alpaca_data.json. In Alpaca, researchers have manually crafted 175 seed tasks to guide text-davinci-003 in generating 52K instruction data for diverse tasks.


### View Project
The project link: [https://youtu.be/tL701g38ZMg]

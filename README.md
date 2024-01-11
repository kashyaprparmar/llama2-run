# LLM (Large Language Model) Inference using Meta's Llama-2-7b

This repository contains Python code showcasing the utilization of Meta's Llama-2-7b, a state-of-the-art large language model, for text generation and inference. The provided code leverages the Hugging Face Transformers library to interact with the Llama-2-7b model.

## Overview

The code demonstrates the following key functionalities:

1. **Environment Setup:**
   - Checks for the availability of GPU and sets the appropriate device.
   - Configures quantization to load the large model efficiently with reduced GPU memory usage.

2. **Hugging Face Initialization:**
   - Requires a valid Hugging Face access token for authentication.
   - Initializes the Llama-2-7b model using the AutoModelForCausalLM class from the Transformers library.
   - Enables evaluation mode for model inference.

3. **Tokenizer Initialization:**
   - Initializes the tokenizer using the AutoTokenizer class from Transformers.

4. **Text Generation Pipeline:**
   - Utilizes the Transformers pipeline for text generation with specified parameters.
   - The provided example generates text explaining the difference between a Data Lakehouse and a Data Warehouse.

5. **Prints the Generated Text:**
   - Prints the generated text based on the input prompt.

## Usage

1. **Requirements:**
   - Ensure you have the required dependencies installed. You can install them using:
     ```bash
     pip install transformers==4.33.0 accelerate==0.22.0 einops==0.6.1 langchain==0.0.300 xformers==0.0.21 bitsandbytes==0.41.1 sentence_transformers==2.2.2 chromadb==0.4.12
     ```

2. **Hugging Face Token:**
   - Acquire a Hugging Face access token from [Hugging Face Tokens](https://huggingface.co/settings/tokens).

3. **Configuration:**
   - Replace `<YOUR_HUGGING_FACE_ACCESS_TOKEN>` in the code with your actual Hugging Face access token.

4. **Run the Code:**
   - Execute the provided Python script for LLM inference.

Feel free to customize the input prompt or explore additional use cases by modifying the code as needed.

**Note:** Ensure you comply with the licensing terms and usage policies of Meta's Llama-2-7b and Hugging Face.

For further inquiries, contact me

---

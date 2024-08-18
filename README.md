# Fine-Tuning LLaMA 2 with QLoRA and PEFT  

This repository contains a script to fine-tune the LLaMA 2 model using Quantized Low-Rank Adaptation (QLoRA) and Parameter-Efficient Fine-Tuning (PEFT) techniques. The implementation utilizes the Hugging Face Transformers library and other associated modules.  

## Overview  

The aim of this project is to fine-tune the LLaMA 2 model on a custom instruction dataset to achieve better performance on specific conversational tasks. We leverage 4-bit quantization for efficient training while utilizing LoRA to adapt the model effectively.  

## Requirements  

Make sure you have the following libraries installed:  

```bash  
pip install -q accelerate==0.21.0 peft==0.4.0 bitsandbytes==0.40.2 transformers==4.31.0 trl==0.4.7

## Multi-agent Approach to Generating More Accurate Responses

This is an attempt at implementing a multi-agent solution for generating more accurate/bias-free responses. This was inspired by the work done by Li et al, 2024 (Improving LLM performance through ensembling) and Chen et al, 2024 (Scaling laws of Compound Inference Systems). As observed by Chen et al (and anecdotally), simpler queries tend to speed up while open ended or complex prompts result in inconsistent generation times. 

A simple similarity based scoring is also implemented here to pick the "best" response out of all the generated responses. 

To try this on your machine, ensure the Phi3 model's gguf file is in the same directory as the notebook. 

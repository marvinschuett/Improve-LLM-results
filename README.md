### Getting the best out of LLMs
The script highlights the decising factors that influence the performance of LLMs.

Specifically, it explores three different techniques that share the same goal, namely to increase the performance of the chosen LLM. These techniques are:

1. Prompt engineering
2. Retrievel Augment Generation (RAG)
3. Selecting the appropriate LLM

(Finetuning an LLM, another prominent option, is out of scope of this exercise. Also parameters such as temperature, i.e. "creativity" won't be altered for simplicity.)

### Setup
The LLM will receive three different questions that increase in complexity:

1. What is 1000*55 (simple and deterministic)
2. Who is the most powerful character in Star Wars? (simple but subjective, requiring reasoning)
3. What is the effect of wind turbines on property values? (complex and potentially not in the training data of the LLM)

Three different LLMs are tested:
1. Gemma3:1b "Lightweight, efficient open model ideal for local inference and mobile deployment. https://ollama.com/library/gemma3:1b

2. llama3.1:8b "Llama 3.1 is a new state-of-the-art model from Meta available in 8B, 70B and 405B parameter sizes." https://ollama.com/library/llama3.1:8b

3. Mistral:7b High throughput open model, strong in code and factual Q&A with fast inference.



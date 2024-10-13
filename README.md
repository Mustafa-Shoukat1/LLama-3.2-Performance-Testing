![image](https://github.com/user-attachments/assets/611314aa-192f-4058-96d9-ce923d6ea664)

# Answer 1: 
The model states there are two 'r's in "strawberry," but it's actually counting tokens, not letters. The model sees the individual letters of "strawberry" as tokens, leading to the discrepancy.

# Answer 2: 
When comparing 9.11 and 9.9, the decimal part should be compared. 0.11 is greater than 0.09, so 9.11 is greater than 9.9. The largest Llama 3.1 405b model returns an incorrect result because of tokenization. It splits 9.11 into three tokens: "9", ".", ".11", while 9.9 is split into two tokens: "9", ".", "9". Correct tokenization of the full numbers could lead to better model accuracy.



# Overview
- **Multimodal Use Case.ipynb**: Demonstrates various use cases of Llama 3.2's multimodal capabilities, such as interpreting images and solving visual reasoning tasks.
- **Multimodality Experiment of Llama 3.2.ipynb**: Contains experiments showcasing advanced image reasoning abilities and how Llama 3.2 handles different visual inputs.
- **Tokenization Experimentation.ipynb**: Explores the use of the tiktoken tokenizer with Llama, highlighting its expanded 128k vocabulary and multilingual support.
- **Tool Calling Functionality Llama.ipynb**: Provides examples of prompting Llama to call both built-in and custom tools, including web search and mathematical problem-solving.

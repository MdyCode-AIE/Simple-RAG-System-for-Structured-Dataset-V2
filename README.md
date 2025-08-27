Hi,

This a improve version of from my first RAG system for structured data. The code utilize FastModel library (with Gemma3 LLM) alongside Json context input. I belive Json context input
is very good for LLM digestion. In fact, even without vector search for limiting the context window, the LLM can still provide a good response based on the Json context given.
Additionally, the type Json format used is quite optimize (the format being 'header':'data',header :'data') for LLM query.

Thats all thanks!

This code will use TruthfulQA as sample (https://huggingface.co/datasets/truthfulqa/truthful_qa).

Some Reference code:

https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Gemma3_(4B).ipynb (Unsloth Fastmodel library)

https://huggingface.co/spaces/MuntasirHossain/RAG-PDF-Chatbot

https://github.com/MdyCode-AIE/Simple-RAG-System-for-Structured-Dataset

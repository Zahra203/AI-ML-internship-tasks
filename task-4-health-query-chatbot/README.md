# Task 4: Health Query Chatbot

This project is a simple and safe chatbot that answers general health-related questions using an LLM (Large Language Model). Built for Task 4 of the AI Health Assistant assignment.

##  Technologies Used
- Hugging Face Transformers (Flan-T5)
- LangChain
- FAISS Vector Store
- Python

## key features

#The chatbot can answer health-related queries accurately using an LLM.
#- Prompt engineering greatly influences the tone, safety, and clarity of responses.
#- FAISS + LangChain enabled fast and reliable document-based context retrieval.
#- A basic keyword-based safety filter was implemented to block harmful queries.
#- Sample questions produced friendly, clear answers grounded in the source PDF

##  Sample Questions
- "What causes a sore throat?"
- "Is paracetamol safe for children?"

## Safety
The chatbot does **not** provide medical diagnoses or treatment advice.

##  Required Libraries
```txt
langchain
langchain-community
langchain-huggingface
faiss-cpu
transformers
sentence-transformers
pypdf
openai
tqdm
```

##  Book Used for Reference
`The_GALE_ENCYCLOPEDIA_of_MEDICINE_SECOND.pdf`


##  Files
- `health_query_chatbot.ipynb`: Full notebook 
-  refference book
- `README.md`: Task overview and summary


##  Future Enchancements
- more books will be added for more accurate queries answers 
-  UI will also be added for better user interaction
  



# AI-Powered HR Assistance with Langchain, Chroma DB, Gradio, and OpenAI/Gemini APIs
Crafting an AI-Powered HR Assistant: A Use Case for Nestle’s HR Policy Documents

## Overview 
The project aims to create a conversational chatbot that responds to user inquiries using PDF document information. It requires proficiency in extracting and converting text into numerical vectors, establishing an answer-finding mechanism, and designing a user-friendly chatbot interface with Gradio. Additionally, the initiative emphasizes structuring inquiries for clear communication and deploying the chatbot for practical use, guaranteeing the system's accessibility and efficiency in meeting user needs.
Instructions

## Situation 
As a developer, you have received the critical task of improving the operational efficiency of Nestlé's human resources department, a leading multinational corporation. Your toolkit includes cutting-edge conversational AI technology, Python libraries, the powerful GPT model from OpenAI, and the user-friendly Gradio UI. Your mission is to integrate these advanced tools seamlessly to transform HR processes, creating a more streamlined and efficient workflow within the Nestlé organization.

## Task 
Your task is to develop a conversational chatbot. This chatbot must answer queries about Nestlé's HR reports efficiently. Use Python libraries, OpenAI's GPT model, and Gradio UI. These tools will help you create a user-friendly interface. This interface will extract and process information from documents. It will provide accurate responses to user queries.

## Action
### Setting up the programming environment 
-	Install Python
-	Install Langchain package
- Install ChromaDB
- Get OpenAI API key
- Install Langchain OpenAI package
- Get Gemini API key
- Install Langchain Gemini package
You can check the packages.txt file in this repository for the list of required packages and their versions.

### Processing text documents
-	Download and store nestle_hr_policy.pdf PDF file on local storage.
-	Process and load PDF file using pyPDFLoader
-	Join text from all pages

### Creating text vector representations 
- Split the file using recursive text splitter.
- Convert the text into vectors using OpenAI embedding,
- Persist the vector data into Chroma DB

### Building a question-answering system
- Build the QA system using langchain RetrievalQAChain and Open AI chat model
- Develop UI using Gradio

## Output

### With OpenAI 

##### Prompt 1:
![alt text](https://github.com/GauravRachchh/RAG/blob/main/img/prompt1_openAI_chatbot.jpg?raw=true)
##### Prompt 2:
![alt text](https://github.com/GauravRachchh/RAG/blob/main/img/prompt2_openAI_chatbot.jpg?raw=true)

### With Gemini

##### Prompt 1:
![alt text](https://github.com/GauravRachchh/RAG/blob/main/img/prompt1_gemini_chatbot.jpg?raw=true)
##### Prompt 2:
![alt text](https://github.com/GauravRachchh/RAG/blob/main/img/prompt2_gemini_chatbot.jpg?raw=true)

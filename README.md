# - Insurance Callbot
### GenAI Hackathon Project 

## 🔍 Abstract

Insurance call centers handle a high volume of repetitive, low-complexity customer requests, leading to long waiting times and operational overload.
This project presents an **AI-powered insurance callbot** that leverages **Generative AI, Agentic AI and NLP pipelines** to autonomously handle common customer inquiries, improving efficiency, responsiveness, and customer satisfaction.



## 🎯 Problem Statement

Insurance support teams receive thousands of daily calls related to:

* claim follow-ups
* contract and policy information
* frequently asked questions

These repetitive interactions result in:

* long customer wait times
* agent overload
* increased operational costs

➡️ **The challenge:** automate these requests while maintaining accuracy, clarity, and user trust.



## 🚀 Proposed Solution

We developed an **intelligent conversational callbot** capable of:

* understanding natural language queries
* identifying user intent
* extracting key entities and context
* interacting with internal business tools
* generating accurate, contextual responses

The system is designed to handle the majority of first-level customer interactions autonomously, escalating only complex cases to human agents.



## 🧠 System Architecture (High-Level)

1. User message ingestion (text or transcribed call input)  
2. Intent classification & entity extraction  
3. **Context retrieval via Retrieval-Augmented Generation (RAG)**  
   - Semantic search over a vector database (Chroma)  
   - Retrieval of relevant policy documents, FAQs, and knowledge base entries  
4. **Business data access & database querying**  
   - Structured queries to retrieve customer-specific or contract-related information  
5. Reasoning and response generation using Large Language Models (LLMs)  
6. Structured and contextual response delivery to the user  



## 🛠️ Technologies Used

* **Python**
* **Large Language Models (LLMs)**
* **LangChain**
* **LangGraph**
* **Multilingual Embeddings**
* **Chroma Vector Database**



## 📂 Deliverables

As required for the hackathon submission:

* **Source Code** – hosted in this GitHub repository
* **Presentation Slides** – available on Google Drive
* **Demo Video** – available on Google Drive
## 💡 Impact & Benefits

This solution enables:

* automation of repetitive customer requests
* reduced waiting times
* improved customer satisfaction
* increased productivity for call center agents
* scalable and multilingual customer support



## 👥 Team

Project developed for the **GenAI Morocco Hackathon – Capgemini**

| Name                | Role                                                |
| ------------------- | --------------------------------------------------- |
| **Manal Es-Sobhy**  | AI Agent Conception, NLP Pipeline, System Design, Prompt Engineering & Audio Input/Output Integration |
| **Nizar Baloubali** | AI Agent Conception, NLP Pipeline, System Design, Prompt Engineering & Audio Input/Output Integration |
| **Aya Lemzouri**    | Research, Documentation & Testing                   |

All team members contributed to the ideation, development, and presentation of this project.



## 🤝 Contributions & Collaboration

This repository represents a collaborative hackathon project.
All contributors are listed as collaborators and participated actively throughout the project lifecycle.



## ✨ Conclusion

This project demonstrates how **Generative AI–driven conversational agents** can transform insurance customer support by automating repetitive tasks, improving operational efficiency, and enhancing user experience at scale.

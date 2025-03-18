Vasuki - Advanced Conversational Agent

Vasuki is an advanced conversational agent designed to understand, process, and respond to user queries with remarkable accuracy. This project leverages state-of-the-art Natural Language Processing (NLP) techniques and Large Language Models (LLMs) to create a versatile tool for various applications, ranging from customer support to personal assistance.

![image](https://github.com/user-attachments/assets/d3d420bb-1193-4ace-9ed1-0994e6c767ab)

Overview

Features and Capabilities
	
1️⃣ Multi-Turn Conversational AI
Handles complex, back-and-forth conversations while maintaining context.
Supports real-time customer interactions with dynamic response adaptation.

2️⃣ Retrieval-Augmented Generation (RAG) Powered
Retrieves relevant information from structured and unstructured data sources.
Utilizes ChromaDB (Vector DB) + Hybrid Search (BM25 & Embeddings) for faster, more accurate responses.
Capable of handling both static document-based Q&A and real-time user queries.

3️⃣ Graph-Based Conversational Flow
Uses Nodes & Edges to structure conversations and decision-making.
Ensures intelligent flow management based on user intent.
Key Nodes & Edges:
GreetingNode – Welcomes users and starts the conversation.
UserInfoChainBasedEdge – Retrieves user information from databases.
AuthenticatedUserNode – Provides personalized responses based on user profile.
CallCustomerEdge & CallCustomerNode – Handles call requests to customer service agents.

4️⃣ Personalized Customer Support
Authenticates users via email or phone number.
Retrieves subscription details (Free vs. Premium users) and tailors responses accordingly.
Supports custom responses based on past interactions.

5️⃣ Voice-Enabled Customer Interaction
Supports call-based customer interactions via the CallCustomerEdge.
Can trigger automated customer support calls for premium users.

6️⃣ Dynamic Knowledge Base Integration
Allows document uploads to expand chatbot knowledge.
Uses vector search to find the most relevant information before generating a response.
Supports both static knowledge retrieval & live database lookups.

7️⃣ Advanced Error Handling & Validation
Implements Personalized Validators to ensure accuracy.
Uses fallback mechanisms for out-of-context queries.
If a query cannot be answered, it guides the user to rephrase their request.

8️⃣ Secure & Scalable
Built on LangChain + OpenAI APIs, ensuring enterprise-grade performance.
Supports fine-tuning & optimization via RLHF-like feedback.
Can scale from small businesses to enterprise-level deployments.

9️⃣ Multi-Platform Compatibility
Streamlit-based UI for easy deployment and testing.
Can be extended to API integrations, mobile apps, or enterprise chat solutions.

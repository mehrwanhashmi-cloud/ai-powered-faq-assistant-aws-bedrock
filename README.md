# ai-powered-faq-assistant-aws-bedrock
A production-style AI project demonstrating Retrieval-Augmented Generation (RAG) using Amazon Bedrock Knowledge Bases, S3, and vector embeddings.

## 🌐 Overview
This project builds an intelligent FAQ assistant that answers user questions based on custom data stored in Amazon S3.
Instead of hardcoding responses, the system uses **semantic search and AI generation** to retrieve and respond to queries in natural language.

## 🧠 Architecture
<img width="1122" height="1402" alt="bedrock" src="https://github.com/user-attachments/assets/6fe08b21-4832-458c-bfb1-747d951b06ac" />

## ⚙️ AWS Services Used

- Amazon Bedrock (Knowledge Bases + Foundation Models)
- Amazon S3 (Data storage)
- Amazon S3 Vectors (Vector database)
- AWS IAM (Secure access control)

## 🚀 Features

- Built a Retrieval-Augmented Generation (RAG) pipeline
- Converted unstructured FAQ data into vector embeddings
- Enabled semantic search (not keyword-based)
- Generated natural language responses using Amazon Nova
- Implemented secure architecture using IAM roles

- "What time does the daycare open?"
- "What should parents pack daily?"
- "When do kids sleep?" (semantic understanding)

## 📸 Screenshots
# Knowledge Base created
 <img width="1920" height="885" alt="knowledge base" src="https://github.com/user-attachments/assets/4568e038-0639-4c41-a517-75695130f2b9" />

#  S3 data source
 <img width="1916" height="899" alt="s3 data source synced" src="https://github.com/user-attachments/assets/b85994b0-26cc-4a74-9935-7ca507fabb6f" />

# Chatbot answering questions
  <img width="1920" height="887" alt="test responding" src="https://github.com/user-attachments/assets/4736637b-0bfe-4525-ba9d-43cebbef27ed" />

## 🎯 Key Learning
- How RAG works in real-world AI systems
- How embeddings power semantic search
- How to integrate AI with cloud-native architecture
- Importance of IAM and region alignment in AWS


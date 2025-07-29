# AI-Interactive-Resume-Interview
 AI Interview Simulation System
Interactive AI-based mock interview platform that analyzes your resume and job description to generate tailored multi-turn Q&A, simulate different company interview styles, and provide real-time feedback using GPT-4o and RAG.

 Project Overview
This project is a final project for the Graduate Institute of Computer and Communication Engineering, National Cheng Kung University, developed by JEN-WEI KUO 

It is designed to assist job seekers in preparing for interviews more effectively through generative AI. The system supports:

Resume and job description parsing

Multi-turn AI interview simulation

Company-style interview mode switching

Feedback and answer refinement

Retrieval-Augmented Generation (RAG) knowledge injection

 Core Technologies
Component	Technology
Language Model	OpenAI GPT-4o
Framework	LangChain
RAG Embedding	text-embedding-3-small, FAISS
UI Interface	Gradio
Parser	PyPDFLoader, UnstructuredLoader

 Project Structure
main_with_RAG.ipynb – Full interview system with RAG support.

main_without_RAG.ipynb – Simplified version without retrieval.

RAG_building.ipynb – FAISS vector DB construction and RAG pipeline.

 Getting Started
⚠ API Key Required
To run the interview simulation system, a valid OpenAI API Key is required. The key should be stored securely in your Colab Secrets environment.

 Setup Instructions (Colab)
Visit: OpenAI API Keys

Create a secret key (format: sk-...)

Open this notebook in Colab.

Click the  Secrets icon on the left sidebar.

Add a new secret:

Name: OpenAI (case-sensitive)

Value: your OpenAI key

Enable “Notebook access” for the key.

Run all cells in the notebook.
 If no key is provided or it is invalid, the system will not function properly.

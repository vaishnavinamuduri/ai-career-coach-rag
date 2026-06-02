# AI Career Coach RAG Architecture

## Version 1 Scope

Features:
- Resume Upload
- Job Description Upload
- Semantic Search
- Resume Matching
- Skill Gap Analysis
- Career Recommendations

## Architecture

User
↓
Streamlit Frontend
↓
FastAPI Backend
↓
Retrieval Layer
↓
Supabase pgvector
↓
Gemini LLM
↓
Response

## Data Flow

Resume PDF
↓
Text Extraction
↓
Chunking
↓
Embedding Generation
↓
Vector Storage

Job Description
↓
Text Extraction
↓
Chunking
↓
Embedding Generation
↓
Vector Storage

User Query
↓
Semantic Retrieval
↓
Gemini
↓
Answer

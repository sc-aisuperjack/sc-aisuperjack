# AI Superjack (Stefanos Cunning)

AI engineering portfolio focused on agentic systems, practical RAG, and data intelligence. Everything here is built to be demoable, testable, and easy to review.

## Live demos

PDF RAG Chat (multi-document RAG plus evaluation). https://pdfragchat.streamlit.app/  
GuestPulses (review intelligence for hospitality). https://guestpulses.streamlit.app/  
MongoLens (MongoDB exports to grounded insights and RAG). https://mongolens.streamlit.app/

## Featured projects

agentic-os. Agentic system template for orchestrator and worker services. Designed for extensible automation workflows, tool use, and scalable patterns that can be containerised. https://github.com/sc-aisuperjack/agentic-os  

pdfragchat. PDF to Markdown conversion without an LLM, LangChain chunking, OpenAIEmbeddings, local vector storage, multi-document chat, page-aware citations, caching, and retrieval evaluation metrics (MRR, Hit@k, Recall, Precision, MAP). https://github.com/sc-aisuperjack/pdfragchat  

mongolens. Connect to MongoDB, export collections, generate profiling and analysis, and chat with grounded answers backed by exported data. Streamlit demo included. https://github.com/sc-aisuperjack/mongolens  

guestpulses. Upload CSV or Excel reviews, map columns, extract sentiment and emotion signals, classify hospitality categories, and export insights. Streamlit demo included. https://github.com/sc-aisuperjack/guestpulses  

grabapic. Utility for downloading images from URL lists for dataset building and content workflows. https://github.com/sc-aisuperjack/grabapic  


## What I build

Agentic patterns (orchestrator, workers, tools, gateways), and RAG systems that do not skip the hard parts. Document ingestion pipelines (PDF, MongoDB exports, CSV and Excel), chunking and embeddings, caching and provenance metadata, grounded answering with citations, and retrieval evaluation to measure quality over time.

## Tech stack

Python, Streamlit, LangChain, OpenAI (embeddings and chat), FAISS and vector stores, MongoDB, FastAPI, Docker.

## How to run most repos

Create a virtual environment.  
python -m venv .venv  

Activate it.  
Windows: .venv\Scripts\activate  
macOS or Linux: source .venv/bin/activate  

Install dependencies.  
pip install -r requirements.txt  

Set environment variables.  
Copy .env.example to .env and set values such as OPENAI_API_KEY.  

Run the app.  
streamlit run app.py  

Run tests.  
pytest -q  

## Contact

Website. https://aisuperjack.com  
LinkedIn. https://www.linkedin.com/in/stefanoscunning/

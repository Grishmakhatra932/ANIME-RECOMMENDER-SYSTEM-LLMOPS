# Anime Recommendation System with MLOps

An AI-powered application that provides personalized anime recommendations based on users’ natural-language preferences. It uses semantic search and Retrieval-Augmented Generation (RAG) to understand user interests and return relevant recommendations.

## Key Features

- Personalized anime recommendations
- Natural-language preference input
- Semantic search using vector embeddings
- RAG-based recommendation pipeline
- Interactive Streamlit interface
- Containerized deployment using Docker
- Kubernetes deployment support
- Application monitoring with Prometheus and Grafana

## How It Works

1. The user describes the type of anime they want.
2. The embedding model converts the request into a vector.
3. ChromaDB searches for semantically similar anime.
4. The retrieved results are provided to the LLM.
5. The application generates personalized recommendations.

## Technologies Used

- Python
- Streamlit
- Sentence Transformers
- MiniLM/BGE Embeddings
- ChromaDB
- RAG
- Groq LLM
- Docker
- Kubernetes
- Prometheus
- Grafana
- Google Cloud Platform

## Project Structure

```text
├── app/          # Streamlit application
├── chroma_db/    # Vector database
├── config/       # Project configuration
├── data/         # Anime dataset
├── pipeline/     # Recommendation pipeline
├── src/          # Core source code
├── utils/        # Utility functions
├── Dockerfile
├── llmops-k8s.yaml
└── requirements.txt
```

## Installation

```bash
git clone https://github.com/Grishmakhatra932/ANIME-RECOMMENDER-SYSTEM-LLMOPS.git
cd ANIME-RECOMMENDER-SYSTEM-LLMOPS
pip install -r requirements.txt
```

Add your Groq API key to the environment:

```env
GROQ_API_KEY=your_api_key
```

Run the application:

```bash
streamlit run app/app.py
```

## Author

**Grishma Khatra**

Master of Computer Science graduate interested in AI/ML, data analytics, system integration, and production-oriented application development.

[GitHub](https://github.com/Grishmakhatra932) | [LinkedIn](https://www.linkedin.com/in/grishma-khatra)

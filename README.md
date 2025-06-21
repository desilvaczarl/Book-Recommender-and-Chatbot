## Book Recommender and Chatbot

### What This App Does
- Helps users **discover new books** based on a book title, topic, or theme
- Displays **visually appealing book results** with cover, genre, year, and description
- Includes a **smart chatbot assistant** to answer general questions about books, genres, authors, or literary concepts

### How It Works
- Uses **Sentence Transformers (`all-MiniLM-L6-v2`)** to convert book descriptions and user queries into embeddings
- Leverages **FAISS** for fast similarity search across all book embeddings
- Embeds book metadata like title, author, genre, year, thumbnail, and description
- Uses **Flan-T5** from Google to power a conversational Q&A chatbot about books

### Functionalities
- **Semantic search:** Find books using natural language descriptions with sentence-transformers and FAISS.
- **Category and year filtering:** Narrow recommendations by category or publication year.
- **Chatbot integration:** Uses transformers (Flan-T5) for book-related conversations.
- **Interactive UI:** Powered by Gradio for easy-to-use web interface.

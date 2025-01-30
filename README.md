# Qdrant Notebook Examples

This repository contains a collection of Jupyter notebooks demonstrating various features and use cases of Qdrant, a vector similarity search engine. Each notebook showcases different aspects of vector search and embedding techniques.

## 📚 Notebooks Overview

1. **Quick Start** (`01-quick-start.ipynb`)
   - Basic setup and connection to Qdrant
   - Fundamental operations with Qdrant client

2. **FastEmbed Examples** (`02-fastembed.ipynb`)
   - Implementation using FastEmbed for efficient embedding generation
   - Vector similarity search examples

3. **Sparse Vectors** (`03-sparse-vectors.ipynb`)
   - Working with sparse vector representations
   - Optimization techniques for sparse data

4. **ColBERT Multi-vectors** (`04-colbert-multivectors.ipynb`)
   - Implementation of ColBERT-style multi-vector representations
   - Advanced search techniques using multiple vectors

5. **Semantic Search** (`05-semantic-search.ipynb`)
   - Implementation of semantic search capabilities
   - Real-world examples of text similarity search

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- A Qdrant instance (cloud or local)

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/qdrant-notebook-examples.git
cd qdrant-notebook-examples
```

2. Install required packages:
```bash
pip install qdrant-client
pip install fastembed
pip install python-dotenv
```

3. Set up your environment variables in a `.env` file:
```
QDRANT_API_URL=your_qdrant_url
QDRANT_KEY=your_api_key
```

## 🔧 Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Navigate to the desired notebook and run the cells sequentially.

## 📖 Documentation

Each notebook is self-contained with detailed explanations and comments. The notebooks are designed to be run sequentially from 01 to 05, as they progress from basic to more advanced concepts.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open source and available under the MIT License.

## 🔗 Links

- [Qdrant Documentation](https://qdrant.tech/documentation/)
- [FastEmbed Documentation](https://qdrant.github.io/fastembed/) 
# RAG Evaluation Framework

This project implements various RAG (Retrieval-Augmented Generation) evaluation frameworks to assess and compare different RAG implementations using the RAGAS methodology.

## 🚀 Features

- Multiple RAG implementation support:
  - ✅ LlamaIndex
  - 🔄 LangChain (in progress)
  - 🔄 Haystack (in progress)
- Standardized evaluation metrics
- Data indexing capabilities
- Comparative analysis tools

## 📋 Prerequisites

- Python 3.8+
- Required packages (see `requirements.txt`)
- Data files for indexing

## 🛠️ Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd rag-eval-react
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## 📖 Usage

1. Data Indexing:
   - Place your data in the `data/` directory
   - Run the indexing script for your chosen implementation

2. Running Evaluations:
```bash
python -m llamaindex.llamaindex_ragas
```

## 📁 Project Structure

```
.
├── data/                  # Data directory for storing documents
│   └── gold_data.json    # Gold standard evaluation data
├── llamaindex/           # LlamaIndex implementation
│   ├── __init__.py
│   └── llamaindex_ragas.py
├── requirements.txt      # Project dependencies
└── README.md            # Project documentation
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

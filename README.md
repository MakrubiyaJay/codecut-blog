# CodeCut Blog Articles

[![Visit CodeCut Blog](https://img.shields.io/badge/Visit-CodeCut%20Blog-E583B6?style=for-the-badge)](https://codecut.ai/blog?utm_source=github&utm_medium=codecut-blog&utm_campaign=readme)

## About CodeCut

These notebooks are from **[CodeCut](https://codecut.ai/?utm_source=github&utm_medium=notebook&utm_campaign=codecut-blog)**. CodeCut features open-source Python data science tools explained in clear, digestible tutorials. Subscribe to get:

- Weekly articles with step-by-step guides
- Newsletters 3x per week (2-minute digests)

## Repository Overview

This repository contains 45+ comprehensive technical articles covering data science, MLOps, and AI tools.

Here are some examples of what you'll find in this repository:

**Data Engineering**
- [PySpark SQL](pyspark_sql_complete_guide.ipynb) - DataFrames, window functions, aggregations
- [DuckDB](duckdb.ipynb) - Fast analytical queries for data scientists
- [DVC](dvc_data_version_control.ipynb) - Data versioning and experiment tracking
- [Delta Lake](from_pandas_to_production_delta_rs.ipynb) - Production lakehouses with delta-rs

**Machine Learning**
- [Bayesian Optimization](bayesian_optimization.ipynb) - Efficient hyperparameter tuning
- [MLflow](essential-rag-evaluation-mlflow.ipynb) - RAG evaluation and experiment tracking
- [pytest for Data Scientists](pytest_for_data_scientists.ipynb) - Testing ML pipelines

**LLM Applications**
- [LangChain + Ollama](langchain_ollama.ipynb) - Private AI workflows
- [Pydantic AI](pydantic_ai.ipynb) - Type-safe LLM applications
- [RAG Pipelines](open_source_rag_pipeline_intelligent_qa_system.ipynb) - Intelligent QA systems
- [pgvector](pgvector_rag.ipynb) - Vector search for embeddings

**Data Visualization**
- [Python Visualization Libraries](top_6_python_visualization_libraries.ipynb) - Matplotlib, Plotly, Seaborn comparison
- [Manim](manim_mathematical_animations.ipynb) - Mathematical animations like 3Blue1Brown

**Data Utilities**
- [Faker](faker_generate_fake_data.ipynb) - Generate realistic test data
- [PRegEx](pregex_readable_regex.ipynb) - Human-readable regex patterns
- [Loguru](loguru_python_logging.ipynb) - Simplified Python logging
- [Hydra](hydra_config.ipynb) - Configuration management


### Prerequisites

1. **Python 3.9+**
2. **UV package manager** (recommended) or pip

### Setup Instructions

#### Option 1: Using UV (Recommended)

```bash
# Install UV if you haven't already
curl -LsSf https://astral.sh/uv/install.sh | sh

# Clone the repository
git clone https://github.com/khuyentran1401/codecut-blog.git
cd codecut-blog

# Install dependencies for a specific article
uv pip install package1 package2 package3
```

#### Option 2: Using pip

```bash
# Clone the repository
git clone https://github.com/khuyentran1401/codecut-blog.git
cd codecut-blog

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies for a specific article
pip install package1 package2 package3
```

## Dependencies

Each article is self-contained and lists its required packages at the beginning. Install only what you need for the specific articles you want to run to keep your environment lean.

## Contributing

Found an issue or have a suggestion?
- Open an issue at [codecut_articles repository](https://github.com/khuyentran1401/codecut_articles/issues)
- All articles are also published on [CodeCut.ai](https://codecut.ai/blog?utm_source=github&utm_medium=codecut-blog&utm_campaign=readme)

## License

All articles are copyright � Khuyen Tran. Code examples within articles are MIT licensed for reuse.
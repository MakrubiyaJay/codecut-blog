# CodeCut Blog Articles

[![Visit CodeCut Blog](https://img.shields.io/badge/Visit-CodeCut%20Blog-E583B6?style=for-the-badge)](https://codecut.ai/blog?utm_source=github&utm_medium=codecut-blog&utm_campaign=readme)

## About CodeCut

[CodeCut](https://codecut.ai/blog?utm_source=github&utm_medium=codecut-blog&utm_campaign=readme) is a platform dedicated to helping data scientists and ML engineers bridge the gap between prototyping and production. Founded by **Khuyen Tran**, a top writer on Towards Data Science with 110,000+ LinkedIn followers, CodeCut delivers daily Python tips and in-depth technical articles.

### What We Offer

- **Newsletter**: Bite-sized Python tips curated for data professionals - delivered 3 times per week, each skimmable in under 2 minutes
- **Technical Blog**: Comprehensive tutorials on data science, MLOps, and AI tools
- **Production-Ready Examples**: Code you can execute and adapt for real projects

## Repository Overview

This repository contains 45+ comprehensive technical articles covering data science, MLOps, and AI tools.

Here are some examples of what you'll find in this repository:

**Data Engineering**
- [PySpark SQL](pyspark_sql_complete_guide.qmd) - DataFrames, window functions, aggregations
- [DuckDB](duckdb.qmd) - Fast analytical queries for data scientists
- [DVC](dvc_data_version_control.qmd) - Data versioning and experiment tracking
- [Delta Lake](from_pandas_to_production_delta_rs.qmd) - Production lakehouses with delta-rs

**Machine Learning**
- [Bayesian Optimization](bayesian_optimization.qmd) - Efficient hyperparameter tuning
- [MLflow](essential-rag-evaluation-mlflow.qmd) - RAG evaluation and experiment tracking
- [pytest for Data Scientists](pytest_for_data_scientists.qmd) - Testing ML pipelines

**LLM Applications**
- [LangChain + Ollama](langchain_ollama.qmd) - Private AI workflows
- [Pydantic AI](pydantic_ai.qmd) - Type-safe LLM applications
- [RAG Pipelines](open_source_rag_pipeline_intelligent_qa_system.qmd) - Intelligent QA systems
- [pgvector](pgvector_rag.qmd) - Vector search for embeddings

**Data Visualization**
- [Python Visualization Libraries](top_6_python_visualization_libraries.qmd) - Matplotlib, Plotly, Seaborn comparison
- [Manim](manim_mathematical_animations.qmd) - Mathematical animations like 3Blue1Brown

**Data Utilities**
- [Faker](faker_generate_fake_data.qmd) - Generate realistic test data
- [PRegEx](pregex_readable_regex.qmd) - Human-readable regex patterns
- [Loguru](loguru_python_logging.qmd) - Simplified Python logging
- [Hydra](hydra_config.qmd) - Configuration management

## Article Format

All articles are written in **[Quarto Markdown (`.qmd`)](https://quarto.org/)** format, an open-source publishing system that:
- Lets you write narrative explanations alongside working code
- Automatically runs code and displays output as you render
- Produces polished documents in multiple formats
- Ensures every example is executable and reproducible

## Running Articles Locally

### Prerequisites

1. **Python 3.9+**
2. **UV package manager** (recommended) or pip
3. **Quarto** (for rendering)

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

### Running an Article

**Option 1: VS Code with Quarto Extension**

Open the `.qmd` file in **VS Code** with the [Quarto extension](https://marketplace.visualstudio.com/items?itemName=quarto.quarto) installed. Click "Run Cell" above each code block to execute individual chunks, or use "Run All" to execute the entire article.

**Option 2: Jupyter Notebook**

Convert the `.qmd` file to a Jupyter notebook and run it:

```bash
quarto convert article_name.qmd
jupyter notebook article_name.ipynb
```

## Dependencies

Each article is self-contained and lists its required packages at the beginning. Install only what you need for the specific articles you want to run to keep your environment lean.

## Contributing

Found an issue or have a suggestion?
- Open an issue at [codecut_articles repository](https://github.com/khuyentran1401/codecut_articles/issues)
- All articles are also published on [CodeCut.ai](https://codecut.ai/blog?utm_source=github&utm_medium=codecut-blog&utm_campaign=readme)

## Stay Connected

- **Website**: [codecut.ai](https://codecut.ai?utm_source=github&utm_medium=codecut-blog&utm_campaign=readme)
- **LinkedIn**: [Khuyen Tran](https://www.linkedin.com/in/khuyen-tran-1401/)

## License

All articles are copyright � Khuyen Tran. Code examples within articles are MIT licensed for reuse.
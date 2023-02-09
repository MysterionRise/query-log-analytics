# Query Log Analytics

Series of simple reusable Jupyter notebooks that would give you ability to quickly analyse user queries, cluster them, assign topics and could be a great starting point for advanced use cases

### How to run

Install venv and dependencies
```
python3 -m venv /path/to/new/virtual/environment
pip install -r requirements.txt
```

Run Jupyterlab

```
jupyter-lab
```

### Available notebooks

`query_clustering.ipynb` - provides capability to group similar queries into one cluster based on their semantic meaning. Currently, using sentence-transformers and `distiluse-base-multilingual-cased-v1` model
## datasets-notebooks

> Visualize data from Pinax's datasets.

### Getting started

1. Install [Jupyter notebook](https://jupyter.org/install#jupyter-notebook)
```bash
python -m venv .venv  # Create virtual environment
source .venv/bin/activate  # Activate virtual environment
(.venv) pip install notebook  # Install Jupyter notebook in venv
```
2. Run Jupyter notebook server
```bash
jupyter notebook
```
3. Open [notebook](http://localhost:8888/) in browser

### Notebooks

> [!TIP]
>
> Run directly in [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pinax-network/datasets-notebooks/HEAD)

#### [`block_sizes_estimates`](./block_sizes_estimates.ipynb)

Using Ethereum's block header `size` field to divide block ranges into equal sizes. Useful for data sinks operations.

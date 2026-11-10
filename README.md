# Spatial Compressibility

Combines a spatially embedded RNN (seRNN, Achterberg et al., *Nat. Mach. Intell.* 2023) with a genomic bottleneck (g-network, Shuvaev et al., *PNAS* 2024) to answer one question:

> Does a spatially embedded RNN compress into a genomic bottleneck better than an L1-regularised RNN?

## Installation

Python 3.12.

With uv:

```bash
uv venv --python 3.12
source .venv/bin/activate
uv pip install -r requirements.txt
```

With pip:

```bash
python3.12 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then open `spatial_compressibility.ipynb` with the `.venv` kernel.

## Files

- `spatial_compressibility.ipynb`: the experiment, block by block.
- `seRNN_demo.ipynb`: original seRNN demo (source of the copied blocks).
- `outputs/`: results written by the notebook.

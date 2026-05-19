# Nanoform Biodistribution Analysis

Reproducible analysis workflow for the manuscript:  
**"Are similar nanoforms comparable in biodistribution? Data-driven approaches for optimizing nanomedicine design"**

## Requirements

- Python 3.13 or later
- See `requirements.txt` for package dependencies

## Installation

```bash
pip install -r requirements.txt
```

## Usage

1. Place `model-data.xlsx` in the repository root
2. Open `Source-code.ipynb` in Jupyter or VS Code
3. Run all cells sequentially

## Input data

`model-data.xlsx` must contain two sheets:
- **Sheet `X`**: Nanoform descriptors (numerical + categorical)
- **Sheet `Y`**: Biodistribution endpoints (%ID)

## Outputs

The notebook generates:
- `correlation_analysis_outputs/` — Correlation matrices and heatmaps
- `SI_screening_outputs/` — Univariate and multivariate screening results
- `HCA_outputs/` — Hierarchical cluster analysis heatmaps
- `PCA_outputs/` — Principal component analysis plots

## Citation

If you use this workflow, please cite our manuscript: Merugu S, Mi K, Chen Q, Monteiro-Riviere NA, Riviere JE, Lin Z. Are similar nanoforms comparable in biodistribution? Data-driven approaches for optimizing nanomedicine design. Under review.

## License

MIT License

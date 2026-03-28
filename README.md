# Codespaces Jupyter Workspace

This repository contains a lightweight Jupyter workspace for data exploration and image-classification experiments.

## Environment

- Python: 3.14.3
- Key libraries: ipywidgets, matplotlib, pandas, torch, torchvision, tqdm, pillow
- Dependency file: requirements.txt

## Project Structure

- notebooks/population.ipynb: population data analysis
- notebooks/matplotlib.ipynb: plotting and visualization examples
- notebooks/image-classifier.ipynb: image classification workflow using PyTorch
- data/atlantis.csv: sample dataset used by notebooks

## Quick Start (Codespaces)

1. Open this repository in GitHub Codespaces.
2. Rebuild the container after configuration changes:
	- Command Palette -> Dev Containers: Rebuild Container
3. Verify Python version:

```bash
python --version
```

4. Install dependencies (if not already installed by container hooks):

```bash
python -m pip install -r requirements.txt
```

5. Open any notebook in notebooks/ and run cells.

## Quick Start (Local)

1. Install Python 3.14.3.
2. Create and activate a virtual environment.
3. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

4. Launch Jupyter:

```bash
jupyter notebook
```

5. Open notebooks/ in the browser UI.

## Notes

- Package versions are pinned for reproducibility.
- torch and torchvision should be kept in compatible version pairs.
- If a notebook kernel does not appear, reopen the notebook and select the Python interpreter for this environment.

# Advanced RL Code (Neural Data Science)

Notebooks and code for contextual bandit simulation and RPE decoding with LaseNet.

## Run in the browser (no install)

Click the badge below to launch the repo on **MyBinder**. The environment will build once (may take a few minutes), then you can run any notebook in your browser.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Center-for-Computational-Psychiatry/advancedRL/HEAD?labpath=decoding-example.ipynb)

To open a different notebook from Binder, change the `labpath` in the URL, e.g.:
- `simulate-contextual-bandit.ipynb`
- `simulate-contextual-bandit-solutions.ipynb`

## Run locally

1. Clone the repo (without the large `.venv` if you added it to `.gitignore`).
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Start Jupyter and open the notebooks:
   ```bash
   jupyter notebook
   ```

## Contents

- **`decoding-example.ipynb`** – Decoding reward prediction errors with LaseNet.
- **`simulate-contextual-bandit.ipynb`** – Contextual bandit simulation and attention exercises.
- **`simulate-contextual-bandit-solutions.ipynb`** – Solutions for the bandit notebook.
- **`libraries/`** – `World`, `FeatureRL`, `Data`, `plotting` for simulations.
- **`lasenet/`** – LaseNet model and training utilities (included in this repo; no separate clone needed on Binder).

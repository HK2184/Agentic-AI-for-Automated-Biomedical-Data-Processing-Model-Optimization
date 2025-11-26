# Gemini CLI — Biomedical Pipeline Agent (Demo Repo)

This repo contains a working local demo of the **Biomedical Pipeline Agent** wired to simple CLI tool wrappers.
It includes:
- synthetic EMG generator
- planner, preprocessing, feature extraction, trainer stubs
- Gemini CLI agent config (agent.toml)
- a demo Jupyter notebook that runs the pipeline end-to-end locally
- a zipped package for easy download

Quick steps (local demo):
1. Create a Python virtualenv and activate it.
2. Install requirements: `pip install -r requirements.txt`
3. Generate synthetic EMG: `python src/synthetic/generate_synthetic_emg.py --duration 10 --fs 1000 --channels 1 --out data/synthetic/sample_emg.csv`
4. Run the demo notebook `notebooks/demo.ipynb` or run the CLI wrappers directly.

The repo is meant for local demo and Kaggle capstone preparation. The Gemini CLI tool integration uses simple tool wrappers that Gemini can call when configured.

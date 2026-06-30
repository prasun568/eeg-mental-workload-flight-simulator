# EEG Mental Workload Flight Simulator

This repository contains an EEG-based mental workload classification pipeline for flight-simulator data. The notebook covers dataset inspection, preprocessing, sliding-window segmentation, CNN and EEGNet baselines, SMOTE balancing, and a flight-based evaluation split.

## Contents

- `EEG_Mental_Workload_Flight_Simulator.ipynb` - end-to-end experiment notebook
- `requirements.txt` - Python dependencies for local or Colab use
- `.gitignore` - keeps generated artifacts and notebook cache files out of the repo

## Workflow

1. Mount Google Drive in Colab or point the notebook to your local dataset path.
2. Load the EEG parquet file from the flight-simulator dataset.
3. Run preprocessing, normalization, segmentation, and model training cells.
4. Review the saved confusion matrices, comparison plots, and summary tables.

## Notes

- The dataset itself is not included in this repository.
- The notebook is written for Google Colab, but the core logic can be adapted to a local Jupyter environment.
- Generated figures are saved by the notebook during execution and are intentionally ignored by git.

## Suggested citation

If you use this work in a report or presentation, mention the dataset source and the model variants evaluated in the notebook.

# Post-Training-an-LLM-for-Complex-Alignment
This repository contains the code, datasets, evaluation framework, and results
for the post-training experiment described in the accompanying report.

## Running the experiments

The notebooks are designed to run in Google Colab.

1. Open the required notebook from `notebooks/`.
2. Select a GPU runtime.
3. Run the cells sequentially.
4. The required Python packages are installed in the first cell.

## Experiments

- `run_baseline.ipynb` — evaluates the untuned models.
- `LLM_PostTraining.ipynb` — performs LoRA-based supervised fine-tuning.
- `Evaluator_python.ipynb` — evaluates the fine-tuned model.

## Dataset

The `data/` directory contains the training and held-out validation datasets.

## Evaluation

The `evaluator/` directory contains the rule-based protocol evaluator.

## Results

The `results/` directory contains the saved evaluation results.

## Hardware

Experiments were conducted using an NVIDIA Tesla T4 GPU in Google Colab.

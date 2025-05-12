# Dataset Conversion for Mimic Robot

This repository provides a Jupyter notebook to assist in converting datasets into a format compatible with the [LeRobot](https://github.com/huggingface/lerobot) codebase.

## Overview

The goal of this project is to facilitate the transformation of existing robot datasets for use with the LeRobot framework, a library by Hugging Face for robot learning tasks.

## Contents

- `save_data_clean.ipynb`: A notebook that walks you through the steps to convert your dataset into the required LeRobot format.

## Requirements

Before using the notebook, ensure that you have the [LeRobot](https://github.com/huggingface/lerobot) repository cloned and properly set up on your machine.

```bash
git clone https://github.com/huggingface/lerobot
cd lerobot
pip install -e .
```

## Example Output

A sample converted dataset is available on Hugging Face:

Dataset: `chengkunli/green_cup_pour`

## Visualization: 
You can preview and inspect the dataset using the LeRobot visualizer: [lerobot/visualize_dataset](https://huggingface.co/spaces/lerobot/visualize_dataset?path=%2Fchengkunli%2Fgreen_cup_pour%2Fepisode_1)

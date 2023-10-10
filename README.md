## Dataset
This repo has a paired chart image and table. The source of this dataset is [https://huggingface.co/datasets/chiragtubakad/chart-to-table-mix](https://huggingface.co/datasets/chiragtubakad/chart-to-table-mix).

---
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: test
    path: data/test-*
dataset_info:
  features:
  - name: image
    dtype: image
  - name: text
    dtype: string
  splits:
  - name: train
    num_bytes: 102169807.41570717
    num_examples: 2245
  - name: test
    num_bytes: 25042009.85429284
    num_examples: 562
  download_size: 108880031
  dataset_size: 127211817.27000001
---
# Dataset Card for "chart-to-table-mix"

[More Information needed](https://github.com/huggingface/datasets/blob/main/CONTRIBUTING.md#how-to-contribute-to-the-dataset-cards)# chiragtubakad-chart-to-table-mix

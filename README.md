# AE-NAS
The code for Neural Architecture Search Using Attention Enhanced Precise Path Evaluation and Efficient Forward Evolution.


## Dataset

NAS-Bench-101 and NAS-Bench-201 are benchmark datasets for evaluating NAS methods. These datasets provide a fixed set of neural architectures, along with performance metrics (e.g., accuracy, latency) for each architecture. This allows researchers to evaluate NAS algorithms without needing to train architectures from scratch.

NAS-Bench-101:
NAS-Bench-101 contains a collection of 423,624 neural network architectures. For each architecture, the dataset provides validation accuracy and training time for three different random seeds. It can be download from https://github.com/google-research/nasbench.

NAS-Bench-201:
NAS-Bench-201 contains 15,625 architectures sampled from the search space of NAS algorithms, with the evaluation metrics including validation accuracy and training time across five different datasets. It can be download from https://github.com/D-X-Y/NAS-Bench-201.

## Setup
Clone this repository:
```bash
git clone https://github.com/Zhangqian0616/AE-NAS.git
cd AE-NAS
```
Set up the required environment:
```bash
conda create -n nas-bench python=3.8
conda activate nas-bench
pip install -r requirements.txt
```


## quick start
```bash
sh run.sh
```

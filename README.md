# Rethinking Domain Generalization for Face Anti-spoofing: Separability and Alignment

This is the source code for CVPR 2023 paper [Rethinking Domain Generalization for Face Anti-spoofing:
Separability and Alignment](https://arxiv.org/abs/2303.13662)
by Yiyou Sun, Yaojie Liu, Xiaoming Liu, Yixuan Li and Wen-Sheng Chu.

## Preliminaries
It is tested under Ubuntu Linux 20.04 and Python 3.8 environment, and requries some packages to be installed with the following commands:

```bash
sudo apt install ffmpeg
pip install -r requirements.txt
```

## Usage

### 1. Dataset Preparation

Download the OULU-NPU, CASIA-FASD, Idiap Replay-Attack, and MSU-MFSD datasets.

### 2. Prepocessing

Run `./preprocess.py`. (You might need to change the rootpath to the datasets in the script.)

### 3. Demo

Run `./train.py --protocol [O_C_I_to_M/O_M_I_to_C/O_C_M_to_I/I_C_M_to_O]`.

## Citation

If you use our codebase, please cite our work:

```
@article{sun2023safas,
  title={Rethinking Domain Generalization for Face Anti-spoofing:
Separability and Alignment},
  author={Sun, Yiyou and Liu, Yaojie and Liu, Xiaoming and Li, Yixuan and Chu Wen-Sheng},
  journal={CVPR},
  year={2023}
}
```


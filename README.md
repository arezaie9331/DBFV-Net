# Two-Stage ID Document Forgery Detection (DBFV-Net)

  

This repository contains the implementation code for our paper on forged identity document detection.  

The project is provided as an executable **Jupyter Notebook** along with pretrained weights and dataset access information.

  

---

  

## Abstract

  

Forgery of identity documents has become increasingly accessible due to recent advances in image generation and editing tools. This creates significant risks for digital identity verification and Know Your Customer (KYC) applications, where robust automatic detection of manipulated ID documents is essential. In this work, we address the problem of forged identity document detection using a dual-branch deep learning framework trained in two stages. The proposed system is designed to analyze both portrait-related and document-level visual information and to support reliable discrimination between genuine and forged samples. Experiments are conducted on the FantasyIDiap dataset, which contains fantasy identity cards captured under realistic conditions and includes multiple types of tampering. The results demonstrate the effectiveness of the proposed approach, achieving a best reported F1-score of **93.4%**.

  

---

  

## Repository Contents

  

- Executable Jupyter Notebook

- Pretrained model weights

- Dataset access information
  

---

  

## Project Structure

```bash

.

├── README.md

├── requirements.txt

├── notebook/

│   └── project.ipynb

├── weights/

│   └── weights.pth

└── data/

```

  
  

---

  

## Installation

  

It is recommended to use Python **3.10+** and a clean virtual environment.

  

### Clone the repository

  
```bash
git clone https://github.com/arezaie9331/DBFV-Net.git
cd DBFV-Net
```
  

### Create and activate a virtual environment

  

#### Linux / macOS

  

```bash
python -m venv .venv
source .venv/bin/activate
```
  

#### Windows

  
```bash
python -m venv .venv 
.venv\Scripts\activate
```
  

### Install dependencies

  
```bash
pip install -r requirements.txt
```
  

---

  

## Dataset

  

This project uses the **FantasyID / FantasyIDiap** dataset.

  

Official dataset page:

  

[Official Dataset Page](https://www.idiap.ch/paper/fantasyid/)

  

Please follow the instructions on the official page to access or download the dataset.

  

After downloading, place the dataset in the appropriate directory, for example:

  

`data/`

  

If needed, preprocess or reorganize the data according to the notebook requirements.

  

---

  

## Pretrained Weights

  

Pretrained weights are available at:

  

[Google Drive Weights](https://drive.google.com/file/d/11plm3PBzaekYPNmE54RN6YcmQbbR9KqO/view?usp=sharing)

  

After downloading, place the weights file inside:

  

`weights/`

  

Example:

  

`weights/ └── model.pth`

  

If necessary, update the checkpoint path inside the notebook before execution.

  

---

  

## Running the Notebook

  

Launch Jupyter Notebook:

  

`jupyter notebook`

  

Then open:

  

`notebook/project.ipynb`

  

Before running all cells, make sure that:

  

- all dependencies are installed

- the dataset is downloaded and placed correctly

- the pretrained weights are available locally

- dataset paths and checkpoint paths are updated inside the notebook

  

---
  
## Paper

  

**Two-Stage Training of a Dual-Branch FaceNet–ViT Network for ID Document Forgery Detection**

  

If you use this repository, please cite the corresponding paper.

  
## Contact

For questions, suggestions, or issues, please open an issue on GitHub.

## Citation

If you use this repository, please cite the corresponding paper.

## License

This repository is provided for research purposes only.


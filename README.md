(WIP)
This repository contains the lab exercises for the **Information Retrieval** lecture at the Dresden University of Technology (TUD) for the Winter term 25/26.

## Table of Contents
- [Setup](#setup)
  - [Installing/Updating uv](#installing/updatinguv)
- [Installation](#installation)
- [Usage](#usage)

## Setup
We recommend using [uv](https://docs.astral.sh/uv/) for this project, nonetheless, we also provide a `requirements.txt` file.

### Installing/Updating uv
```bash
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh

# Update uv
uv self update
```

However, pip can also be used (we will not provide further setup details, though if you installed `uv` via pip, you can simply type e.g. python3 -m uv sync and achieve similar results):
```bash
pip install uv
```

## Installation
1. First, clone the repository
```bash
git clone git@github.com:jembie/ir-exercises.git
cd ir-exercises/
```

2. Then install the required dependencies
```bash
# Recommended through uv
uv sync

# Alternatively via pip
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Usage
Within the **`exercises/`** directories are all the relevant Jupyter Notebooks stored. Once the required dependencies are installed, each notebook should be ready to use.

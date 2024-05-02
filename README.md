# Source Code for TPPJ Paper
This repository contains all the code used for model training/tuning/testing and visualizations. All code is written with Jupyter Notebooks. 

## Directory Structure
This section highlights the directory structure of this project and how to navigate through it. Below is an overiew of the directory structure:

<pre>
├── Hypothesis_1\
│   │
│   ├── Datasets\
│   │   │
│   │   ├── 2021\
│   │   │   └── Dataset_2021.csv
│   │   │
│   │   └── 2022\
│   │       └── Dataset_2022.csv
│   │
│   │
│   ├── LORO\
│   │   │
│   │   ├── 2021\
│   │   │   │
│   │   │   ├── Baseline_Model\
│   │   │   │   │
│   │   │   │   ├── Baseline_LASSO.ipynb
│   │   │   │   └── Baseline_XGBoost.ipynb
│   │   │   │
│   │   │   ├── Outputs\
│   │   │   │   └── predictions.csv
│   │   │   │
│   │   │   ├── Proposed_Models\
│   │   │   │   │
│   │   │   │   ├── Proposed_Modeling_Approach_1\
│   │   │   │   │   │
│   │   │   │   │   ├── H1A1M1.ipynb
│   │   │   │   │   └── H1A1M2.ipynb
│   │   │   │   │
│   │   │   │   └── Proposed_Modeling_Approach_2\
│   │   │   │       │
│   │   │   │       ├── H1A2M1.ipynb
│   │   │   │       └── H1A2M2.ipynb
│   │   │   │
│   │   │   │
│   │   │   └── Testing\
│   │   │       └── LORO.ipynb
│   │   │
│   │   │
│   │   └── 2022\
│   │       │
│   │       ├── Baseline_Model\
│   │       │   │
│   │       │   ├── Baseline_LASSO.ipynb
│   │       │   └── Baseline_XGBoost.ipynb
│   │       │
│   │       ├── Outputs\
│   │       │   └── predictions.csv
│   │       │
│   │       ├── Proposed_Models\
│   │       │   │
│   │       │   ├── Proposed_Modeling_Approach_1\
│   │       │   │   │
│   │       │   │   ├── H1A1M1.ipynb
│   │       │   │   └── H1A1M2.ipynb
│   │       │   │
│   │       │   └── Proposed_Modeling_Approach_2\
│   │       │       │
│   │       │       ├── H1A2M1.ipynb
│   │       │       └── H1A2M2.ipynb
│   │       │
│   │       │
│   │       └── Testing\
│   │           └── LORO.ipynb
│   │
│   │
│   │
│   └── LOYO\
│       │
│       ├── Baseline_Model\
│       │   │
│       │   ├── Saved_Models\
│       │   │
│       │   ├── Baseline_XGBoost.ipynb
│       │   └── Basline_LASSO.ipynb
│       │
│       ├── Outputs\
│       │
│       ├── Proposed_Models\
│       │   │
│       │   ├── Proposed_Modeling_Approach_1\
│       │   │   │
│       │   │   ├── Saved_Models\
│       │   │   │
│       │   │   ├── H1A1M1.ipynb
│       │   │   └── H1A1M2.ipynb
│       │   │
│       │   └── Proposed_Modeling_Approach_2\
│       │       │
│       │       ├── Saved_Models\
│       │       │
│       │       ├── H1A2M1.ipynb
│       │       └── H1A2M2.ipynb
│       │
│       │
│       └── Testing\
│           └── LOYO.ipynb
│
│
│
├── Hypothesis_2\
│   │
│   ├── Datasets\
│   │   │
│   │   ├── Agronomic\
│   │   │   │
│   │   │   ├── 2021\
│   │   │   │   └── Dataset_2021.csv
│   │   │   │
│   │   │   └── 2022\
│   │   │       └── Dataset_2022.csv
│   │   │
│   │   │
│   │   └── Images\
│   │
│   │
│   ├── LORO\
│   │   │
│   │   ├── 2021\
│   │   │   │
│   │   │   ├── Outputs\
│   │   │   │   ├── predictions.csv
│   │   │   │   ├── pumap_embedding_test.csv
│   │   │   │   └── pumap_embedding_train.csv
│   │   │   │
│   │   │   ├── Proposed_Models\
│   │   │   │   │
│   │   │   │   ├── Proposed_Modeling_Approach_3\
│   │   │   │   │   │
│   │   │   │   │   ├── Saved_Models\
│   │   │   │   │   │
│   │   │   │   │   ├── H2A3M1.ipynb
│   │   │   │   │   └── H2A3M2.ipynb
│   │   │   │   │
│   │   │   │   └── Proposed_Modeling_Approach_4\
│   │   │   │       │
│   │   │   │       ├── Saved_Models\
│   │   │   │       │   └── H2A4M1.keras
│   │   │   │       │
│   │   │   │       └── H2A4M1.ipynb
│   │   │   │
│   │   │   │
│   │   │   └── Testing\
│   │   │       └── LORO.ipynb
│   │   │
│   │   │
│   │   └── 2022\
│   │       │
│   │       ├── Outputs\
│   │       │   ├── predictions.csv
│   │       │   ├── pumap_embedding_test.csv
│   │       │   └── pumap_embedding_train.csv
│   │       │
│   │       ├── Proposed_Models\
│   │       │   │
│   │       │   ├── Proposed_Modeling_Approach_3\
│   │       │   │   │
│   │       │   │   ├── H2A3M1.ipynb
│   │       │   │   └── H2A3M2.ipynb
│   │       │   │
│   │       │   └── Proposed_Modeling_Approach_4\
│   │       │       │
│   │       │       ├── Saved_Models\
│   │       │       │
│   │       │       └── H2A4M1.ipynb
│   │       │
│   │       │
│   │       └── Testing\
│   │           └── LORO.ipynb
│   │
│   │
│   │
│   └── LOYO\
│       │
│       ├── Outputs\
│       │
│       ├── Proposed_Models\
│       │   │
│       │   ├── Proposed_Modeling_Approach_3\
│       │   │   │
│       │   │   ├── Saved_Models\
│       │   │   │
│       │   │   ├── H2A3M1.ipynb
│       │   │   └── H2A3M2.ipynb
│       │   │
│       │   └── Proposed_Modeling_Approach_4\
│       │       │
│       │       ├── Saved_Models\
│       │       │
│       │       └── H2A4M1.ipynb
│       │
│       │
│       └── Testing\
│           └── LOYO.ipynb
│
│
│
├── poetry.lock
└── pyproject.toml
</pre>

There are four proposed modeling approaches:
- PCA-based dimension reduction (proposed modeling approach 1, addressed by Hypothesis 1)
- UMAP-based dimension reduction (proposed modeling approach 2, addressed by Hypothesis 1)
- PUMAP-based spatially-aware dimension reduction (proposed modeling approach 3, addressed by Hypothesis 2)
- Spatiotemporal learning with 3D-CNN (proposed modeling approach 4, addressed by Hypothesis 2)

The root directory specifies the hypothesis. Under each hypothesis, there are two types of model evaluation:
- Withing-season (LORO)
- Cross-season (LOYO)

Under each evaluation type, you will find a directory for the proposed models that address their respective hypothesis. The notebook file's name is formatted as follows: `H[1-2]A[1-4]M[1-2]` \
The numbers and letters represents:
- H[1-2] -> **H**ypothesis 1/2
- A[1-4] -> **A**pproach 1/2/3/4
- M[1-2] -> Underlying **M**odel 1/2

There are two underlying models for almost all approaches: LASSO (M1) and XGBoost (M2). This doesn't apply for modeling approach 4, where M1 represents the 3D-CNN model.

Under each modeling approach, the serialized models can be found under `Saved_Models\` that can easily be loaded via `joblib`. An example of how to load the models can be found in <a href="Hypothesis_1\LOYO\Testing\LOYO.ipynb">LOYO.ipynb</a>

The baseline models can be found under `Baseline_Model\`. We used the same baseline models for both hypotheses (they can be found under `Hypothesis_1\`).

For example, if you're interested in viewing the code for training the spatiotemporal 3D-CNN model (modeling approach 4) for cross-season evaluation, you can find it under Hypothesis_2\LOYO\Proposed_Models\Proposed_Modeling_Approach_4\H2A4M1.ipynb.

## Dataset
There are two types of data used in this project, depending on which hypothesis:
- Hypothesis 1 models used a tabular dataset that contains the UAV-derived features. Those can be found under `Hypothesis_1\Datasets\`
- Hypothesis 2 models uses raw UAV images which needs to be seperately downloaded (hosting link and download instructions are coming soon). Agronomic information about the images can be found under `Hypothesis_2\Datasets\Agronomic`

## Installation
This project uses Python 3.10.11 and `poetry` as the virtual environment manager. The env files are included in the root directory. To create an environment using our `pypoetry.toml` env file, execute the following commands. Note: this assumes you have poetry installed. If not, download it from [here](https://python-poetry.org/docs/). 
Also, it assumes that you have Python 3.10.11. If not, download it from [here](https://www.python.org/downloads/release/python-31011/).

Clone the github repo to your local machine
```
git clone https://github.com/FareedFarag/TPPJ-Modeling-Code
```

Navigate to the directory
```
cd TPPJ-Modeling-Code
```

Install the environment
```
poetry install
```




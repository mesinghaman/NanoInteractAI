# Drug Modification Prediction via Micro-Nanoparticle Interactions

**In collaboration with the Department of Nanotechnology, VIT Vellore**

This project aims to analyze and predict drug modifications caused by micro- and nano-particle interactions using advanced machine learning techniques. We leverage few-shot learning with LLMs, XGBoost, and GraphSAGE to understand and model complex nanoparticle-induced alterations in drug behavior.

## Project Overview

Micro-nanoparticles can significantly influence drug stability, release, and bioavailability. This project presents predictive models to:

*Detect potential drug modifications
*Understand nanoparticle-drug interaction patterns
*Support nanoformulation design using data-driven insights

## Models Implemented
###1. LLM (Few-Shot Learning)
Used for prompt-based prediction and understanding patterns in low-resource settings.

###2. XGBoost
*Gradient boosting technique for structured tabular data
*Used for classification and regression of drug modification effects
*See XGBoost.ipynb for implementation

###3. GraphSAGE
*Applied to model nanoparticle-drug relationships as graphs
*Captures structural dependencies in data

##Repository Structure

.
├── XGboost.ipynb           # XGBoost model notebook
├── GraphSAGE/              # Directory for GraphSAGE implementation
├── LLM_Prompts/            # Few-shot learning examples and results
├── data/                   # Input data files (preprocessed/cleaned)
├── utils/                  # Helper functions
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
## Results
*XGBoost achieved high accuracy in classifying modification likelihood.
*Few-shot learning showed potential in generalizing from limited examples.
*GraphSAGE captured complex relational structures with nanoparticle interaction data.



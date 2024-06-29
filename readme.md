# Hands-on MLOps

![alt text](assets/image.png)

Welcome to the Hands-on MLOps Curriculum repository! This repository contains practical exercises and examples to help you learn MLOps concepts using various toolkits including Ray, MLflow, Optuna, DVC, and LIME for model interpretability.

## Table of Contents

1. [Introduction](#introduction)
2. [Structure](#structure)
3. [Setup Instructions](#setup-instructions)
5. [Resources](#resources)
6. [License](#license)

## Introduction

This curriculum is designed to provide hands-on experience in implementing MLOps practices using state-of-the-art toolkits. Whether you're new to MLOps or looking to deepen your knowledge, these exercises will guide you through practical examples that demonstrate the integration of machine learning models with deployment pipelines, experiment tracking, hyperparameter tuning, version control, and model interpretability.

## Structure 

This repository has broken down the MLOps on the basis of categories: 

1. Classical Machine Learning
2. Natural Language Processing 
3. Computer Vision
4. Large Language Model 


## Setup Instructions

To get started with the Hands-on MLOps Curriculum, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AdityaKulshrestha/MLOps.git
   
   cd MLOps
   ```

2. **Install dependencies:**
    We recommend creating a virtual environment (e.g., using virtualenv or conda) and installing the required dependencies:

    ```bash
    python -m venv practical_mlops
    source practical_mlops/bin/activate # for linux
    pip install -r requirements.txt
    ```

3. **Start Jupyter Notebook:**
    Launch Jupyter Notebook to access the exercises and examples:

    ```bash
    jupyter-notebook
    ```

4. **Run the mlflow server**
    Launch the mlflow ui server:

    ```bash
    mlflow server --host 0.0.0.0 --port 8000
    ```

## Resources 

### Machine Learning & NLP
    - [Distributed computing with Ray](https://docs.ray.io/): Ray is a framework for building and running distributed applications at scale. It provides simple APIs for parallel and distributed computing, making it easy to scale and manage machine learning workflows efficiently.

    - [Experiment tracking and model packaging with MLflow](https://mlflow.org/): MLflow is an open-source platform for managing the end-to-end machine learning lifecycle. It provides tools for tracking experiments, packaging code into reproducible runs, and managing models' lifecycle, enabling collaboration and reproducibility in machine learning projects.

    - [Hyperparameter optimization with Optuna](https://optuna.org/): Optuna is an automatic hyperparameter optimization framework. It streamlines the process of tuning machine learning model parameters to achieve optimal performance, using techniques such as Bayesian optimization and pruning algorithms.

    - [Versioning datasets and models with DVC](https://dvc.org/): Data Version Control (DVC) is an open-source tool for managing datasets and machine learning models. It provides version control, data provenance tracking, and experiment reproducibility, enhancing collaboration and maintaining consistency across machine learning projects.

    - [Model interpretability using LIME](https://github.com/marcotcr/lime): LIME (Local Interpretable Model-agnostic Explanations) is a library for explaining the predictions of machine learning models. It helps understand how models make decisions by generating locally faithful explanations, aiding model interpretability and trust.


    - [AutoML](https://en.wikipedia.org/wiki/Automated_machine_learning): Automated Machine Learning (AutoML) refers to the process of automating the end-to-end process of applying machine learning to real-world problems. Various tools and libraries exist for AutoML, such as [Auto-sklearn](https://automl.github.io/auto-sklearn/) and [TPOT](http://epistasislab.github.io/tpot/).

    - [Transformers Interpretable](https://github.com/cdpierse/transformers_interpretable): This library focuses on providing interpretability tools for transformer-based models, allowing for better understanding of model predictions and behavior.

    - [Feast (Feature Selection)](https://docs.feast.dev/): Feast is an open-source feature store for machine learning. While it primarily serves as a feature store, it also provides utilities for feature selection and management.

    - [Evidently](https://github.com/evidentlyai/evidently): Evidently is a library for explaining machine learning models and monitoring model performance over time. It provides tools for model interpretation, fairness assessment, and drift detection.

### Computer Vision
- [Intel OpenVINO Toolkit](https://www.intel.com/content/www/us/en/developer/tools/openvino-toolkit/overview.html): The Intel OpenVINO Toolkit (Open Visual Inference and Neural Network Optimization) is a comprehensive toolkit for deploying AI and computer vision applications at the edge. It optimizes models trained in popular frameworks like TensorFlow, PyTorch, and ONNX for efficient execution on Intel hardware, including CPUs, GPUs, and VPUs (Vision Processing Units).

- [Geti](https://geti.intel.com/): Intel’s new software for building computer vision models in a fraction of the time and with less data. This software eases laborious data labeling, model training and optimization tasks across the AI model development process, empowering teams to produce custom AI models at scale. 

- [OpenVINO Training Extensions](https://docs.openvino.ai/2022.3/ote_documentation.html): OpenVINO™ Training Extensions provide a suite of advanced algorithms to train Deep Learning models and convert them using the OpenVINO™ toolkit for optimized inference. It allows you to export and convert the models to the needed format. OpenVINO Training Extensions independently create and train the model. It is open-sourced and available on GitHub. Read the OpenVINO Training Extensions documentation to learn more.







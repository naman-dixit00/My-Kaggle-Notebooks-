# My Kaggle Notebooks - Datasets

Welcome to the central repository for the datasets used across my Kaggle notebooks, pipelines, and machine learning scripts. This repository acts as the data backbone for various projects spanning computational mathematics, neuroscience, quantum computing, photonics, and advanced physics.

## 📌 Overview
This collection contains specialized, high-dimensional, and benchmark datasets designed for training complex machine learning models, running simulations, and processing neural or physical signals.

---

## 📂 Dataset Catalog & Descriptions

Below is a detailed breakdown of each dataset available in this repository:

### 🧠 Neuroscience & Cortical Data
* **Cortical Multi-Region Connectivity Dataset (`Cortical Multi-Region Connectivity Dataset.zip`)**
    * *Description:* Contains structural or functional connectivity matrices mapping interactions across multiple regions of the cerebral cortex. Ideal for graph neural networks (GNNs) and brain network analysis.
* **CorticalState-Prob Probabilistic Latent Dynamics (`CorticalState-Prob Probabilistic Latent Dynamics.zip`)**
    * *Description:* Features probabilistic states and latent dynamics extracted from cortical time-series data. Used for modeling state transitions in neural populations.
* **Liquid Units for Cortical Interface Decoding (`Liquid Units for Cortical Interface Decoding.zip`)**
    * *Description:* Designed for brain-computer interface (BCI) applications. It leverages Liquid State Machine (LSM) architectures or liquid computing concepts to decode neural signals from cortical interfaces.
* **Synthetic Human Connectome (`Synthetic Human Connectome.zip`)**
    * *Description:* A mathematically generated or simulated dataset mimicking the structural pathways (connectome) of the human brain, used for benchmarking network neuroscience algorithms.
* **Spikes Morphological Decision Dataset (`Spikes Morphological Decision Dataset.zip`)**
    * *Description:* Focuses on neural spike trains and morphological properties of neurons, helping models make analytical decisions based on neural firing patterns and shapes.

### 🔬 Advanced Physics, Optics, & Photonics
* **High-Speed Diffraction-Encoded Optical Matrix Data (`High-Speed Diffraction-Encoded Optical Matrix Data (2).zip`)**
    * *Description:* Features complex optical matrices generated from high-speed, diffraction-encoded optical computing setups. Perfect for optical neural network (ONN) simulations.
* **Interference Photonics Dataset (`Interference Photonics Dataset.zip`)**
    * *Description:* A dataset capturing wave interference patterns in photonics systems, crucial for training models to predict phase shifts, signal integrity, or holographic reconstructions.
* **RNA Geometrical Physics Dataset (`RNA Geometrical Physics Dataset.zip`)**
    * *Description:* Combines molecular biology with structural physics, mapping the spatial geometries, folding thermodynamics, and physical constraints of RNA molecules.
* **Ising Criticality Dynamics Transformers Datasets (`Ising Criticality Dynamics Transformers Datasets.zip`)**
    * *Description:* Features state transitions and critical dynamics of the thermodynamic Ising Model, structured specifically for training Transformer architectures to predict phase transitions.

### 💻 Computational Mathematics & Quantum ML
* **Computational Mathematics Dataset (`Computational Mathematics Dataset.zip`)**
    * *Description:* A foundational dataset consisting of numerical matrices, algebraic equations, or differential system outputs designed for optimizing numerical solvers and mathematical ML pipelines.
* **Quantum Machine Learning Benchmark (`Quantum Machine Learning Benchmark.zip`)**
    * *Description:* A highly specialized benchmark dataset for validating Quantum Machine Learning (QML) algorithms, featuring quantum state classifications and quantum circuit performance data.

### 🏭 Industrial & Engineering Variation
* **Energy-Landscape Wafer Variation Benchmark (ELWVB) (`Energy-Landscape Wafer Variation Benchmark (ELWVB) (2).zip`)**
    * *Description:* An engineering dataset tracking micro-manufacturing variations across semiconductor wafers using energy-landscape modeling for quality control and predictive maintenance.
* **Molecular Interaction Manifold Dataset (`Molecular Interaction Manifold Dataset.zip`)**
    * *Description:* Maps high-dimensional topological manifolds of molecular interactions, used in drug discovery pipelines to understand how molecules bind and interact.

---

## 🛠️ How to Use These Datasets

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/naman-dixit00/My-Kaggle-Notebooks.git](https://github.com/naman-dixit00/My-Kaggle-Notebooks.git)
    cd My-Kaggle-Notebooks/Datasets
    ```
2.  **Unzip the Required Dataset:**
    Choose the dataset you need for your script or notebook and extract it:
    ```bash
    unzip "Dataset_Name.zip" -d ./data/
    ```
3.  **Load in Python:**
    ```python
    import pandas as pd
    # Example for loading unzipped CSV or structural data
    # data = pd.read_csv('./data/your_dataset_file.csv')
    ```

## 📜 License
This project is licensed under the terms specified in the main repository's [LICENSE](../LICENSE) file.

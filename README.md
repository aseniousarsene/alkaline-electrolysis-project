
# README: Research Code for Evaluation of Alkaline Water Electrolysis for Green Hydrogen: A Numerical Optimization and Machine Learning Approach

## 1. Overview 

This repository contains the research code patterning to the paper:
**"Evaluation of Alkaline Water Electrolysis for Green Hydrogen: A Numerical Optimization and Machine Learning Approach"**
Authors: Mahiya Arsene ka, Tumisang Seodigeng ,John Kabuba 
Published in: [Results in Engineering]
DOI:[]
This code implements the modelling, evaluation and optimization of an alkaline electrolysis system for green hydrogen production. It includes Python Jupiter notebook scripts for the system simulation and ANN modelling with result visualization.

## 2. Repository Structure

📂 Alkaline-electrolysis-project  
 ┣ 📂 data                                # Sakas Excel file for validation
 ┣ 📂 images                              # For plot result output
 ┣ 📂 logs                                # ANN tensorboard log  
 ┃ 📜 Cell-Optimum-efficiency.ipynb       # Efficiency optimization model 
 ┃ 📜 Model-AWE-ANN.ipynb                 # Electrolyser and Artificial neural network modelling  
 ┃ 📜 Model-AWE-Evaluation.ipynb          # Electrolyser modelling and evaluation  
 ┣ 📜 README.md                           # Documentation 
 ┣ 📜 requirements.txt                    # Dependencies list
 ┣ 📜 LICENSE                             # License information  


## 3. Requirements & Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation

Install dependencies using:
```python
pip install -r requirements.txt
```
Set Up a Virtual Environment (optional but recommended) using:
```python
python -m venv venv
```
Activate the environment:
On Windows with: 
```python 
venv\Scripts\activate
```
Then install dependencies in the venv: pip install -r requirements.txt

## 3. Usage

**Run the Jupyter Notebooks**:
   - Open each Jupyter notebook in Jupyter Notebook or JupyterLab.
   - Execute all cells simultaneously or run them in sections to simulate the electrolyser models and generate results.

**Save Figures**:
   - Uncomment the figure-saving functions (`plt.savefig()`) in the notebooks to export plots to the `images` folder.

**Train the ANN Model**:
   - The Artificial Neural Network (ANN) may require multiple training runs to achieve optimal results.

**Visualize Network Results**:
   - Detailed ANN training logs are saved in the `logs/fit` folder.
   - Use TensorBoard to visualize these results by running:
     ```bash
     tensorboard --logdir logs/fit
     ```

## 4. Data Availability

The dataset used in this research is available at 
[ DOI link].

## 5. License & Citation

This project is licensed under the MIT License - see the LICENSE file for details.

Please cite this work using the DOI from Zenodo:

 ```bibtex
@misc{Mahiya_2025,
  author       = {Arsene, Mahiya},
  title        = {Electrolyser Performance Modeling and AI Prediction: Version 1.0},
  year         = 2025,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.14954755},
  url          = {https://doi.org/10.5281/zenodo.14954754}
}
 ```

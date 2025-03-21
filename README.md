- This manuscript is currently under revision at *Earth and Planetary Science Letters*

## ***Jupyter Notebooks to accompany the paper:***
    
# **Unraveling Remagnetization Sources using Statistical Learning**

### *by L. C. Gallo<sup>1</sup>, M. Domeier<sup>1</sup>, P.Y. Antonio<sup>2</sup>, F. Sapienza<sup>3</sup>, A. Rapalini<sup>4</sup>, E. Font<sup>5</sup>, T. Adatte<sup>6</sup>, R.I.F. Trindade<sup>7</sup>, F. Temporim<sup>8</sup>, J. Tonti-Filippini<sup>1</sup>, P. Silkoset<sup>1</sup> and L. Warren<sup>9</sup>*

*(1) Centre for Planetary Habitability, University of Oslo, Norway.*  
*(2) Géosciences Montpellier, Université de Montpellier, France.*  
*(3) Department of Geophysics, Stanford University, Stanford, United States.*  
*(4) Consejo Nacional de Investigaciones Científicas y Técnicas, Buenos Aires, Argentina.*  
*(5) Departamento de Ciências da Terra, Universidade de Coimbra, Portugal.*  
*(6) Institute of Earth Sciences (ISTE), University of Lausanne, Switzerland.*  
*(7) Department of Geophysics, University of São Paulo (USP), Brazil.*  
*(8) Faculdade de Ciências e Tecnologias, Universidade Federal de Goiás, Brazil.*  
*(9) Instituto de Geociências e Ciências Exatas, Departamento de Geologia, Rio Claro (SP), Brazil.*


## Contents
This repository contains all the notebooks and code required to reproduce our analysis. Using a high-resolution geochemical dataset collected alongside the rock magnetic data, we employ a Random Forest regressor trained on the geochemical features extracted from paleomagnetic samples to accurately predict the extent of remagnetization.

## Overview
In this project, we introduce a novel approach that integrates geochemical data with rock magnetic measurements. By training a Random Forest regressor on the extracted geochemical features, our method provides accurate predictions of remagnetization, offering improved insights into the associated geological processes.
Unlike traditional machine learning methods, which often prioritize predictive accuracy, our statistical learning framework focuses on uncovering the geochemical mechanisms behind remagnetization through feature importance analysis. This approach not only yields robust predictions but also offers valuable insights into the complex processes driving remagnetization.

## Repository Structure
 - Code: Detailed Jupyter notebooks that guide you through the entire analysis workflow—from data preprocessing and feature extraction to model training and evaluation.
 - Data: Documentation and links to the high-resolution geochemical and rock magnetic datasets used in our study.

## How to Reproduce the Analysis

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/LenGallo/Gallo-etal-2025_Statistical-Learning-Remagnetizations

2. **Set Up the Environment:**  
   ```bash
   conda env create -f environment.yml
   conda activate ml_env
3. **Run the Notebooks:**  
Open the Jupyter notebooks in the `ml_env` environment and execute the cells sequentially to reproduce the complete analysis pipeline.

### Run on Binder ☁️

To open a cloud JupyterHub version of the notebooks in this repository and run them on Binder used the following Binder link. Note that the repository will take a long time to load as the environment is being created: ![Binder](https://mybinder.org/badge_logo.svg)

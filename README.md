# AIMS26: Graph Neural Networks for designing organic materials

In this workshop, we explore how we can predict the properties of organic materials. It uses a published dataset containing density functional theory calculations of electron affinity and ionisation potential for ~6000 polymer photocatalysts. The workshop focuses on how chemists can represent organic materials in a machine-learning-friendly way. It has two parts:

## 1. Lecture and Interactive Workshop
This part explains why and how we use machine learning for property prediction of organic materials. It compares two approaches over three notebooks: 
1. The "fixed representations" approach, in which deterministic Morgan fingerprints are used to represent polymer structures.
2. A notebook visualising message passing with the graph neural network package Chemprop.
3. Utilising graph neural networks in Chemprop to learn hidden representations of polymer structures. 

|  | Description |
|:--------|-------------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S-AJ-H/AIMS26/blob/main/1_Fixed_representations.ipynb) | 1. Fixed Representations |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S-AJ-H/AIMS26/blob/main/2_Message_passing.ipynb) | 2. Message passing |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S-AJ-H/AIMS26/blob/main/3_Chemprop_representations.ipynb) | 3. Chemprop Representations |

## 2. Projects for further exploration
This part contains two projects which further explore graph neural networks for chemistry. These projects are designed to take ~3 hours to complete. They are:
- 4a. Project A: Polymer Representations with Chemprop: this explores the impact of using different SMILES strings as inputs to Chemprop.
- 4b. Project B: Structure-base Splitting with Chemprop: this explore the impact of chemistry-based splitting of training and validation data.

|  | Description |
|:--------|-------------|
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S-AJ-H/AIMS26/blob/main/4a_Project_A_Polymer_Representations_with_Chemprop.ipynb) | 4a. Project A: Polymer Representations with Chemprop |
| [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/S-AJ-H/AIMS26/blob/main/4b_Project_B_Structure_based_splitting_with_Chemprop.ipynb) | 4b. Project B: Structure-based Splitting with Chemprop |

## Resources:

>RDKit:   
>https://rdkit.org/docs/index.html

>Chemprop:  
>https://pubs.acs.org/doi/10.1021/acs.jcim.9b00237  
>https://pubs.acs.org/doi/10.1021/acs.jcim.3c01250  
>https://chemprop.readthedocs.io/en/latest/

>Data from:  
>https://pubs.acs.org/doi/full/10.1021/jacs.9b03591

>Polymer representations:  
>https://pubs.rsc.org/en/content/articlelanding/2022/SC/D2SC02839E

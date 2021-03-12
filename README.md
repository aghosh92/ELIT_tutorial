# ELIT_tutorial

The goal of the tutorial is to give a hands-on experience of introduction to image segmentation, utilizing Ensemble Learning Iterative Training (ELIT) framework to discover atom features.

In particualr, the notebooks address the following:

(1) How to apply a UNet-like neural network for semantic segmentation of atomic images and to perform; ii) how to apply multivariate statistical analysis to the semantically-segmented output.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg](https://colab.research.google.com/github/aghosh92/ELIT_tutorial/blob/main/01b_SemanticSegmentation_MZ.ipynb)


(2) How to construct a training dataset from ab-initio molecular dynamics (MD) data for a supercell of graphene atoms.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/ELIT_tutorial/blob/main/MD_data_labelled.ipynb)


(3) How to utilize ELIT approach to begin with training ensemble models using the simulated data, followed by using these models as baseline to adapt to experimental data. Here the goal is to find the carbon and impurity atoms present in the STEM image of graphene.

Adapted to the latest AtomAI version:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/ELIT_tutorial/blob/main/ELIT_tutorial.ipynb)

Parent Notebook:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/ELIT/blob/main/elit_graphene_v3b.ipynb)


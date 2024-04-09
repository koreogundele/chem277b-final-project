# CHEM277B Fall 2023
# Individual Final Project - Molecular Energy Prediction
## Olukorede Ogundele

In this individual project, I engineered two deep learning models—an Artificial Neural Network (ANN) and a Residual Neural Network—specifically designed for predicting molecular energies within the ANI1 dataset. To enhance the models' understanding of molecular structures, I employed the Many Body Tensor Representation, a method encoding structures through a distribution of various structural motifs. Leveraging Python packages, including numpy, scikit-learn, and PyTorch, I implemented and fine-tuned both the ANN and ResNet models.

Data files can be found here: https://figshare.com/articles/dataset/ANI-1_data_set_20M_DFT_energies_for_non-equilibrium_small_molecules/5287732. Files found in this directory are:

- predicting_ani_energies.ipynb: this Jupyter notebook contains all the code for unpacking and uncoding molecules and then building an running an ANN and RNN. It also contains commentary on what worked and what did not.

- trained_model.pkl: this is my trained ANN.

- trained_rnn.pkl: this is my trained RNN.

The subdirectory training_curves contains photos of saved training curves from the first vanilla run to the final product.

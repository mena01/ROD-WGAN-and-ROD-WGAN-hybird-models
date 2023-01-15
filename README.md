# ROD-WGAN-and-ROD-WGAN-hybird-models

ROD-WGAN and ROD-WGAN hybrid models have mimicked protein structure's distance matrices on various large scales.

In the molecular chemistry world, the functions, interactions, and bonds between proteins and each other depend on their tertiary structures; by adjusting their tertiary structures to modulate their interactions with other molecular partners, protein molecules are naturally dynamic under physiological conditions.We harness the great progress in the GenerativeAdversarialNetwork (GAN) to generate tertiary structures that closely mimic the natural features (backbone, local and distal characteristics) found in real proteins. In this research, we have revealed stable models (ROD-WGAN and ROD-WGAN hybrid) that are able to generate tertiary structures that mimic natural features. This has been achieved through four contributions. (1) Using the Ratio Of Distribution (ROD) as a penalty function in Wasserstein Generative Adversarial Networks (WGAN), (2) Developing a GAN network architecture based on fertilizing the residual block in the generator, (3) Coupling our GAN models with the hybrid loss function which involves generating an adversarial loss, perceptual loss, distance by distance loss, and structural similarity loss, and (4) Increasing the length of the amino acids to 256 aa. Our models are major steps towards robust deep-generation models that explore the extremely diverse set of structures that support the various activities of the protein molecule in the cell. Also, it provides a source of data augmentation for different important applications, such as molecular structure prediction, inpainting, dynamics, and drug design.

The dataset directory provides a PDB id for proteins, code to download PDB files, and code to generate a distance matrices "training data set".


The Network_Weights directory provides the weights of the generator network to generate distance matrices for the protein structure.

The six files represent the network architecture of ROD_WGAN 64aa, ROD_WGAN hybrid 64aa, ROD_WGAN 128aa, ROD_WGAN hybrid 128aa, ROD_WGAN 256aa, and ROD_WGAN hybrid 1256aa that generate distance matrices of proteins structure. To run as an example, just set the path of the Network_Weights directory.

![Distance matix](https://user-images.githubusercontent.com/73284871/212543083-641cf627-9625-4c4e-b821-b5363f891485.png)


We use the ADMM algorithm to fold the generated distance matrix.

![FoldingByADMM](https://user-images.githubusercontent.com/73284871/212543092-ed2a5db4-8bc3-4068-96b5-782c320ece0d.png)


We provide the generator network and its weight. In addition, the R code of folding protein structure.

The dataset directory provides a PDB id for proteins, code to download PDB files, and code to generate a distance matrices "training data set".








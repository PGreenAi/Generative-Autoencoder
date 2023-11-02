# Generative-Autoencoder
Autoencoding shape using deep generative networks
Autoencoder based on neural network are designed for image dimensionality reduction
by learning a representation, called latent space, from the given images and reconstruct
the images from that latent space as accurately as possible. The goal of this project is
to investigate the interpolation capability of optimal autoencoder (AE) architecture
to encode geometrical shape where the latent space is interpolatable. For this purpose,
toy datasets like disk and ellipse with distinguishable geometrical parameters are used.
We investigate the pitfalls of a standard AE in the generalisation of latent space to
interpolate unknown geometrical parameters. We have investigated the importance
of the loss function on interpolation capacity of the AE systems. We argue that
the interpolation capability of an autoencoder for data generated from continuous
geometrical parameter, could be improved by defining a proper loss function to
impose the convexity in the latent space. We used weighted loss function to improve
the convexity in the latent space. Additionally, to improve further the convexity in
the latent space a pairwise distance function between the input images and their
latent vector is added as a regularization term to the weighted lost function. Finally,
we demonstrate that the proposed algorithm improves the interpolation capability

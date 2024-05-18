# Variational_Autoencoders
This project is based on Variational Autoencoders
It describes how to reduce inputs to its latent features which is done by the encoder. A decoder reconstructs the data using the these latent features( using transpose convolution ). We can find the reconstructed data of the decoder is as close as the input data feed into the encoder. The project is an inspiration to GANs. The random variable z is converted to deterministic form. We call this as Reparametrized form. KL Divergence loss is calculated which is equivalent to the relative entropy. 

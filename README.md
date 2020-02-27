# Keras VAE

Some simple modifications of the keras VAE example found [here](https://keras.io/examples/variational_autoencoder/).

I added options for:

* `-n`: specify the name of the h5 file to save your weights. Default is `vae_mlp_mnist.h5`.
* `-e`: number of epochs to train for. Default is 50.
* `-r`: reverse the color of images (so that they are black numbers on a white background). Default is False (white numbers on black background).

Example usage:

` $ python model.py -n "my_model_weights.h5" -e 30 -r True`

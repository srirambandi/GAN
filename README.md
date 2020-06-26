# GAN and Wasserstein-GAN Implementations

This repo implements both the [Original](https://arxiv.org/abs/1406.2661) and [Wasserstein](https://arxiv.org/abs/1701.07875) Generative Adversarial Networks to generate image data. I implemented the code using my [ai](https://github.com/srirambandi/ai) open-source library! I chose to work with MNIST data, and to generate images similar to the dataset. You can refer to and run the notebooks on colab.

The repo also contains weights and sampled images of the models in data/GAN and data/WGAN directories.

- data/GAN has the weights of GAN Generator and Discriminator after 6000 iteration producing results as shown in Results section.
- data/WGAN has the weights of the Wasserstein-GAN's Generator and Critic after only 2400 iterations which doesn't yet generate quality images. I stopped the run as it's taking too long and many sessions on colab.

# Results

I ran the GAN for 6000 iterations and you can see the results in the notebook. The progress of sampled images for GAN:

![GAN Sampled Images](https://github.com/srirambandi/GAN/blob/master/data/GAN/gan.gif)

Results for WGAN are not yet available. You can run the model on colab and generate images for yourselves.

# References

I referred to the implementation for the structure of GANs from [lilianweng/unified-gan-tensorflow](https://github.com/lilianweng/unified-gan-tensorflow)

### License

MIT

### Author

Sri Ram Bandi / [@\_srirambandi\_](https://twitter.com/_srirambandi_)

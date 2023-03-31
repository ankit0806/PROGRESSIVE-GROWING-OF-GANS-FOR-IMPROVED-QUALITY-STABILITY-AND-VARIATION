# PROGRESSIVE-GROWING-OF-GANS-FOR-IMPROVED-QUALITY-STABILITY-AND-VARIATION

A new training methodology for generative adversarial networks. 

The key idea is to grow both the generator and discriminator progressively: starting from a low resolution, we add new layers that model increasingly fine details as
training progresses. This both speeds the training up and greatly stabilizes it, alllowing us to produce images of unprecedented quality, e.g., CELEBA images at
1024x1024.

Also proposes a simple way to increase the variation in generated imaages, and achieve a record inception score of 8.80 in unsupervised CIFAR 10.
Several implementation details that are important for discouraging unhealthy competition between the generator and discriminator.

A new metric for evaluating GAN results, both in terms of image quality and variation. As an additional contribution, constructed a higher-quality version of 
the CELEBA dataset.

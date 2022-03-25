**Project**

Generating logos by making use of GAN for marketing purposes to save costs 

Source: [14 Ways Machine Learning Can Boost Your Marketing - Metamaven](https://www.metamaven.com/14-ways-machine-learning-can-boost-marketing/#:~:text=GANs%20involve%20two%20competing%20networks,and%20another%20for%20generating%20voices.)

—

**Problem statement**

People in marketing constantly have to come up with catchy brand materials such as logos. Human logo creation is not scalable and costs can escalate quickly.

—

**Papers**

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/24134b47-3adc-4454-b7db-4fc03651284c/Untitled.png)

- [LoGANv2: Conditional Style-Based Logo Generation with Generative Adversarial Networks | Papers With Code](https://paperswithcode.com/paper/190909974)
- [LoGAN: Generating Logos with a Generative Adversarial Neural Network Conditioned on color | Papers With Code](https://paperswithcode.com/paper/logan-generating-logos-with-a-generative)

—

**Datasets**: [LLD - Large Logo Dataset (ethz.ch)](https://data.vision.ee.ethz.ch/sagea/lld/)

LLD comes in 2 flavours: LLD-icon & LLD-logo. For this project, LLD-logo will be chosen to work with the highest resolution dataset, LLD-logo. This dataset consists of 112.920 logos (13 GB). For this project, the cleaned version of the dataset is used (HDF5).

—

**AI Model**

- Encoder + DCGAN (source [LogoGAN: Creating Logos with Generative Adversarial Networks | Workshop Capstone - YouTube](https://www.youtube.com/watch?v=KCaFGCVnFfA))
- LoGAN (source https://github.com/ajki/LoGAN)
- LoGANv2 (source https://github.com/cedricoeldorf/ConditionalStyleGAN)
- ...

—

**Future ideas**

- Generating photorealistic images from sketches “Sketch your own GAN”
- Constrained Neural Style Transfer for Decorated Logo Generation

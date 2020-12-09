## Welcome to our paper webpage

### Abstract

Recent research has shown remarkable success in revealing “steering” directions
in the latent spaces of pre-trained GANs. These directions correspond to semantically meaningful image transformations (e.g., shift, zoom, color manipulations),
and have similar interpretable effects across all categories that the GAN can generate. Some methods focus on user-specified transformations, while others discover
transformations in an unsupervised manner. However, all existing techniques rely
on an optimization procedure to expose those directions, and offer no control over
the degree of allowed interaction between different transformations. In this paper,
we show that “steering” trajectories can be computed in closed form directly from
the generator’s weights without any form of training or optimization. This applies
to user-prescribed geometric transformations, as well as to unsupervised discovery
of more complex effects. Our approach allows determining both linear and nonlinear trajectories, and has many advantages over previous methods. In particular,
we can control whether one transformation is allowed to come on the expense of
another (e.g., zoom-in with or without allowing translation to keep the object centered). Moreover, we can determine the natural end-point of the trajectory, which
corresponds to the largest extent to which a transformation can be applied without incurring degradation. Finally, we show how transferring attributes between
images can be achieved without optimization, even across different categories
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```


### Link to the paper and Appendix

Check out our [paper](https://github.com/nsping13/GAN-steerability-without-optimization-/blob/main/Generative_image_manipulations_web_main.pdf) [Appendix](https://github.com/nsping13/GAN-steerability-without-optimization-/blob/main/Generative_image_manipulations_web_SM.pdf).

Code will be available soon
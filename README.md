# Difussion Model

Diffusion Models are class of generative models used in image generation. The Difussion Model works by gradually adding noise to the data and learning to reverse this process. 
<br>
The statement `learning to reverse this process` means undoing the noise that was added during the `forward` process.

## The key steps of Difussion Models are 
- **Forward process**: Gradually add noise to data at each step.
- **Reverse process**: Learn to predict and remove the noise at each step and reconstruct the original data.
- **Training**: Train the model to predict the noise added at each step.
- **Generation**: To create new data, we can start with `Pure Noise` ( eg. add random pixel values for an image, the noise is typically Gaussian to follow normal distribution)

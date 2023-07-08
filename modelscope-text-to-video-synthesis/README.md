# ModelScope Text to Video Synthesis

The text-to-video generation diffusion model consists of three sub-networks: text feature extraction, text feature-to-video latent space diffusion model, and video latent space to video visual space. The overall model parameters are about 1.7 billion. Support English input. The diffusion model adopts the Unet3D structure, and realizes the function of video generation through the iterative denoising process from the pure Gaussian noise video.

It requires 4 CPUs/16G RAM/1 GPU.

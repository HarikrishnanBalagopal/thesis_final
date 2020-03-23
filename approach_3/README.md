# Approach 3
Generate image-text pairs simultaneously, train jointly.

## Experiments
1. Noise to latent vectors, latent to image and latent to text decoders. Joint discriminator for image and text. Text discriminator using policy gradients.
2. Same as above with U-NET based image discriminator.
3. Same as 1. with heirarchical cross-model attention.


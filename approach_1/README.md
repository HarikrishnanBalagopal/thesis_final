# Approach 1
Generate images, generate captions conditioned on images.
This splits into 2 tasks: Image generation and Image captioning.

# Image generation
Images can be generated unconditionally or conditionally given a class. It MUST NOT use text to generate the image.

## Experiments
1. DCGAN
2. PGAN
3. StyleGAN
4. StyleGAN 2
5. BigGAN

# Image captioning

## Experiments
1. CNN + RNN
2. CNN + RNN with global attention


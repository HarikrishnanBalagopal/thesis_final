# Approach 2
Generate text, generate images conditioned on text.
This splits into 2 tasks: Text generation and Text to image generation.

# Text generation
Text can be generated unconditionally or conditionally given a class. It MUST NOT use images to generate the text.

## Experiments
1. RNN
2. RNN with global attention.
3. RNN with discriminator using policy gradients.
4. SeqGAN

# Text to image generation
Generate images given text.

## Experiments
1. AttnGAN
2. StackGAN
3. StackGAN++


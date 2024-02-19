# Experiments in Diffusion

This repository contains various notebooks experimenting with using Stable Diffusion for image generation on Google Colab.

## Notebooks

1. **inference_steps_video.ipynb**: This notebook generates a video from a prompt using different numbers of inference steps, demonstrating the effect of varying the number of steps on the output.

    - An example generated video can be found [here](https://vimeo.com/914370372?share=copy).

2. **abstract_diffusion.ipynb**: This notebook prompts the user for a description of their mood and generates an abstract image based on this input using just a few inference steps.

   - **index.html** and **style.css** create a webpage to display the generated images along with an embedded song that reflects each mood, which can be found [here](https://jacquelinegrimm.github.io/experiments-in-diffusion/).

## Running Notebooks

Before running these notebooks on Colab, allocate a GPU by selecting "Change runtime type" under the "Runtime" menu.

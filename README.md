# Computer Vision (CSCI-GA.2271) Final Project Repository
## Author: Sunny Son

This repository is primarily for the Final Proejct for Computer Vision.

The experimentation is broken up into Ablation and Training, where

- Ablation: Found in the folders `ablation_study`, is the notebook to attempt different neural network combinations, as well as the results of each combination (the last epoch) after being trained for 100 epochs.

    - Usually, data would be downloaded in the `data` folder, however given its size, GitHub was unable to take the files

- The main Experiment: Two separate models trained under two separare notebooks, `ddpm_cancerous` and `ddpm_non-cancerous` which adds the feature of training where would else be left off (or training ended early), due to potential bugs or usage limits implemented when training on Google Colab.

Enjoy these reverse diffusion images!

![reversediffusion1](https://github.com/sunnydigital/cv-f22/blob/main/images/gifs/cosine_beta_schedule-no_attention43-interval10.gif)
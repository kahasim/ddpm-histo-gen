# Computer Vision (CSCI-GA.2271) Final Project Repository
## Author: Sunny Son

This repository is primarily for the Final Proejct for Computer Vision.

The experimentation is broken up into Ablation and Training, where

- Ablation: Found in the folders `ablation_study`, is the notebook to attempt different neural network combinations, as well as the results of each combination (the last epoch) after being trained for 100 epochs.

    - Usually, data would be downloaded in the `data` folder, however given its size, GitHub was unable to take the files

- The main Experiment: Two separate models trained under two separare notebooks, `ddpm_cancerous` and `ddpm_non-cancerous` which adds the feature of training where would else be left off (or training ended early), due to potential bugs or usage limits implemented when training on Google Colab.

Note: Will be soon updating code to a conditional DDPM version, accepting classes of images dependent on a label through affected time embedding.

For now, enjoy these trippy reverse diffusion image!

<style>

<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>How to create side-by-side images with the CSS float property:</p>

<div class="row">
  <div class="column">
    <img src="img_snow.jpg" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="img_forest.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="img_mountains.jpg" alt="Mountains" style="width:100%">
  </div>
</div>

</body>
</html>

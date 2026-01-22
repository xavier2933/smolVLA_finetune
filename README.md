# Fine Tuning SmolVLA for New Environments
<p align="center">
  <img src="assets/success_vla.gif" alt="GIF of arm picking up block">
</p>

This is the code associated with [my article](https://medium.com/correll-lab/fine-tuning-smolvla-for-new-environments-code-included-af266c56d632) about my experience fine tuning a smolVLA to complete a simple pick task in a new environment. This process involved overcoming several hurdles, which I've detailed in the medium article. This code is **not** meant to be production ready, and probably will not work with your system. It is, however, meant to provide a reference of the techniques and functions needed to perform some of these huggingface-specific actions, as they are not well documented on the internet. 

## A note on the lerobot environment
This project uses lerobot 0.4.3, which follows the newer API. See the requirements.txt for a complete list of packages required for this project.


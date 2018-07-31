# CCTV-Street-Garbage-Detection
This program classifies an input image (Image of street from CCTV Camera) as clean/unclean. This can later be used to automatically send alerts to respective authorities when a street is found to be unclean.
Once a street is found to be unclean, it automatically sends an email alert to the respective authorities who can then take action.

This program makes use of the tensorflow library to classify images from the camera as clean or unclean based on a few hundred traning images that were manually selected.

## Run
> python -m scripts.detect --graph=files/retrained_graph.pb --image=<path of image from CCTV Camera>

# BodySegment_Webcam
Python code for removing or changing the background during video chat sessions, such as in Teams or Zoom.

To enhance the training of The Face Synthetics model, a dataset of 1000 images from the FaceSynthetics repository (https://github.com/microsoft/FaceSynthetics) was utilized. However, it is recommended to further improve the resulting weights by incorporating additional real images along with their corresponding ground truth data for training. This approach can lead to better model performance and accuracy.

The timm-mobilenetv3_small model has been selected to execute the code on low-power PCs. This model is specifically designed to be lightweight and efficient, making it suitable for running on devices with limited computational resources

## TODO
- [ ] Enhance the detected contour smoothing for a more natural transition between the foreground and background.

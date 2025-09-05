# Image-captioning
Image captioning models take an image as input, and output text. Ideally, we want the output of the model to accurately describe the events/things in the image, similar to a caption a human might provide. For example, given an image like the example below, the model is expected to generate a caption such as "some people are playing baseball.".

In order to generate text, we will build an encoder-decoder model, where the encoder output embedding of an input image, and the decoder output text from the image embedding

I this notebook, we will use the model architecture similar to Show, Attend and Tell: Neural Image Caption Generation with Visual Attention, and build Attention-based image captioning model.

This notebook is an end-to-end example. The training dataset is the COCO large-scale object detection, segmentation, and captioning dataset.

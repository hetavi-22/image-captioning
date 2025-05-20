# Image Captioning using CNN + Transformer

This project is about generating captions for images — basically getting a model to look at an image and describe what’s going on in a natural sentence. The idea was to combine computer vision and NLP to build a simple image captioning system from scratch.

It takes an image, extracts features using a pretrained CNN, then passes those through a transformer decoder to generate a caption word-by-word. The frontend is for uploading images and showing results.

## What this project does

- Loads images and their captions (sampled from the COCO dataset).
- Preprocesses both the images and text captions.
- Uses InceptionV3 to extract visual features.
- Passes those features into a Transformer decoder that generates the caption.
- Trains the whole model end-to-end and allows caption generation on new images.


## How to use

1. Clone the repo
2. Make sure TensorFlow and the other dependencies are installed
3. Run the training script if you want to train from scratch (optional)
4. Use the inference script to try it on new images


## Model evaluation

- Training Loss: 2.7
- BLEU-4 Test score: 0.4211
- CLIPScore (avg across test images): 0.45

---



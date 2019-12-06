# Image-Captioning

Image Captioning:
We designed a deep learning model which accepts images features along with its possible captions as input.
The model predicts the image caption of test images.
We used pre trained inception V3 model to generate image features.
We mapped caption words using pre trained Glove embedding model.
We used data generator to efficiently train the model.
We tested the trained model on new images.

Dataset:
We used Flickr 8K dataset, it contains 8000 images along with 5 possible captions for each image.

Download Glove embeddings from the following link [We couldnt add to Glove data to github because space limitation]
http://nlp.stanford.edu/data/glove.6B.zip

References:
https://medium.com/analytics-vidhya/basics-of-using-pre-trained-glove-vectors-in-python-d38905f356db
https://cs.stanford.edu/people/karpathy/sfmltalk.pdf
https://medium.com/mlreview/multi-modal-methods-image-captioning-from-translation-to-attention-895b6444256e
https://towardsdatascience.com/image-captioning-in-deep-learning-9cd23fb4d8d2
https://www.tensorflow.org/tutorials/text/image_captioning
https://medium.com/@sh.tsang/review-inception-v3-1st-runner-up-image-classification-in-ilsvrc-2015-17915421f77c
https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8
https://medium.com/@sh.tsang/review-inception-v3-1st-runner-up-image-classification-in-ilsvrc-2015-17915421f77c
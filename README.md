# road-image-segmentation
Semantic 2D Image Segmentation.


This is a script to train and evaluate a semantic 2D image segmentation model built and trained from scratch on a public dataset(available on kaggle).
The results are mind blowing and helps one understand the task of semantic image segmentation clearly.
Used Tensorflow 2 and Python for the same and built the model using the Functional API approach available in Tensorflow.
Used VGG19 for the encoder and built the bottleneck and decoder from scratch.
Also one of the other main attraction of this is the extensive EDA and preprocessing done before model training.

<h2>MODEL METRICS</h2>
EPOCHS = 21 (until ran out of GPU quota)

<h3>TRAINING</h3>
LOSS(CATEGORICAL CROSSENTROPY): 0.1125

METRICS(MEAN INTERSECTION OVER UNION) = 73.23%

<h3>VALIDATION</h3>
LOSS(CATEGORICAL CROSSENTROPY): 0.2350

METRICS(MEAN INTERSECTION OVER UNION) = 52.13%

<h3>TESTING</h3>
LOSS(CATEGORICAL CROSSENTROPY): <YET TO FIND>

METRICS(MEAN INTERSECTION OVER UNION) = <YET TO FIND>

LINK: https://colab.research.google.com/drive/1vgUjdiRbzqW-n73onClzJjEIbapi7njc?usp=sharing

Please upvote if found this useful.

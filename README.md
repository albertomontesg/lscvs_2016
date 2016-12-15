# Temporal Activity Detection in Untrimmed Videos with Recurrent Neural Networks

## Abstract

This work proposes a simple pipeline to classify and temporally localize activities in untrimmed videos. Our system uses features from a 3D Convolutional Neural Network (C3D) as input to train a a recurrent neural network (RNN) that learns to classify video clips of 16 frames. After clip prediction, we post-process the output of the RNN to assign a single activity label to each video, and determine the temporal boundaries of the activity within the video. We show how our system can achieve competitive results in both tasks with a simple architecture. We evaluate our method in the ActivityNet Challenge 2016, achieving a 0.5874 mAP and a 0.2237 mAP in the classification and detection tasks, respectively.

## Publication

This is a paper for the [1st NIPS Workshop on Large Scale Computer Vision Systems](https://sites.google.com/site/largescalecvsystems/). Check on ArXiv [here](https://arxiv.org/abs/1608.08128). Please cite with the following Bibtex code:

```
@InProceedings{Montes_2016_NIPSWS,
    author = {Montes, Alberto and Salvador, Amaia and Pascual, Santiago and Giro-i-Nieto, Xavier},
    title = {Temporal Activity Detection in Untrimmed Videos with Recurrent Neural Networks},
    booktitle = {1st NIPS Workshop on Large Scale Computer Vision Systems},
    month = {December},
    year = {2016}
}
```

## Code

All the code related with this publication can be found in:
```
https://github.com/imatge-upc/activitynet-2016-cvprw
```

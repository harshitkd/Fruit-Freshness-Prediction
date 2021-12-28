# Fruit-Freshness-Detection

## Introduction
What's Fresh & What's Rotten is our way to solve problem about fruits classification whether it is rotten or it is fresh (safely can be eaten) using Deep Learning. We do simple CNN to expect some basic performance this simple CNN had in the dataset. Then we improved the model by adding Transfer Learning with VGG-16 and ResNet50 as our baseline model.

## Dataset
Used the [Fruit fresh and rotten for classification](https://www.kaggle.com/sriramr/fruits-fresh-and-rotten-for-classification) kaggle dataset.
The dataset contains 13599 images of apple, banana and orange divided into fresh and rotten each.

Dataset       | Directories     | Files
------------- | -------------   | -------------
Train         | freshapples     | 1693
|             | freshbanana     | 1581
|             | freshoranges    | 1466
|             | rottenapples    | 2342
|             | rottenbanana    | 2224
|             | rottenoranges   | 1595
Test          | freshapples     | 395
|             | freshbanana     | 381
|             | freshoranges    | 388
|             | rottenapples    | 601
|             | rottenbanana    | 530
|             | rottenoranges   | 403


## Algorithm

## CNN

## Result

Model                      | Total Parameters     | Loss     | Accuracy
-------------              | -------------        | -------- | ----------
Sequential 3 layer         | 9,497,126            | 0.0960   | 96.96%
ResNet50V2                 | 23,696,326           | 0.0259   | 97.41%

## Future Enhancement

## Conclusion

## References
I have taken references from:
* [Research Papers](https://github.com/harshitkd/Fruit-Freshness-Prediction/tree/main/reference%20Docs)
* [A guide to an efficient way to build neural network architecture](https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7)
* [Convolutional neural network for visual recognition](https://cs231n.github.io/convolutional-networks/)




# Fellowship.ai Challenges

[Fellowship.ai](https://fellowship.ai/challenge)

## Food-101

***[Solution](https://github.com/TheCaffeineDev/Fellowship.ai-Challenges/blob/master/Food-101/Food-101.ipynb)***

[Food-101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/) is a challenging vision problem, but everyone can relate to it.  Recent SoTA is ~80% top-1, 90% top-5.  These approaches rely on lots of TTA, large networks and  even novel architectures.

Train a decent model >85% accuracy for top-1 for the test set, using a ResNet50 or smaller network with a reasonable set of augmentations.


## One Shot Learning

***[Solution](https://github.com/TheCaffeineDev/Fellowship.ai-Challenges/blob/master/One%20Shot%20Learning/One_Shot_Learning_Omniglot.ipynb)***

***[Google Colab Notebook](
https://colab.research.google.com/drive/1tgJnxdefACoq7-XYU5IUBO9aBSKgs1ua)***

* [Omniglot](https://github.com/brendenlake/omniglot) the “transpose” of MNIST, with 1623 character classes, each with 20 examples. 

* Use background set of 30 alphabets for training and evaluate on set of 20 alphabets. Refer to this script for sampling setup.

## ULMFiT Sentiment

***[Solution](https://github.com/TheCaffeineDev/Fellowship.ai-Challenges/blob/master/One%20Shot%20Learning/One_Shot_Learning_Omniglot.ipynb)***

***[Google Colab Notebook](
https://colab.research.google.com/drive/1IilJf4dl6S1JS5kxGUaaheIpIJ8OS9fL)***

*  Apply a supervised or semi-supervised [ULMFiT](http://nlp.fast.ai/classification/2018/05/15/introducting-ulmfit.html) model to [Twitter US Airlines Sentiment](https://www.kaggle.com/crowdflower/twitter-airline-sentiment#Tweets.csv)

* Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service"). It contains whether the sentiment of the tweets in this set was positive, neutral, or negative for six US airlines

# Venomous Snake Classifier

Upon seeing a snake, if you want to know whether the snake is venomous or not, you may use this web-tool 
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/akhilpotdar1/Venomous_snake_classifier/master?urlpath=%2Fvoila%2Frender%2FVSnake_classifier.ipynb)

CAUTION! Please do note that this classifier is not a perfect one as it has classfied non-venomous snakes as venomous ones. Hence the classifier will detect most of the snakes to be venomous even if its not. While this may cause inconvinience to snake enthusiasts, an average Joe, would love to know if the snake in the backyard is approachable or not. 

Also approach all snakes at your own peril :P 

P.S.: This tool will not classify whether the image has a snake or not, hence a photo of yourself too will be classified. :P

You can access this at https://mybinder.org/v2/gh/akhilpotdar1/Venomous_snake_classifier/master?urlpath=%2Fvoila%2Frender%2FVSnake_classifier.ipynb

This model is made using resnet18 pre-trained network. Fine-tuning was performed using fastai. The data set is created using images from bing search. This application is inspired from the bear classifier seen in the fastai book chapter 2 (https://github.com/fastai/fastbook/blob/master/02_production.ipynb) 

# Sports-Image-Classification
 Predicting given image to what class of sport it belongs among 6 types of sports ( basket, rowing , swimming , football, Yoga , Tennis ). Explored and visualized data to understand it. Preprocessed the data by normalizing it and making data augmentation to avoid overfitting when training the model. Scraped data from Bing search engine. Balanced the data by making weighted random sampler. Implemented different CNN architecture from scratch (VGG, ResNet, GoogleNet, EfficientNet) and using pre-trained weights. Modified some of the models by replacing the batch normaliztion by pixel normalization which is normalizes the feature vector in each pixel to unit length, which prevent signal magnitudes from spiraling out of control during training. Another Modification is scaling weights of a layer according to how many weights that layer have, which make the layers learn at a similar speed. Implemented transformer from scratch for this task. Combined CNN with transformer. Evaluated the models and choose the best one based on the score of the validation set.
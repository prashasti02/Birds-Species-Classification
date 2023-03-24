# Birds-Species-Classification

Used MobileNet from various models like VGG16, AlexNet, GoogleNet because of its low latency, low complexity and most importantly less training time. 

After setting the epoch size to 64 and batch size to 64 and steps per epochs to len(train_data), we were able to reduce the training time of the model from 12-15 hours to 3-5 hours at the cost of 2% accuracy, later we tested our model on several different bird species and every time we got correct results.

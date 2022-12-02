# IMAGE-CAPTIONING

Used Neural Networks to automatically caption the images in Flickr 8K Dataset.

Repurposed the InceptionV3 model by removing the softmax layer to enable transfer learning. This output of the network is fed as the image data to the neural Network.

The Long Short Time Memory(LSTM) is used as the Network to process the partial captions generated after each iteration.






# Sample Predictions

![ic1](https://user-images.githubusercontent.com/32400008/64564089-6839ea00-d36e-11e9-8a43-a50c66c1d244.PNG)
![ic3](https://user-images.githubusercontent.com/32400008/64564172-97505b80-d36e-11e9-9246-e73c1569215d.PNG)
![ic4](https://user-images.githubusercontent.com/32400008/64564173-97505b80-d36e-11e9-8c84-ebb832276a1a.PNG)
![ic2](https://user-images.githubusercontent.com/32400008/64564175-97505b80-d36e-11e9-9bbe-20bbbc387661.PNG)

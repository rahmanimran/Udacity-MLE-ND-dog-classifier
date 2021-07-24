## Project Overview

In this capstone project I will build a machine learning model which will process images. If an image of a dog is provided, the model will identify its breed. If an image of a human is provided, the model will identify the most resembling dog breed.

## CNN model created from Scratch:

I created a CNN model from scratch. It gave an accuracy of 12% after 10 epochs. Benchmark was considered at 10%.

## CNN model created using Transfer Learning:

To increase the accuracy I used the transfer learning model. ResNet-101 architecture was selected for this. It comes with 101 layers. I increased the out_features to accommodate 133 layers. After 5 epochs the accuracy came as 82%, which is very good compared to the benchmark model. Increasing epochs would increase the accuracy I believe. This architecture is suitable because rsnet101 is already pre-trained.


## Final Words
An accuracy of 82% seems very good to me. The output is better than I expected. It can classify human and dogs. After providing an image of a cat and a cycle it showed the error message.


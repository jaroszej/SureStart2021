After comparing the performance of a model implementing a convolutional neural network (CNN) on a portion of a dataset to the performance on the entire dataset I understand that each can have some advantages.
First, a model was made to learn from a sample of the MNIST Database containing 42,000 images of written numbers. This model performed well, achieving an accuracy of about 93% after 10 epochs.
The second model, label t10k, would use almost 60,000 images of written numbers. This model would outperform the first model, achieving an accuracy of about 95% and achieving an accuracy of 93% after only # epochs.
The second model needed a lot more data than the first did to achieve that 2% improvement. I would consider both of these models successful and would prefer to have access to the full set of data in future projects but I would also feel assured that my models will be proficient when given only 70% of a dataset.
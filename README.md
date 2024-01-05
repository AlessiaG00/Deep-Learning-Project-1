# Deep-Learning-Project-1

This deep learning project aims to predict age based on images depicting faces of individuals of different ages. The project was carried out in collaboration with 2 university colleagues.

The dataset used consists of 23,813 images, each sized 200x200 pixels, portraying individuals ranging in age from 1 to 116 years.

To achieve our goal, we started by using the well-known AlexNet model, with some minor modifications to the activation function (we used the sigmoid function instead of the linear function, which better suited our objective) and the number of nodes employed. 

We used Mean Squared Error (MSE) as the loss function. This metric was also utilized to evaluate the performance of our model. To better comprehend the results, the square root of the MSE was taken and interpreted as the average error in predicting the true age from the image.

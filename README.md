here i built some basic level ml model using pytorch . And i used a jupyter note book to build these models , also a python libraries .
PREREQUIRTIES
    1.)python environment or conda envo for programming 
    2.)python libraries like numpy , pandas , matplotlib , scipy....
    3.)pytorch or tensorflow , but here i used a pytorch for my model development
    4.)basic knowledge on programming.
01.] initially i did some basic pytorch programming like creating tensors using pytorch and operations on it
02.] secondly we go for linear regression model for predicting the output , we use stochastic gradient descent for calculating loss.
03.] thirdly we gor image classification on mnist digits using logistic regression model , here we use totensor transform , dataset, dataloader for developing model.
04.] fourthly we go for image classification using neural network , here we create a neural layers between the input and output that helps us to predict the output more efficiently and quickly so this method helps us to deal with real world applications.
05.] fifthly we classify the image using cnn(convolutional neural network) here we use kernels to read the input and weights and create the convolutional layers this helps us to predict the output more easily , but while using cnn we need more data to train the model otherwise it leads to "overfitting" , at the same time when we have more data to train , validate , test our model it takes more time to get the predicted output, so we use gpu's for runtime. 

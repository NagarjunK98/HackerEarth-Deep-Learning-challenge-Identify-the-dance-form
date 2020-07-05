# HackerEarth-Deep-Learning-challenge-Identify-the-dance-form
<h2>Problem statement : "Identify the dance form"</h2>
* The training dataset consists of 364 images belonging to 8 categories, namely <b>manipuri, bharatanatyam, odissi, kathakali, kathak, sattriya, kuchipudi, and mohiniyattam</b> and the testing dataset consists of 156 images.
<h2>Training model : </h2>
Number of epochs = 50.
Batch_size = 8
Optimizer = Adam
loss = categorical_crossentropy
Metrics = Accuracy
<h2> Input to the model : </h2> Images are converted into gray from RGB color and resized to 256x256 shape.
<h2>Libraries used : </h2>Tensorflow, keras, numpy, pandas and matplotlib
<h2> Layers used : </h2> Conv2D, Dense, Maxpooling, Flatten and Droupout layers.
<h2>Activation functions used : </h2> relu and softmax function

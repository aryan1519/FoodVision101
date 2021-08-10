
# FoodVision101

This is a multiclass-classification model that classifies images of food into one of 101 classes. It gives a confidence % and displays top-5 possible foods.

EfficientNetB0 is used as the base model and is fine tuned according to the use case.

The model is trained on ~75,000 images and acheives an accuracy of around 80% which improves on the previous work done in DeepFood.

The project is build entirely in Python.
Numpy,Pandas,matplotlib are used along with Tensorflow.

The model can be used in a user-friendly environment in which the user can simply upload an image and get the top-5 results. This is done using gradio.




## Screenshots

![App Screenshot](https://www.linkpicture.com/view.php?img=LPic6112bbb33d1101607837983)

![App Screenshot](https://ibb.co/8ck0xVh)

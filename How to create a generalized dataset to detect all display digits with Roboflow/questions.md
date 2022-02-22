
# I want to detect digits on a display. 

For doing that I am using a custom 19 classes dataset. The choosen model has been yolov5-X. The resolution is 640x640. Some of the objets are:

- 0-9 digits
- Some text as objects
- Total --> 17 classes

I am having problems to detect all the digits when I want to detect 23, 28, 22 for example. If they are very close to each other the model finds problems.

I am using roboflow to create diferent folders in which I add some prepcocessings to have a full control of what I am entering into the model. All are checked and entered in a new folder called TRAIN_BASE. In total I have 3500 images with digits and the majority of variance is with hue and brightness.

Any advice to make the model able to catch all the digits besides being to close from each other?

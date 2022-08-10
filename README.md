# CNNs-for-geophysical-imaging

My dissertation project. I created a synthetic dataset of a "world" which contained between 1-3 objects (ellipses or rectangles) which varied in size
and location. The world also had 3 layers which varied in size. These objects and layers were attributed randomised electrical resistivity values of between
10 and 1200 ohms. This produced an image of "apparent resistivity". The apparent resistivity and true model images were saved. 

These images will serve as the input for the convolutional neural network. The goal is for the CNN to be given apparent resistivity images/values and be 
able to predict what the true model looks like, i.e. where the objects are, what their size is, how deep the layers are, etc. 

The first model is a simple UNET. Intersection over Union (IoU) is the metric used to measure improvement. 

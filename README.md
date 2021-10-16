# indian-food-vision
A computer vision model which predicts the name of the indian food through its image. It uses transfer learning and I have used resnet50v2 and efficient_netb0 models which are pretrained Convolutional neural network models imported from the tensorflow hub to predict the name of the dish.

> ##### **Dataset used :**  **`Indian-food-classification`**

> ##### **Model Used :** **`EfficientNetB0`** and **`Resnet50V2`**

> ##### **Accuracy :** **`91%`**



## Okay 
> If you actually want to know the Nuts and Bolts how the model was trained check out **[`model-training.ipynb`](https://github.com/gauravreddy08/food-vision/blob/main/model_training.ipynb) Notebook**

1. #### Imported Food101 dataset from **[indian-food-classification](https://www.kaggle.com/theeyeschico/indian-food-classification)** Module.


We are dealing with a complex Neural Network (EfficientNetB0) its a good practice to have few callbacks set up. The one I have used in here is:

   - **TensorBoard Callback :** TensorBoard provides the visualization and tooling needed for machine learning experimentation



######                                             


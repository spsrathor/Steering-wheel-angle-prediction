# Steering-wheel-angle-prediction
Steering wheel angle prediction by using dashcam images

Dataset was taken from [here](https://drive.google.com/file/d/1Ue4XohCOV5YXy57S_5tDfCVqzLr101M7/view). Dataset contains 45,500 images taken from dashcam of the car along with angles.

A CNN model is used for prediction of the angles. L2 Loss function is used along with Adam optmizer and atan (inverse of tan) as activation function.

Basic flowchart of the complete process is given below-
![flowchart](https://user-images.githubusercontent.com/62622079/182952595-5d315a27-7073-4f25-a89d-182d3f83b0d4.png)

Firstly, run `train.py` to train the model and save the trained model.
Use `run_dataset.py` to get live results as shown below.

Screenshot of the final application is shown below.
![Screenshot from 2021-05-08 08-10-17](https://user-images.githubusercontent.com/62622079/182952991-a7a98aa5-dccc-43dc-9548-2a1c9117d39f.png)

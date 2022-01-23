# OU-CSI5130
Self driving car project

We use behavior cloning technique via Machine Learning and Convolutional Neural Network (CNN).  
1. The training data is based on people’s actual driving behavior in car simulator 
  a. Collected through 3 dash cameras, including a direct-front-facing, left-front-facing and right-front-facing camera. 
  b. Saved the steering wheel angle, acceleration, brake and vehicle speed records along with the camera images. 
2. This driving record is then used to train our proposed CNN. 
3. Once the model is trained, use it to process new vehicle dash cam image and predict wheel angle and drive the vehicle per input driver’s driving behavior. 
4. The proposed approach proved successful in cloning the driving behavior embedded in the training data set.

# Environmental features recognition
 <img src='./Environmental-feature-recog.jpg' width=50%>

We present a robust environmental features recognition system (EFRS),which can assist the control of exoskeleton by estimating environmental features in the following steps. A depth sensor and an inertial measurement unit (IMU) are combined to stabilizethe point cloud of environments. Subsequently, the 2D point cloud is extracted from origin 3D point cloud and is classified through a neural network. Environmental features, including slope of road, width,and height of stair, were also estimated via the 2D point cloud. 

This repository includes 2D binary image dataset and a CNN model based on Keras.  You can test and train the model directly by running the file: classification.py.

## Run

```bash
python classification.py
```

I just uploaded the environmental classification algorithm because I think it should be the most useful part. If you want me to upload the image preprocessing and environmental parameter estimation part, please leave a message in the issue or send an email to me directly. 


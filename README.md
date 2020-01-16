# Ball Motion Prediction using Kalman_Filter

The Kalman filter has many uses, including applications in control, navigation, computer vision, and time series econometrics. In this project, I have used Kalman Filter to detect the motion of a ball in a video clip.
The Kalman filter is used for object tracking when you have estimates of object position, measured with error. Predicting the object’s next position requires not just knowing the previous position, but knowing things like velocity and acceleration.
Any filter takes current measurements of position, updates estimates of state variables (including the estimate of position, the filter will not accept the new measurement as errorless), and then predicts future positions. If there is no measurement available, the filter just continues predicting by evolving the state variables from the last measurement. Every measurement leads to a revised estimate of state.
Kalman filters are a particularly simple version of filtering, that works well when dynamics are known and smooth (like Newton’s laws of motion) and error probability declines smoothly with error size.

I performed the required image processing to get ball coordinated in the video by using Kalman Filter.

I used various techniques like Morphological Operations, Thresholding, Filtering etc.

Programming Language Used : Python

Package Used : OpenCV, Numpy, SYS

Platform Used : Windows 10

Software Used : Jupyter Notebook

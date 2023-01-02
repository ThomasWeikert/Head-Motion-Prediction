# Head-Motion-Prediction
Comparing Deep Learning to state of the art method double exponential smoothing and and a baseline, the time-lagged time series by 100 milliseconds.

Keywords:
- Tensorflow, Keras
- Numpy, Scipy, Seaborn, Matplotlib
- Varjo
- Pre-Processing
- Gated Recurrent Units
- Double Exponantial Smoothing

Context:
Extended Reality enables 3D content to be experienced with six degrees of freedom with head-mounted displays (HMD). Since rendering XR experiences with head-mounted displays (HMD) requires prohibitively high computational power, the use of remote rendering (RR) can outsource the required computational power. One drawback of this solution is the increased interaction latency (motion-to-photon), which can lead to latency errors in XR applications. One possible approach to mitigate this problem is to predict the viewer’s head pose in order to pre-load the appropriate content. A suitable time frame for predicting future head motion is 100 milliseconds, as this is approximately the round-trip time of the data in an average remote rendering environment. To predict the immediate future (100 milliseconds) head motion, a method based on Gated Recurrent Units is presented to model the position and rotation of the user’s head. The model is compared to a state-of-the-art method, Double Exponential Smoothing Prediction (DESP), and a baseline, the time-lagged time series by 100 milliseconds. The developed models meet the goals of the work: the models outperform the state-of-the-art method DESP and the selected baselines in head position and rotation. The results show great potential for further investigation of Deep Learning methods for head motion prediction in the future.

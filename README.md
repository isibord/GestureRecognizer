# Gesture Recognizer
Imagine working for a company that would like to use the phone as an input device to an interactive video game system like the XBox or Playstation--for example, using the phone as a paddle in tennis or as a "ball" in bowling. In this project, I built my own 3D gesture recognizer to automatically recognize these gestures.

While in the "real world" you would ultimately need to create a real-time gesture recognizer, this is an offline version in Jupyter Notebook. There are two regonizers: 
(i) a shape-matching recognizer
    Euclidean distance metric and Dynamic Time Warping
(ii) a feature-based (or model-based) recognizer using a support-vector machine (SVM) 

The gestures were recorded with the [A2: Gesture Logger](https://github.com/jonfroehlich/CSE590Sp2018/tree/master/A02-GestureLogger).


## Getting Started
1. The first thing you need to do is to ensure the logPath variable to points to the directory with your gesture logs. Scroll down to the "Load the Data" cell
2. Then, you should be able to select Cell->Run All in the File Menu above and the data should be read in.
3. Note that the Dynamic Time Warping (DTW) API can be slow (up to 15 minutes), the code will print progress updates. 

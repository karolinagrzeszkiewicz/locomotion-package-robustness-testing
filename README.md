# locomotion-package-robustness-testing
This repository contains the scripts I used for robustness testing as part of development work for the locomotion package created by Prof. Matthew Stamps and his collaborators. 

The Python package contains computational geometric tools for quantifying and analysing animal behaviour and is intended for use by neuroscientists. One of the measures of similarity between animal behaviour is the Behavioural Distortion Distance (BDD) depending on height, velocity, and curvature. 

Since the input for analysis is in the form of data files (csv or xls) corresponding to a recording of animal motion with a camera, in the scripts below I examine how sensitive the BDD is to differences in frame rate and pixel density of the camera (ideally it should not be too sensitive). I also determine whether the visible differences are statistically significant. I attribute the differences to some mathematical methods used in the BDD computation, such as the parameters of the Savitzky-Golai smoothing function.

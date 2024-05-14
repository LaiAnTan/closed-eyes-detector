# closed-eyes-detector

A random Jupyter notebook that i whipped up to use computer vision to detect closed eyes, for the demo in FIT1055's A2b presentation.

## Dependencies

- opencv - for computer vision
- dlib - for face / eyes prediction
- [shape_predictor_68_face_landmarks.dat](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) - model for face prediction

## Installation and Usage

1. install opencv, dlib (preferabally in a conda env)
2. download and extract shape_predictor_68_face_landmarks.dat and put it in the same directory
3. run the code

It has a high chance of not working in WSL as the kernel has to be recompiled to support webcams from the host machine.

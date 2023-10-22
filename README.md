# Digital_Makeup_Generation

### Steps(Target for now):
1. Find the face landmarks using `face_recognition` library.
2. Warp landmarks to fit target face.
3. Interpolate for more data points
4. Otsu's method to get rid of hair

### References:
1. [face-recognition library](https://pypi.org/project/face-recognition/)
2. [face-recognition repo](https://github.com/ageitgey/face_recognition)
3. [Face-Morphing](https://learnopencv.com/face-morph-using-opencv-cpp-python/)
# Things to know about Haskell OpenCV
...from my own beginners perspective and experience.
Mat = image

# Contributing to a function tutorial. (HighGUI | imshow)
1. Find the C++ implementation/docs of said function.
imshow - Displays an image in the specified window.
```c++
void cv::imshow (const String & winname, InputArray mat)
```
1.1. Make note of the types and their description
i.e.
const String &winname: name of the window
mat: image to be shown




# Object-Detection-in-Images
Computer science mini project submitted in satisfaction of my third year at Department of Technology, Shivaji University, Kolhapur.

The program takes in an image file as input and detects most objects from it by drawing a bounding box around the respective object. It also prints the detected name of that object above the box. The accuracy of the recognition depends on the size of the object and clarity of the image. Generally, the larger the size of the bounding box surrounding the object, the more accurate the recognition will be. It also displays a table listing all the objects that it has managed to detect and the percentage probability of their accuracy.

![Main window](https://github.com/ShantanuBalse/Object-Detection-in-Images/blob/master/Screenshots/Capture.PNG)

![Before](https://github.com/ShantanuBalse/Object-Detection-in-Images/blob/master/Screenshots/before.jpg)
![After](https://github.com/ShantanuBalse/Object-Detection-in-Images/blob/master/Screenshots/after.jpg)
![table](https://github.com/ShantanuBalse/Object-Detection-in-Images/blob/master/Screenshots/table.PNG)


### Dependencies

```
pip install opencv-python
pip install appJar
pip install tensorflow
pip install numpy
pip install scipy
pip install pillow
pip install matplotlib
pip install h5py
pip install keras
pip install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.2/imageai-2.0.2-py3-none-any.whl
```

### Execution

Once you have all the dependencies installed, simply run ```build.bat``` to execute the program.

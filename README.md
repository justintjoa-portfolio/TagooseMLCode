# Machine-Learning-End

Hey Guys! So to run this code make sure you do this FIRST:

If you are a **WINDOWS** user, you might need to reinstall the latest version of Python found here: https://www.python.org/downloads/release/python-377/  
> When you install, MAKE SURE that you CHECK A BOX right at the beginning of the installation: `"Add Python 3.7 to PATH"`. This will allow you to do `pip` installs like everyone else.


Then **everyone** should type these commands into their terminal:  
> `pip install tensorflow==1.13.1` 
`pip install opencv-python`  
`pip install keras`  
`pip install imageai --upgrade`  


These might take awhile to download onto your computer.  
Also, click on the link below to download the RetinaNet model file that will be used for object detection:  
https://github.com/OlafenwaMoses/ImageAI/releases/download/1.0/resnet50_coco_best_v2.0.1.h5

## Note  
- Image file must be called `image.jpg`
- Downgrades version of Tensorflow because `get_session` is not available when using TensorFlow 2.0

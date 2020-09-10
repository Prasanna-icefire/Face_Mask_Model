# Face_Mask_Model

The trained model is available in the given link below.
https://www.dropbox.com/s/9cd7bzo0otdt8ts/FaceMask.weights?dl=0

First you need to set up your darknet directory, compile and such. Use this person's github readme to compile stuff:
https://github.com/AlexeyAB/darknet

Having commpiled and having your installation set up,download this model and paste it into the DetectExecute directory. 
In the obj.data file present in the DetectExecute directory, modify the path and set to whatever you have named your system and whereever you  have stored this project.

Having done this successfully, execute : ./darknet detector demo ./DetectExecute/obj.data ./DetectExecute/yolo-obj.cfg ./DetectExecute/FaceMask.weights -c 0 
from the darknet directory where you initially compiled using AlexerAB's steps.
Your detections must execute well. Happy Coding.

Do check my linkedin profile: https://www.linkedin.com/in/prasanna-mg-456bb0b8/


![](https://raw.githubusercontent.com/Prasanna-icefire/Face_Mask_Model/master/Screenshot%20from%202020-09-10%2023-59-42.png)


![](https://raw.githubusercontent.com/Prasanna-icefire/Face_Mask_Model/master/Screenshot%20from%202020-09-10%2023-59-57.png)


![](https://raw.githubusercontent.com/Prasanna-icefire/Face_Mask_Model/master/Screenshot%20from%202020-09-10%2023-59-51.png)

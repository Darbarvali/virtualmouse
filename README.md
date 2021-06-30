# virtualmouse

The present project relates to a virtual mouse that helps people if their mouse is not working in emergence  by forming a fingertip detection area on the front of the operator with the camera, detecting the operator's fingertips moving in the area, and converting it into two- dimensional position information. It transmits to the computer to control the position of the computer cursor, analyzes the trajectory of the fingertip position to reset the mouse area in the fingertip detection area, or extracts and transfers the operator's click information, it allows the operator to perform the same operation as using a mouse by moving the hand freely within the fingertip detection area. So, that the operator does not hold the mouse in his hand. It is about a virtual mouse system that enables the convenient and intuitive performance of input actions and that the operator gives. The present invention replaces a mouse to control a product adopting a display and cursor system such as the computer, TV, etc.

##Working process##
Here is a flow chart explaining the python code in this open CV project for AI-Based Mouse Application. Let's check the code to see AI-Based Mouse functionality. It checks whether the angle between the fingers is less than 20 degrees or not if it is True then scrolling functionality works otherwise it verifies the next condition that is if the angle between two fingers is less than 60 degrees or not if it is true Left-click works otherwise Right-click. Same conditions are applied for every moment in our fingers and the loop iterates if it satisfies the mentioned conditions else breaks out from the loop.


![image](https://user-images.githubusercontent.com/84654043/123919858-00212180-d9a3-11eb-82f9-1851d1bd816b.png)

##Drawings##

 ![image](https://user-images.githubusercontent.com/84654043/123919991-22b33a80-d9a3-11eb-8589-226a68f34fbc.png)
![image](https://user-images.githubusercontent.com/84654043/123920036-29da4880-d9a3-11eb-919d-415cb676ad40.png)


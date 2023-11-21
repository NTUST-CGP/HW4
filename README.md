## **User manual**
---
### Controls
#### Run
* Press `Run` to run / stop the train
* Press `ArcLength` to use / unuse Arc Length Parameterization
* Scroll `speed` to change the run speed of train
* Choose `Linear`/`Cardinal Cubic`/`Cubic B-Spline` in Spline Type groupbox to switch the track mode
* Scroll `scale` in Cardinal Cubic mode to change the tension of curve
#### View
* Hold down `right button of mouse` to move the camera view
* Press `WASD` to move the camera position
* Scroll the mouse wheel to zoom in / out.
* Press `World`/`Train`/`Top` to switch camera view to world / train / top view
#### Control point
* Hold down `left button of mouse` on control point to move control point in x-axis and z-axis
* Hold down `left button of mouse` + `ctrl` on control point to move control point in y-axis
* Press 'Add Point' / 'Delete Point' to add / delete control point
* Press `R+X`/`R-X`/`R+Z`/`R-Z` to rotate control point
* Press `Reset` to reset control point
#### Lighting
* Press `Light On` to close / open the sunlight

## **Technology**
---
### **TrainView**
    Set eye transform to position of train plus offset.
![image](https://hackmd.io/_uploads/B1DRN75Np.png)
### **Track**
*     cardinal
    *     tension
*     b-spline
*     linear
*     parallel rails
*     rail ties
*     arc length parameterization
### **Train**
*     speed
*     orientation
*     
### **Load Model**
1.     Use assimp library to read *.obj file.
2.     
### **Lighting**


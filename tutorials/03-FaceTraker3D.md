# See me mom I am a painting

## 1) Find Resources.

### - Search for the rigth inspiration for your filters, let you imagination fly

## 2) Open Spark AR and create a new project.

### - Once we open the Spark AR program, we will select ```New Project```

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_1.jpg?raw=true" width="50%">
</p>

## 3) Add a Face Tracker

### - The first thing we need is a new object, so we're goign to click in ```Add object```

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_2.jpg?raw=true" width="50%">
</p>

### - We need a canvas, and inside the canvas 2 rectangles

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_3.jpg?raw=true" width="50%">
</p>

### - We will change the name of the rectangles to ```user``` and ```bg```, also make sure that on the material you have selected the 3D object.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_5.jpg?raw=true" width="50%">
</p>

### - On this same properties, make sure you have the ```visible``` option checked and the ```position``` in ```Fill Height```

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_7.jpg?raw=true" width="50%">
</p>

### - Now we'll go to the camera, once selected, we can change its properties.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_8.jpg?raw=true" width="50%">
</p>

### - In ```texture``` we'll choose ```cameraTexture0``` and in ```Segmentation``` => ```Person```

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_9.jpg?raw=true" width="50%">
</p>

### - For the rectangle ``user``, we'll add a new ``material``. Called it ``user`` and change its properties: 
- ``Shader Type`` => ``Flat``
- ``STexture`` => ``CameraTexture0``
- ``Alpha`` => Checked

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_10.jpg?raw=true" width="50%">
</p>

### - Once we have the ``Alpha`` option selected, we choose the texture we want, in this case we'll select ``personSegmentationMaskTexture0``

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_11.jpg?raw=true" width="50%">
</p>

### - The screen has to look like this.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_12.jpg?raw=true" width="50%">
</p>

### - Now its the turn of the other rectangle, we'll add a brand new material

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_13.jpg?raw=true" width="50%">
</p>

### - For this material we new a new texture. We'll selected now the background we want.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_14.jpg?raw=true" width="50%">
</p>

### - Once done this, we can see the background of our painting. 

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_15.jpg?raw=true" width="50%">
</p>

## 4) Add the 3d elemets inside the facetracker

### - The next thing is to add the ``Face Tracker`` for our filter.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_16.jpg?raw=true" width="50%">
</p>

### - This is the fun part, we will start adding our assets.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_17.jpg?raw=true" width="50%">
</p>

### - We select ``import from computer``

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_18.jpg?raw=true" width="50%">
</p>

### - For this we had prepared our own assets, you can do it to, or just use the ones we are using to.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_19.jpg?raw=true" width="50%">
</p>

### - On the files we just upload, there is this one that contains the head of our mask.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_20.jpg?raw=true" width="50%">
</p>

### - We need to drag it to our ``Face Tracker`` so we can use it.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_21.jpg?raw=true" width="50%">
</p>

### - We repeat this same process for the hat.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_22.jpg?raw=true" width="50%">
</p>

### - Now we have a head with a little hat

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_23.jpg?raw=true" width="50%">
</p>

### - And once again, but now with the apple

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_24.jpg?raw=true" width="50%">
</p>

## 5) Fix the 3d Elements

### - We'll move the apple and all of the other elements to the place we want, you can do this with the selection tool on the top of the screen.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_25.jpg?raw=true" width="50%">
</p>

## 6) Prepare and Testing

### - We have now all the assets we need, we just have to change their colors, for that we need to change the ``Blend Mode`` => ``Replace`` and the ``Opacity`` => 100%

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_26.jpg?raw=true" width="50%">
 </p>

### - In the upper section we can change the color of the elements.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_27.jpg?raw=true" width="50%">
</p>

### - An it's done, the only thing left to do is to test it and send it to revision.

<p align="center">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_28.jpg?raw=true" width="50%">
</p>












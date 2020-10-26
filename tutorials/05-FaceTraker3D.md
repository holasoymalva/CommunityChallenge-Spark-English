# See me mom I am a painting

## 1) Find Resources.

### - Search for the rigth inspiration for your filters, let you imagination fly

## 2) Open Spark AR and create a new project.

### - Once we open the Spark AR program, we will select ```New Project```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_1.jpg?raw=true" width="50%">

## 3) Add a Face Tracker

### - The first thing we need is a new object, so we're goign to click in ```Add object```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_2.jpg?raw=true" width="50%">

### - We need a canvas, and inside the canvas 2 rectangles

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_3.jpg?raw=true" width="50%">

### - We will change the name of the rectangles to ```user``` and ```bg```, also make sure that on the material you have selected the 3D object.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_5.jpg?raw=true" width="50%">

### - On this same properties, make sure you have the ```visible``` option checked and the ```position``` in ```Fill Height```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker3D_7.jpg?raw=true" width="50%">

### - Now we'll go to the camera, once selected, we can change its properties.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_8.jpg?raw=true" width="50%">

### - In ```texture``` we'll choose ```cameraTexture0``` and in ```Segmentation``` => ```Person```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_9.jpg?raw=true" width="50%">

### - For the rectangle ``user``, we'll add a new ``material``. Called it ``user`` and change its properties: 
- ``Shader Type`` => ``Flat``
- ``STexture`` => ``CameraTexture0``
- ``Alpha`` => Checked

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_10.jpg?raw=true" width="50%">

### - Once we have the ``Alpha`` option selected, we choose the texture we want, in this case we'll select ``personSegmentationMaskTexture0``

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_11.jpg?raw=true" width="50%">

### - The screen has to look like this.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_12.jpg?raw=true" width="50%">

### - Now its the turn of the other rectangle, we'll add a brand new material

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_13.jpg?raw=true" width="50%">

### - For this material we new a new texture. We'll selected now the background we want.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_14.jpg?raw=true" width="50%">

### - The next thing is to add the ``Face Tracker`` for our filter.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_15.jpg?raw=true" width="50%">

### - This is the fun part, we will start adding our assets.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_16.jpg?raw=true" width="50%">

### - We select ``import from computer``

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_17.jpg?raw=true" width="50%">

### - For this we had prepared our own assets, you can do it to, or just use the ones we are using to.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_18.jpg?raw=true" width="50%">

### - On the files we just upload, there is this one that contains the head of our mask.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_19.jpg?raw=true" width="50%">

### - We need to drag it to our ``Face Tracker`` so we can use it.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_20.jpg?raw=true" width="50%">

### - We repeat this same process for the hat.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_21.jpg?raw=true" width="50%">

### - Now we have a head with a little hat

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_22.jpg?raw=true" width="50%">

### - And once again, but now with the apple

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_23.jpg?raw=true" width="50%">

### - We'll move the apple to the front of all the other ones, you can do this with the selection tool on the top of the screen.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_24.jpg?raw=true" width="50%">

### - We have now all the assets we need, we just have to change their colors, for that we need to change the ``Blend Mode`` => ``Replace`` and the ``Opacity`` => 100%

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_25.jpg?raw=true" width="50%">




<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_26.jpg?raw=true" width="50%">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_27.jpg?raw=true" width="50%">
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark-English/blob/main/tutorials/03-source/FaceTracker_28.jpg?raw=true" width="50%">






## 4) Add the 3d elemets inside the facetracker

## 5) Fix the 3d Elements

## 6) Prepare and Testing


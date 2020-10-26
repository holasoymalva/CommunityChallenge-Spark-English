# Make your first VanGogh Filter <img src="https://www.enlinealasalle.com/pluginfile.php/8983/course/overviewfiles/vincent-van-gogh-png-2.png" height="25">

# Make the Background

### - The first thing we need to do, is to open Spark AR and create a new project.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/01.png?raw=true" width="50%">

### - Once the interface loads, we'll click on the option "Add Object"

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/03.png?raw=true" width="50%">

### - We need to search for the "canvas" option and click it. A canvas is a layer where we can add other elements, this elements can be either dynamic or static.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/04.png?raw=true" width="50%">

### - Once we add this to our canvas, we select again the option "Add object" and we add a rectangle

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/05.png?raw=true" width="50%">

### - Now we can see the rectangle on the canvas.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/06.png?raw=true" width="50%">

### - We need to add another rectangle, the first one is for the user and second one is for the background

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/07.png?raw=true" width="50%">

### - Once we change the names of the rectangle to ```user``` and ```bg```, we can procced to edit them.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/08.png?raw=true" width="50%">

### - If we select the rectangle, we can edit its properties on the right side.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/09.png?raw=true" width="50%">

### - We need to change its width and heigth to 100%. This ensure us to cover the hole screen and not to leave any blank space on the filter

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/10.png?raw=true" width="50%">

### - Once you have the properties like us, we now have to add a material the user rectangle. We click on the plus sign on the material section.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/11.png?raw=true" width="50%">

### - Let's change the name of the material to ```user ```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/12.png?raw=true" width="50%">

# Add Camera Textures and Segmentation

### - On top of the rectangles, there is the camera section. We need to click it because we now need to add the texture and segmentation.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/13.png?raw=true" width="50%">

### - On the rigth side we can find the properties of the camera. 

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/14.png?raw=true" width="50%">

### - We're going to click on ```Texture Extraction``` and select ```cameraTexture0```, next in Segmentation we're going to select the ```personSegmentationMaskTexture0```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/15.png?raw=true" width="50%">

# Preview our Vangogh BG

### - Now on the properties for the material on ```Shader Type``` we select ```Flat```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/16.png?raw=true" width="50%">

### - On ```Texture``` we select ```cameraTexture0```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/17.png?raw=true" width="50%">

### - Once we've done that, on ```Alpha``` we cross the checkbox. 

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/18.png?raw=true" width="50%">

### - In ```Texture``` we choose ```personSegmentationMaskTexture0```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/19.png?raw=true" width="50%">

### - We need to add the user canvas in another layer, this because we want them to be separated, the user from the background.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/20.png?raw=true" width="50%">

### - If you have done everything so far acording to the tutorial, you will see something like these. We have our user separated from the background on different layers.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/21.png?raw=true" width="50%">

### - We now need a material for our background.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/22.png?raw=true" width="50%">

### - Let's change its name to ```bg```.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/23.png?raw=true" width="50%">

### - The background needs a new texture, now is time to select the image we had for our background and add it to the project.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/24.png?raw=true" width="50%">

### - As you can see, now we have our background done. The very next thing is to make the crown.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/25.png?raw=true" width="50%">

# Make the Crown

### - The first thing you need to do to make the crown, is to add a ```Face Tracker``` located on ```Add Object```.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/26.png?raw=true" width="50%">

### - And inside the ```Face Tracker```, we're going to add a new object, in this case a ```Plane```

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/27.png?raw=true" width="50%">

### - If you look closely, now we have a rectangle following the face of the person. But it's out of place, we just need to move it a little to the front.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/28.png?raw=true" width="50%">

### - Now we go to the very bottom on the ```Textures``` section, and add all the images for our crown.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/29.png?raw=true" width="50%">

### - In this case we added 3 images, they have to be at the same level of the other textures.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/30.png?raw=true" width="50%">

### - For every image you add, you need to add at least one ```Plane``` on the ```Face Tracker```, in each plane there's going to be one image, but you can have as many planes you want, if you want to repeat the same image over and over again.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/31.png?raw=true" width="50%">

### - Now on the upper section, there's an icon with four arrows, once we select this icon, we can move all the planes we've create.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/32.png?raw=true" width="50%">

### - Once we've placed all the planes, we add them the materials.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/33.png?raw=true" width="50%">

### - Let's call them the same as the files.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/34.png?raw=true" width="50%">

### - Now we choose the texture, that is going to be the image we have.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/35.png?raw=true" width="50%">

### - What happened here, is that this plane is at the back of the others.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/36.png?raw=true" width="50%">

### - You just need to rearrange them as you seem fit.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/37.png?raw=true" width="50%">

# Make details

### - If you don't want your filter to look like this, we can fix it.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/38.png?raw=true" width="50%">

### - Create a new layer.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/39.png?raw=true" width="50%">

### -  And add more images to this layer.

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/40.png?raw=true" width="50%">

 ### - Then move it to the sides of the face, so it can look more natural.
 
<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/41.png?raw=true" width="50%">


# The Result

<img src="https://github.com/L3ts-H4ck/CommunityChallenge-Spark/blob/master/tutorials/03-source/42.png?raw=true" width="50%">

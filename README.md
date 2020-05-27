# CMPM163Labs
## Lab2: https://drive.google.com/file/d/1UYj_EKKP0A_NvElDIGpYD4HpztFmEBZH/view?usp=sharing
## Lab3: https://drive.google.com/file/d/15cITrWVt6_4IxNS_Orm8ayePJYI_XAdb/view?usp=sharing
![](images/theScene.png)
Lab3 Writeup:
From left to right: 
Wireframe cube was made by creating a cube with MeshNormalMaterial and setting the wireframe variable to true.
Middle top cube was created by interpolating on a different axis than the example and used different colors. 
Center cube is just the example cube shown to us. 
Rightmost cube is just the example cube shown to us.

## Lab4: https://drive.google.com/file/d/11JUkv7FZLIFr_n9JUMFYYmusCmMCFDfq/view?usp=sharing 

Question Answers
a. x = 7u
b. y = 7 - 7v
c. Grey

How I Made the Cubes
Starting from left to right, I simply followed the instructions for the first and second cubes. 
The rightmost cube simply was changing the textures and adding a different normal map. 
The center-top cube was created by following instructions. 
The final cube with the tiled texture was simply doing mod(vUv*2.0, 1.0).

## Lab5: https://drive.google.com/file/d/1Ud0nRmG4grfbBhSNcByay4vMBbyNZBPw/view?usp=sharing

Modifications:
Skybox - Changed it to a dark purple material. Rather simple, just went to window > rendering > light settings, and then replaced it. 
Trees - Changed the saturation on the trees so that they more accurately represent the change in colors as the day turns to night.
Track - Made the track longer by redirecting the turns so that there was an extra portion.
Environment - Added two stock buildings from the assets. 
The Sun - Changed the material in order to make it more closely resemble a full moon.
Basic wheel particles - Followed the tutorial, but then changed the material to make them yellow/gold.
Smoke particles from exhaust - Created a new particle system which inherits velocity from parent and exists in a global scope rather then local scope.
Kart speed - Simply increased the speed of the kart to make it a bit more exhilarating.

## Lab6: Part 1 (Unity)
![](images/scene.png)
![](images/screen.jpg)
![](images/brushed1.jpg)

Spotlight: Affected by both position and rotation. Lights an area in a cone with a given angle.
Directional light: Behaves like the sun. Not affected by positon. Lights all objects in a scene given the light's rotation.
Point light: Behaves like a light bulb, and not affected by rotation. Lights an area around a single point.
Area light: Only work when using baking a light map. Shines in all directions on one side of a rectangular plane.

I made the material I chose look like real-life object by using the Standard shader and making it metallic. In order to give it a brushed metal look I increased the roughness.

The first textured object uses a cobbled stone texture. 
The second textured object uses a marble texture.

The skybox is just a space skybox I found and thought was cool.

## Lab7: Part 1 (Unity) https://drive.google.com/file/d/1DfEAvmeajLB5Uw1Ua4acqYVZEXWQF_mh/view

I made this scene using both the mountain range and water and adjusting some properties for each. Then, I simply added more 3D objects to the scene until I got the look I desired, creating different materials along the way.  

My partner also did part one (unity) of this lab.
He found that the most challenging part of this tutorial was being able to properly adjust the nodes to get the effect he wanted. 
The most interesting part for him was being able to use a noise map to make realistic terrain.

Note: We didn't help each other for this lab.

## Lab8: Part 1 (Unity) 
![](images/cityTut.png)
![](images/walled.png)
![](images/kowloon.jpg)

My inspiration for this project was a city so crowded that it seemed as if it was all one big apartment complex. The changes it inspired were simple, just create an extra loop in which the buildings would be built upwards. 

My partner created a rural village. I really liked how the landscape generated felt as if one was looking at the countryside.
My partner taught me that you can combine different scales of objects to crete interesting combinations.

Note: We didn't help each other for this lab.

# CS4331 - Project 1 - Atharva Raibagi

## Introduction

This is my Virtual Reality Project 1. It is based on creating a human scale scene from the 'inside out' on how COVID-19 has affected us in different ways. 

### Pre-COVID Scene
When the project is first opened up, you will be first taken to the Pre-COVID scene. Here you will be in a classroom where students go to class and attend lectures before lockdown and COVID 19. There are a couple interactive elements in this scene.
You can click on the Double T object to make it rotate.
You can click on the Masked rider to play sound.

### Post- COVID Scene
In order to go to the Post-Covid scene, you'll have to click on the door in the first scene. You will then be transported to the Post-COVID scene where you will be able to see the layot of a bedroom and this scene explains how students now have to attend classes online from their home. The interactive element in this scene is the ceiling fan. You can click on the fan to start its rotation. 

![alt text](https://media.giphy.com/media/gTW8hUBnLn02KTCsLb/giphy.gif)

You can watch the video demo here: https://youtu.be/5HSOVfgWBls



## Interactions/Animations

**Change of Scene**
In order to change the scene when the door is clicked, I had to write a custom model to handle on click navigation.

![alt text](https://github.com/atharvaraibagi/atharvaraibagi.github.io/blob/master/images/customFunction.png)



**Pre COVID Scene:**

![alt text](https://github.com/atharvaraibagi/atharvaraibagi.github.io/blob/master/images/precov.png)

**Post COVID Scene:**

![alt text](https://github.com/atharvaraibagi/atharvaraibagi.github.io/blob/master/images/postcov.png)



**Rotating the Double T**

![alt text](https://github.com/atharvaraibagi/atharvaraibagi.github.io/blob/master/images/t.png)


To rotate the Double T object, I added a onclick event handler to start animation when the object is clicked

![alt text](https://github.com/atharvaraibagi/atharvaraibagi.github.io/blob/master/images/onclick.png)

**Masked Rider Sound**
*This sound was downloaded from: Zapsplat.com*

To add the sound, I again added an onclick event and played the sound when the object was clicked

![alt text](https://github.com/atharvaraibagi/atharvaraibagi.github.io/blob/master/images/onclicksound.png)


## Libraries Used
Aframe : https://aframe.io/
         https://aframe.io/releases/1.0.4/aframe.min.js


## Sources

**Models**

[Door](https://free3d.com/3d-model/interior-door-66723.html)

[Bed](https://free3d.com/3d-model/full-size-bed-with-white-sheets-black-v1--434476.html)

[Lamp](https://free3d.com/3d-model/older-lamp-28459.html)

[BedsideDraswer](https://free3d.com/3d-model/drawer-bed-side-547686.html)

[Desk](https://free3d.com/3d-model/computer-table-86952.html)

[Backpack](https://free3d.com/3d-model/backpack-v2--607100.html)

[Book](https://free3d.com/3d-model/books-pencil-lapis-e-livros-52285.html)

**Sound**

Masked Rider Sound: from Zapsplat.com
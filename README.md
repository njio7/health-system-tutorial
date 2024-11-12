# Health system tutorial


To start,

-

-

-

-
# Make sure to save occasionally!

After this, you will want to create a plane, a cube and two more cubes beside the main player.

You can place them wherever you want but i have set mine up like this. 

![image](https://github.com/user-attachments/assets/7628e451-2bfd-4b56-bffa-0fb30fb82d1c)

To make things visually clearer, we can create a new material and then assign a new colour to our cubes. 

For my example, i will be using green and red cubes to make it clear whhich cube will give our player health and which cube with remove health from the player.

![image](https://github.com/user-attachments/assets/5cfeba50-ba02-49b9-9ba3-94f50797b159)
![image](https://github.com/user-attachments/assets/a90f69dc-f47d-440d-b39b-48781c62f2b8)

This is how my scene looks once things have been put into place.

![image](https://github.com/user-attachments/assets/c2b5ad36-2f39-4aed-89a4-f0305ed3ce04)

After creating eveything we need for our scene, we can move onto giving the player a collider that will trigger when it touches either the green or red cube.

When clicking on both the red and green cube, you will want to make sure that the "Is Trigger" box is ticked to make sure that the player cube will be able to interact with it.

![image](https://github.com/user-attachments/assets/259b4943-8ece-49ad-9dcc-17bb6a2f5276)

(This tutorial is not about learning how the player moves so i will be skipping a lot of the details of player movement.)
 
Now we can create a script called "Player" that will be using the code below to move left and right using the A/D keys or Left and Right arrow keys.


![image](https://github.com/user-attachments/assets/9eb47ae3-f2d4-44a2-a067-086aa88b528a)

You can now assing this to the player cube by draging the scriipt onto the cube or dragging it into the "Add Component" area in the inspector.
Make sure to have the cube selected otherwise you might be assigning the player movment scipt to something else.

Once you have done this, you can press play at the top of the scene to test if the cube moves left and right when you press the keyboard.


After asigning the player movment to the player cube. we can create another C# script. we can call this 






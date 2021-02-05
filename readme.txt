Name: Doaa Idris
Student Number:101118226
Date: Feb. 4th, 2021
Course: IMD3901 A
Assignment 2



For assignment 2, we had our very first try with working with webVR using aframe and
JavaScript. I do not have much experience with VR, so I thought this would be
quite interesting, while at the same time a great learning experience. The theme of
the space is a Japanese restaurant, or more specifically a sushi one. This is a special
type of sushi restaurant that serves their meals on conveyer belts, so that the items
are moving around for customers to look at and take. I have only ever seen conveyer belt 
sushi on TV, so I thought it would be fun to make one myself. One of my lifetime goals 
is to go to Japan, and like many others, we are currently stuck at home due to the 
pandemic. Although basic, experiences like this can help us "virtually travel" and 
visit new paces without having to get out of our houses. For the 3D assets, I mostly 
downloaded free to use ones from sketchfab, and used aframe's visual editor to help 
position items more easily. I also used some aframe components for the food's movement, 
and grabbing and moving items. In this space, users can spawn food from two choices using 
the book. The green button spawns the food, while the red button will destroy them. 
Instead of having plain buttons, I put them on a book, to create an "interactive" menu.
Additionally, when any of the two options are spawned, the background music begins to play.
On the left, there is a table with chopsticks and juice. These are the items that can be
grabbed and moved around to maybe the dining table on the right.

Since its my first time using aframe, there were some challenges that I faced
throughout. For example, making it so that it could successfully spawn the food items 
was a little challenging, especially its movement animation. At first, spawning would
occur at the wrong places, and I just could not get it to be at a position that I wanted.
To add, I wanted the food to move around the table in the middle and keep looping that
way. My first instinct was to use the animation component, however I did not find much
luck getting anything to move after the first translation. 

To solve the issue with spawning, I found a demo tutorial on aframe's website on how to 
create a mini minecart-like experience. I found this helpful, however the tutorial spawns
cubes according to where the curser is. In my case, I wanted it to start spawning at a specific
location. I then found that you can use JavaScript to change an entity's attribute. Using that
I tried to set the position of the food item when it is spawned. This is also where I add in the
movement animation. To solve the animation issue, I found a component to help with this. It uses
curves, and attached an object to it, so that it moves along the path of this curve. I found using
components to be extremely helpful, and I aim to apply these learned concepts to the final term
project as well.


Components used for this project:
Aframe environment component
Aframe curve component
Aframe alongpath component
Aframe super hands component

Platforms:
desktop and tablet

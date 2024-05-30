# Idea9103_final-coding_dzha3785
1. #### Details of your individual approach to animating the group code.
We divided the picture of Piet Mondrian 'Broadway Boogie Woogie' into 49*49 squares. I am mainly responsible for the task of filling the small grids in the group code, so I mainly use the fillGrid() method. After finishing my part, I changed background(225) to background(255). And changed the strokeWeight of the square to 0.

2. #### Which did you choose to drive your individual code: audio, interaction, Perlin noise or time.
I choose interaction to drive my individual code.

3. #### Instructions on how to interact with the work 
- Mouse pressed

Click on a rectangle: Click on any rectangle on the artwork and the color of the rectangle will change randomly. This can create a dynamic color change effect.

Steps: Move the mouse to the big rectangle whose color you want to change, click the left mouse button, and you can see the color of the rectangle change.

- Keyboard pressed

Move rectangles: Use the W, A, S, D keys on the keyboard to move the positions of all rectangles.
W key: Move the rectangle up. 
A key: Move the rectangle left. 
S key: Move the rectangle down. 
D key: Move the rectangle right.

Steps: After the page is loaded, press the above keyboard keys to see the rectangle move as a whole.

- Page loading animation:

Initial animation: When the page loads, all but the large square need to be clicked to appear.

Steps: When you refresh the page or open it for the first time, the background will appear again by clicking to complete the initial animation.

4. #### References to inspiration for animating your individual code; these can be images (still or gifs). How did they influence your submission?
The painting initially seemed to be based on lines running through it, mainly yellow (closely related to New York City I in this respect) and some connecting bands of different colors, which led to changes in direction and proportion. To this basic composition, small blocks of red, blue, gray, and sometimes the same yellow as the horizontal lines were added, giving the whole a new rhythm, a completely unexpected movement, a bouncing staccato rhythm. So I changed the movement and color of the blocks through keyboard and mouse to better match the meaning of the painting itself.

5. #### Which properties of the image will be animated and how？
- Color change:  In the mousePressed function, when the user clicks a rectangle, color(random(255), random(255), random(255)) is called to generate a random color and apply it to the clicked rectangle. 
- Position movement:  In the keyPressed function, when the user presses the a, d, w, s keys, the moveRectangles function is called to move the positions of all rectangles.
- The transparency changes, and when the page is reloaded, the full image is displayed by clicking on the large square that appears on the page.

6. ##### I didn't make a lot of changes to the group code, I just changed the order of the group code a bit to make the animation run better.
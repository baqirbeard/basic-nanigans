One of the more useful programs I've made. Lets you draw rectangles easily and quickly. Some of my projects may require this program as it is quite useful, although I may merge it into a big "shapes" program at some point

Here's a brief tutorial on how to use it. The actual syntax is identical to just drawing a line using TI-BASIC, which looks like:

``Line(X1,X2,Y1,Y2[,erase,colour,linestyle]``

**HOWEVER!** TI-BASIC does NOT have functions. So instead, if we want to draw a blue rectangle from (0,0) to (5,7) with this program, we have to put it in a list first. I have coded this program to take input from the list A, which does not exist until we declare it like:

``{0,0,5,5,1,BLUE,1}→A``

After we declare the list lA, we can run the program. and ta-da! A rectangle has appeared!

By the way, in terms of syntax, this program does not draw rectangles with shadows as seen when you set the ``linestyle`` value to either ``3`` or ``4``. Instead, I have repurposed it as a fill tool for drawing filled in rectangles.

:)

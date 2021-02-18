## A New Post

Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.

During class we worked on using LOGO 2 to create random directions for a line to follow, using LOGO reminded me of using command lines in a terminal last semester, which I enjoyed a lot. Although I didn’t get far in using LOGO I would’ve liked to create some more colorful rhythmic patterns using the program. I found it interesting in the program how the line would continue off screen and back on again on another spot, instead of the screen zooming outwards to fit the action. In my creation of the algorithmic walk, I tried to make the steps as simple as possible sort of mirroring how LOGO works but in real life. Coming up with rules for the walk was an interesting process, as I was making the rules for the “units” part, or how long forward units would be. It led me to use smaller numbers in the forward function, when creating the 20 lines of direction: 

![Screen Shot 2021-02-04 at 4.53.25 PM.png]({{site.baseurl}}/Screen Shot 2021-02-04 at 4.53.25 PM.png)

![Screen Shot 2021-02-04 at 4.50.04 PM.png]({{site.baseurl}}/Screen Shot 2021-02-04 at 4.50.04 PM.png)

![Screen Shot 2021-02-04 at 4.49.05 PM.png]({{site.baseurl}}/Screen Shot 2021-02-04 at 4.49.05 PM.png)

LEFT 2 
FORWARD 2
RANDOM 1 
FORWARD 1 
RIGHT 1
LEFT 1
FORWARD 3 
FORWARD 2 
BACK 1 
LEFT 1 
RIGHT 1 
FORWARD 2 
LEFT 1 
BACK 3 
RANDOM 1 
FORWARD 1 
LEFT 1 
FORWARD 3
RIGHT 1 
BACK 3 

The rules that i used for the directions were as follows: 
  
LEFT/RIGHT 1 = turn left once 
LEFT/RIGHT 2(or more) = turn left on the nearest street, and turn left again on the next nearest street, before following the next direction.  
FORWARD/BACK 1 = Go forward until you reach a street you could turn on, then follow next direction.
RANDOM 1 = If there is a car passing turn left, if there isnt turn right. (There are a lot of cars passing near where I live)

My Route took me through what for the most part would be a normal neighborhood walk, with the exception of going dowm a busier road in the beginning and ending. The forward function on my makeshiftcode cannot always be fully functional, especially in the case of there being no other option but turning left or right first. In this situation, I would just go straight to the next direction. If I were to improve on this I would make the amount for the “unit” shorter, and add other random rules to make it more realistic and more interesting along the way. The forward function that I created would find better use in an urban area, rather than where I live where the streets are really long. 

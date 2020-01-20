# maths_project

### Work done on the first commit: 

After seeing the code doing the rotation, I had the idea to create 3 axis, one that goes in x, 
another on y and another on z. After that I implemented the keys conditions for each movement. 
I decided to group them to be much more easier to read. I used the code in place to make it rotate.
For the zoom in and out, I just changed the object location depending of the input.
Didn't had much problems on this one.

### Work done on the second commit: 

Firstly I tried to find where the code of the cube is made. In the line of 31 of sample, 
I found that this was the parametres that make the cube and that mesh is the code that makes it. 
I found out that the Mesh.create_square are the one making every faces of the cube. One mesh = one face.
To make my tetrahedron (4 faces object), I just had to draw three faces, because the last one is "invisble" to the user.
I then removed one of the poly append to just draw 3 lines and not four.
I had some trouble to understand the vectors in the Mesh.create_squares so I asked for assistance for that to make the form of it.

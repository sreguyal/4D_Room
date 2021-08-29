# 4D Room
You have been transported to a world with four spatial dimensions! Unfortunately, you are stuck inside a room with no exit. To pass the time, might as well practice seeing the fourth dimension.

## Introduction

### What is the Fourth Spatial Dimension? 
So, for those who are wondering how we can physically understand the fourth dimension, let's quickly go through the lower dimensions.

The 0<sup>th</sup> dimension is a point. Move in any direction and we get to the 1<sup>st</sup> dimension, a line.

While we are in the 1<sup>st</sup> dimension, we can move back and forth across the line. But we want more excitement in life, so we move away from the line. We have reached the 2<sup>nd</sup> dimension. You can imagine this as an infinite flat sheet of paper.

Finally, to get to the 3<sup>rd</sup> dimension, aka the dimension humans live in, we jump up off the 2D plane.

Now, by analogy, to get to the 4<sup>th</sup> dimension, we need to move in a direction we have not moved in yet. If we could just "jump" in a new direction, we would enter the 4<sup>th</sup> dimension. If that sounds unimaginable... well, for us 3D humans, it is (unless you happen to be Fields Medalist Bill Thurston, [apparently](https://www.quora.com/What-is-a-visual-mathematician)). We are stuck in 3D space, after all. And to cap that short summary, here is a picture of a tesseract -- the 4D equivalent of a cube!

<img src="https://user-images.githubusercontent.com/60443351/131231581-e37f6300-1afb-47f9-a82d-e42ba5e4dff1.png" alt="Tesseract Schlegel Wireframe" width="200"/>


### What is 4D Room?
You may have already seen the popular visualization of the fourth spatial dimension known as 4D Toys. To see a game demo and a video explanation of what the fourth spatial dimension is, check out [this excellent video](https://www.youtube.com/watch?v=0t4aKJuKP0Q) posted by the creator of 4D Toys.

So, how is 4D Room different? 4D Toys allows you to see the _intersection_ of a 4D object with 3D space. 4D Room aims to show the _projection_ of a 4D object into 3D space. To make the difference clearer, here is a picture showing the intersection and the projection of a 3D cube in a 2D plane.



As you can see, the projection gives much more understanding of what the two-dimensional drawing of the cube actually represents. In particular, the projection uses certain tricks to give a sense of depth in an additional dimension.

We begin with representing the shapes mathematically in 4D, calculate the rotations of these shapes, and then display their projections into lower dimensions that are understandable for humans. 



## In the 4D Room

### Regular 4D Shapes
Currently, we've created visualizations of all six convex regular 4-polytopes -- the four-dimensional equivalent of the platonic solids -- under simple rotations in 2D. Put simply, we have all six "standard" 4D shapes projected into 2D, so you can view them on your computing device screen. 

Also, note that when we rotate a 4D object, we have to rotate about a plane, such as the XY-plane or the YW-plane (W is the 4<sup>th</sup> dimension. For more on that, refer to the end of this section. And now, without further ado, here are the visuals created using `pygame` in our Jupyter Notebook!

The six convex regular 4-polytopes are: 

**The tesseract** / 8-cell. It is the 4D equivalent of the cube. 


![tesseract1simplerot mp4](https://user-images.githubusercontent.com/60443351/131235041-833d1428-2990-437a-b920-1e7297d26381.gif)
 
We start with this polytope because it is perhaps the most comprehensible out of a set of quite incomprehensible figures. The tesseract hypersurface is bounded by 8 cubical cells, and in total the shape has 24 faces, 32 edges, and 16 vertices. This first gif depicts one simple rotation about the XY-plane. Although it is "about" a plane, in the same way that the earth rotates about its axis, within 3D space the rotation about a plane is only comprehensible as a rotation about an axis.
  

![tesseract2simplerot](https://user-images.githubusercontent.com/60443351/131235273-21a59ce0-9d0b-405d-87ee-e3d92d82a40b.gif)

 This gif depicts the application of two simple rotations about the XY-plane and YW-plane.


**4-simplex** / 5-cell. It is the 4D equivalent of the tetrahedron.

![5cell2simplerot](https://user-images.githubusercontent.com/60443351/131237875-bbb2ceeb-9463-4b8d-ba9d-9834c3406f84.gif)


**16-cell**. It is the 4D equivalent of the octahedron.

![16cell3simplerot](https://user-images.githubusercontent.com/60443351/131237889-ca2ad42a-0f56-428a-8369-9a1d039b680a.gif)


**24-cell**. It has no equivalent in either a lower or higher dimension!

![24cell](https://user-images.githubusercontent.com/60443351/131238336-c0dd8d0b-3502-43a4-8d89-c86c0cda8f86.gif)


**120-cell**. It is made of 120 dodecahedral cells bounding the hypersurface, giving a grand total of 720 faces, 1,200 edges, and 600 vertices.

![120cell2simplerot](https://user-images.githubusercontent.com/60443351/131238361-0f34faba-dc7d-447b-9c00-2769f4f802cb.gif)


**600-cell**. It is made of 600 tetrahedral cells bounding the hypersurface, producing 1,200 faces, 720 edges, and 120 vertices.

![600cell2simplerot](https://user-images.githubusercontent.com/60443351/131238369-0186ac83-c98d-49da-8c55-0960cd06ab49.gif)


**More on Rotations in 4D**

Rotation of 4D objects is done about a plane, or a 2D sheet. This can be understood by analogy by recalling that a polygon constrained to the 2D plane can only rotate about a point (0D), and a solid constrained to 3D space can only rotate about a line (1D). We can see that in order to rotate an object, it needs a pivot that is two dimensions lower. Following that logic, a 4D object will have to rotate about a 2D sheet. As the object rotates in 4D space, the 2D plane of rotation remains fixed.



### Next Steps!

Our main end goal is to look at and interact with these 4D shapes in a VR environment. Being able to walk around these objects and interact with them in 3D VR space, rather than looking at them on a 2D computer screen, would be a significant increase in the amount of visual information from these 4D shapes we are able to retain. Because any time you project an object to a lower dimension, you lose some information. 

Maybe after this work is done, our 3D brains will be more capable of understanding the fourth dimension! So stay tuned!

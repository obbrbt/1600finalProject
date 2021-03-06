# Step Three: Creating an SVG Image



Alright, so now that we’ve discussed how to set up a basic **HTML** document, let’s begin talking about how to create an **SVG** image. *W3schools* has a more in-depth tutorial on how to create an **SVG** image [here](https://www.w3schools.com/graphics/svg_intro.asp). This tutorial will just explain the basics of starting an **SVG** image. The next tutorial will teach you how to make a specific image.

The first step to creating an **SVG** image is to define your **&lt;svg>&lt;/svg>** tags. These tags go inside your **&lt;body>&lt;/body>** tags. Add some space between the tags.

![svgTags](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/17.PNG)



After defining your **&lt;svg>&lt;/svg>** tags, you now need to define a height and width to the image. But first, let's discuss how an **SVG** image is mapped out.

To help visualize, think of your **HTML** document as a big graph. Each point on the graph is defined by an x- and y-coordinate. Each point corresponds to a pixel's position. 

For example, if you want your image to be 100x100 pixels, imagine a graph that is 100x100 points large. By visualizing your **HTML** document as a graph, you can gain a better understanding of how to draw your image with **SVG**.

To define an image to be 100x100 pixels wide, write height=”100” width=”100” in your **&lt;svg>** open tag like this:

![100by100](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/18.PNG)

Height and width are **attributes** of your **&lt;svg>** tag. Attributes are written as **name=""**. Whatever goes inside of the quotation marks is known as a **value**. The number *100* is the value of both the height and width of this particular **SVG** image.

The next step is to decide on what kind of image you want to create.

For a polygonal shape, I recommend using *[Desmos](https://www.desmos.com/calculator)* to place points on a graph, so you can define the points you need to create for your desired image. You can create a point with *Desmos* by typing a point like this: 

![desmos](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/19.PNG)

**Note**: *Because of the way **SVG** works, when you add points to* Desmos *they will appear flipped. If you want to view your image as it would be displayed by your browser, make all of your y-values negative.*

For a more simple image, you can use **SVG**’s predefined shapes, such as circles, rectangles and ellipses. Each of these shapes has its own defined properties, so be sure to check *[W3schools](https://www.w3schools.com/graphics/svg_intro.asp)* for which properties you need for each shape.

To create a polygon **SVG** image, you need to define a polygon.

A polygon is defined with the **&lt;polygon>&lt;/polygon>** tags. Place your **&lt;polygon>** tags inside of your **&lt;svg>&lt;/svg>** tags. 

![polygonTags](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/20.PNG)

The shape of your polygon will be set with the “points” attribute. “Points” are coordinate values on a graph. To define attributes of a polygon, you place them in the opening **&lt;polygon>** tag, just like how you added a height and width to your **&lt;svg>** tag.

![polygonPoints](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/21.PNG)

The points of the polygon are defined as: points=”x1,y1 x2,y2 x3,y3”. When you place a coordinate in the points attribute, separate the x- and y-coordinates with a comma and then use a space between coordinates.

Each of these points will be placed on a graph and lines will be drawn between them to create an image.



#### Example

Here’s a simple example of a triangle created with **SVG** polygons:

![triangle](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/22.PNG)

Here’s the code to do this:

![triangleCode](https://raw.githubusercontent.com/obbrbt/1600finalProject/main/images/23.PNG)

You can create almost any shape you desire with **SVG**. Just by following these simple steps, you can create an image on your own!



### Next Step: Making a Dog SVG Image

#### Tutorial Steps

* [Introduction Page](README.md)
* [Step One: What the Heck is SVG?](stepOne.md)
* [Step Two: What the Heck is HTML?](stepTwo.md)
* [Step Three: Creating an SVG Image (Current Page)](stepThree.md)
* [Step Four: Making a Dog SVG Image](stepFour.md)
* [Step Five: Adding Color](stepFive.md)
* [Closing Page](closing.md)
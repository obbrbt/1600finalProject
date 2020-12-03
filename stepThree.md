# Step Three: Creating an SVG Image



Alright, so now that we’ve discussed how to set up a basic HTML document, let’s begin talking about how to create an SVG image. W3schools has a more in-depth tutorial on how to create an SVG image [here](https://www.w3schools.com/graphics/svg_intro.asp).

The first step to creating an **SVG** image is to define your <svg></svg> tags.

After defining your <svg></svg> tags, you now need to define a height and width to the image.



Let’s discuss how an SVG image is mapped out.



First, think of your html document as a big graph. Each point on the graph is defined by an x- and y-coordinate. Each point corresponds to a pixel. For example, if you want your image to 100x100 pixels, imagine a graph that is 100x100 points large. By visualizing your HTML document as a graph, you can gain a better understanding of how to draw your image.



To define your image to be 100x100 pixels wide, write height=”100” width=”100” in your <svg> open tag like this: <svg height=”100” width=”100”>



The next step is to decide on what kind of image you want to create.



For a polygonal shape, I recommend drawing your desired image on graph paper, so you can define the points you need to create. This kind of image will have to be created with a polygon.



For a more simple image, you can use SVG’s predefined shapes, such as circles, rectangles and ellipses. Each of these shapes has its own defined properties, so be sure to check W3schools(https://www.w3schools.com/graphics/svg_intro.asp) for which properties you need for each shape.



To create a polygon SVG image, you need to define a polygon.



A polygon is defined with the <polygon></polygon> tags. Place your <polygon> tags inside of your <svg></svg> tags. To define properties of a polygon, you place them in the opening <polygon> tag. 



The shape of your polygon will be set with the “points” property. “Points” are coordinate values on a graph.



Put a points property in your polygon start tag like this: <polygon points=””></polygon>



The points of the polygon are defined as: points=”x1,y1 x2,y2 x3,y3”



Each of these points will be placed on a graph and lines will be drawn between them to create an image.



Here’s a simple example of a triangle created with SVG polygons:





Here’s the code to do this:





This is the set-up for a basic polygonal SVG image. From here, you can either create your own unique image by setting the points yourself or you can continue with this tutorial to create your own Dog SVG image.
# What the Heck is HTML?

We’re going to go over a broad definition of **HTML** and only discuss what is necessary for this tutorial. For a more in-depth tutorial on how to use **HTML**, I recommend using [W3Schools](https://www.w3schools.com/html/default.asp) tutorial on **HTML**.

To begin, let’s first discuss the purpose of **HTML**.

#### What is HTML?

According to *Wikipedia*, “_Hypertext Markup Language (**HTML**) is the standard markup language for documents designed to be displayed in a web browser._” [Reference](https://en.wikipedia.org/wiki/HTML).

So, just like **XML**, **HTML** is a web-based markup language. **HTML** is also the most commonly used markup language on the web.

#### Creating an HTML Document

Alright, so now you know what **HTML** is, but how do you *create* an **HTML** document?

To begin, first download an appropriate text editing software. It has to be a software that is _plain-text_, and not _rich-text_. _Plain-text_ means that formatting is defined on the page and is both human and machine-readable. Programs like *Brackets*, *Notepad++*, and *Visual Studio Code* are all examples of programs that use *plain-text*. 

_Rich-text_ that formatting is not viewable on the page and is only machine-readable. Programs like *Microsoft Word*, *TextEdit*, and *Google Docs* are all examples of programs that use *rich-text*. *Rich-text* is not viewable by browsers.  We need a software that is _plain-text_ and readable by a browser.

I like to use *Brackets* because it’s free and available on both Mac and Windows computers.

![Brackets](./images/1.png)

To follow along, open up your favorite plain-text editor. I'll be using Brackets. You can download Brackets [here:](http://brackets.io/). 

_**Note**: if you're following along in a different plain-text editor, the same features may not be available. For the best experience with this tutorial, I highly recommend using Brackets._

#### Getting Started in *Brackets*

Now, the first thing you want to do is open up a new file in *Brackets*. 

![newFile](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\2.PNG)

Before you start any editing, you want to save the file with a .html extension. 

![saveFile](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\3.PNG)

I’ll be calling my file “tutorial.html” but you can name yours to anything you wish, as long as it ends with “.html”.

![nameFile](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\4.PNG)

One nice feature in *Brackets* is the "live preview" function. At any time while writing your **HTML**, you can view your progress by click this button:

![livePreview](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\5.PNG)

Now that you have an **HTML** document ready, let’s discuss how to start writing **HTML**.

For our purposes, we’ll be using five basic tags in **HTML**, but know that there are many more.

#### <!DOCTYPE>

When you first create an HTML document, the first line of code you need is the **doctype declaration**. The doctype declaration provides information to your browser to prepare it to use a specific document format. In this case, it’ll be using the html format.

The doctype declaration looks like this: 

![docType](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\6.PNG)

It’s not case sensitive, so you can use **<!doctype>**, **<!DocType>**, **<!docType>**, or even <!dOcTyPe> and it will still work. However, it is most commonly seen in all caps, so that’s what we’ll be using for our document.

The format portion of the **<!DOCTYPE>** declaration contains what format to prepare our browser for. Since we’ll be using html, we want to prepare our browser to use html by having our first line of code look like this: 

![docTypeHtml](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\7.PNG)

#### HTML Tags

Let's talk about tags. 

**HTML** documents are made up of html tags. These tags are defined with **<>**. To create a tag, you put the tag name between **<>**, like this:

![tag](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\8.PNG)

This is an opening tag. You use it to start the definition of something. To close a tag, you use a / after the <, like this:

![closeTag](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\9.PNG)

Not all tags require both open and close tags. Some only need an opening tag. **&lt;img>** is a tag that only requires the open tag. To learn more about tags, visit this W3schools [link](https://www.w3schools.com/tags).

#### &lt;html>

The first basic tag we'll discuss is the **&lt;html>** tag.

The **&lt;html>** tag contains all of the information that goes into an **HTML** document, except for the **<!DOCTYPE>** declaration.

Every other tag that you create will be placed between the open **&lt;html>** tag and the close **&lt;/html>** tag.

Create the **&lt;html>&lt;/html>** tags in your document.

![htmlTags](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\10.PNG)

When you close the first **&lt;html>** tag, *Brackets* will automatically create the close tag.

#### &lt;head>

After creating **&lt;html>** tags, the next thing you want to write are the **&lt;head>&lt;/head>** tags. 

The **&lt;head>** in an **HTML** document can hold all sorts of things, including style sheets, scripts, and titles. For our purposes, we’ll only be using **&lt;head>** for a **&lt;title>** tag.

Add the **&lt;head>&lt;/head>** tags in between your **&lt;html>&lt;/html>** tags. Add some room in your document. It will help make it more readable.

![headTags](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\11.PNG)

#### &lt;title>

Now that you have a **&lt;head>** tag, let’s place **&lt;title>&lt;/title>** tags inside of them. Again, add some space between your tags to make your code more readable.

![titleTag](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\12.PNG)

The **&lt;title>** tag is used to define a title to your **HTML** document. Whenever you view an **HTML** document in a browser, the title will be at the top of the tab.

![titleBrowser](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\13.PNG)

For my **HTML** document, I’m going to be naming it “SVG Tutorial”. 

![svgTutorialTitle](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\14.PNG)

You can name yours whatever you like. Just make sure you place the title between the **&lt;title>&lt;/title>** tags and the **&lt;title>&lt;/title>** tags between **&lt;head> &lt;/head>** tags.

Also, this wouldn't be a bad time to use the live preview function in *Brackets*. You'll be able to see your title in your browser now!

![titleInBrowser](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\15.PNG)

#### &lt;body>

The final tag we’ll be discussing is the **&lt;body>** tag. Just like the other two tags, **&lt;body>** needs both an opening **&lt;body>** tag and a closing **&lt;/body>** tag. Add your **&lt;body>&lt;/body>** tags after your **&lt;head>&lt;/head>** tags. **&lt;body>** has to be placed outside of the **&lt;head>&lt;/head>** tags.

![bodyTags](C:\Users\Livvy\Documents\GitHub\final-project\1600finalProject\images\16.PNG)

The **&lt;body>** tag holds the “body” of your document. This could be things like headers, paragraphs, and images. Our body is going to hold our **SVG** image.

Great! Now we've created a base for our **HTML** document to house our **SVG** image. This basic outline can be used with almost any **HTML** document so be sure to remember it!

### Next Step: Creating an SVG Image

#### Tutorial Steps

* [Introduction Page](README.md)
* [Step One: What the Heck is SVG?](stepOne.md)
* [Step Two: What the Heck is HTML? (Current Page)](stepTwo.md)
* [Step Three: Creating an SVG Image](stepThree.md)
* [Step Four: Making a Dog SVG Image](stepFour.md)
* [Step Five: Adding Color](stepFive.md)
* [Closing Page](closing.md)




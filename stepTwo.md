# What the Heck is HTML?

We’re going to go over a broad definition of **HTML** and only use what is necessary for this tutorial. For a more in-depth tutorial on how to use **HTML**, I recommend using [W3Schools](https://www.w3schools.com/html/default.asp).

To begin, let’s first discuss the purpose of **HTML**.

According to Wikipedia, “_Hypertext Markup Language (**HTML**) is the standard markup language for documents designed to be displayed in a web browser._”
(https://en.wikipedia.org/wiki/HTML)


So, just like XML, HTML is a web-based markup language. HTML is also the most commonly used markup language on the web.

Alright, so now you know what HTML is, but how do you create an HTML document?

To begin, first download an appropriate text editing software. It has to be a software that is plain-text, and not rich-text. Plain-text means that what you see on the page is all the information available. Rich-text means that what you see on the page has things going on in the background, such as formatting. Microsoft Word, for example, is a rich-text format, so it won’t be appropriate for our purposes. We need a software that is plain-text and readable by a browser.

For this tutorial, I’ll be using Brackets. If you would like to follow along, I would recommend downloading Brackets here: http://brackets.io/ or using your favorite plain text editor.

I like to use Brackets because it’s free and available on both Mac and Windows computers.

Now, the first thing you want to do is open up a new file in Brackets. Before you start any editing, you want to save the file with a .html extension. I’ll be calling my file “tutorial.html” but you can name yours to anything you wish, as long as it ends with “.html”.

Now that you have an HTML document ready, let’s discuss how to start writing HTML.

For our purposes, we’ll be using five basic tags in HTML, but know that there are many more.

<!DOCTYPE>

When you first create an HTML document, the first line of code you need is the doctype declaration. The doctype declaration provides information to your browser to prepare it to use a specific document format. In this case, it’ll be using the html format.

The doctype declaration looks like this: <!DOCTYPE format>



It’s not case sensitive, so you can use <!doctype>, <!DocType>, <!docType>, or even <!dOcTyPe> and it will still work. However, it is most commonly seen in all caps, so that’s what we’ll be using for our document.



The format portion of the <!DOCTYPE> declaration contains what format to prepare our browser for. Since we’ll be using html, we want to prepare our browser to use html by having our first line of code look like this: <!DOCTYPE html>



<html>



The second basic tag we’ll be using is the <html> tag. 

Before we discuss the <html> tag, let’s first talk about tags in general. All tags have an opening tag that looks like this: <tag>

Some tags, like the <html> tag, need to have a close tag in order to be used. The html close tag looks like this: </html>



Not all tags require both open and close tags. Some only need an opening tag. <img> is a tag that only requires the open tag. To learn more about tags, visit this W3schools link: (https://www.w3schools.com/tags)

So, to use an <html> tag, make sure you also use the </html> close tag.



Now that we know more about tags, let’s talk about why you need to use the <html> tag in the first place. 



The <html> tag contains all of the information that goes into an HTML document, except for the <!DOCTYPE> declaration.

Every other tag that you create will be placed between the open <html> tag and the close </html> tag.

<head>



After creating your <html> tags, the next thing you want to write are the <head></head> tags. The <head> in an HTML document can hold all sorts of things, including style sheets, scripts, and titles. For our purposes, we’ll only be using <head> for a <title> tag.

<title>

Now that you have a <head> tag, let’s place <title></title> tags inside of them.



The <title> tag is used to define a title to your HTML document. Whenever you view an HTML document in a browser, the title will be at the top of the tab.



For my HTML document, I’m going to be naming mine “SVG Tutorial”. You can name yours whatever you like. Just make sure you place the title between the <title></title> tags and the <title></title> tags between the <head></head> tags.



<body>



The final tag we’ll be discussing is the <body> tag. Just like the other two tags, <body> needs both an opening <body> tag and a closing </body> tag.



The <body> tag holds the “body” of your document. This could be things like headers, paragraphs, and images. Our body is going to hold our <SVG> image.
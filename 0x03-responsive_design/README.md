<!DOCTYPE HTML>
<html lang= "eng">
<head>
<title>README.md</title>
<body>
Task 01:
Because we did some changes with the article.html page in the previous project, our hero banner background is no more visible. Let’s fix it!

But before that, to ensure we start on the same foot, you should use the starter HTML and CSS provided in the project description.

In your 01-styles.css file

Inside the hero-homepage class selector, update some values:
Property: background-position, Value: 65% 8rem
Property: background-size, Value: 90rem auto
Inside the selector that targets section-inner class inside section-hero class
Update the min-height to 35vh
task 1:Using the previous file as the base, in your 02-styles.css file update the .container selector by changing width to max-width

If you resize your browser, you should see that the content is resizing.

Wide screen:
Task 2:
Whatever the browser you use, it’s a good idea from now on, to toggle the device view.

In a normal situation, you should start with “mobile first” in mind and write your CSS first for the mobile. But because we already have a desktop version, we will exceptionally add some media-queries for mobile and tablet.

For extra large devices (no media queries)
For desktop / large devices (max-width: 992px)
For tablet / medium styles (max-width: 767px)
For mobile styles (max-width: 480px)
We will put media queries at the end of each section to facilitate the reading but for performance reasons, the best practice is to unifiy all similar breakpoints at the end of the CSS file.

In your 02-1-styles.css file:

inside the /* Helpers section target all images inside the main section

Property: width, Value: 100%
Property: height, Value: auto
inside the /* Section Latest news section, add a new media query (max-width: 767px)

Target the row inside section-latest-news
Property: flex-direction, Value: column
inside the /* Grid section, at the end, add a new media query (max-width: 767px)

First, redefine the variable section-padding and give that value: 5rem 1.5rem. And redefine the variable section-body-padding with 2rem 0 0
Target the ul.row and the row class
Property: flex-direction, Value: column
Property: margin, Value: 0
Target all the classes that started with col-
Property: margin, Value: 0 0 3rem 0
Target the col-1-3 and col-1-2 classes
Property: width, Value: 100%
The navbar is not allowing the website to fit the window. We will temporarily hide it and create a mobile navbar later.

inside the /* Navbar section, at the end, add a new media query (max-width: 767px)
Target the navbar-menu class
Property: display, Value: none
You should now be able to easily view the website on a device of any screen/window size. I guess you are surprised that was so easy?!

Rendering on wide screen
Task 3:
In Breakpoints generation settings:

Resolution: From 380 to 1200
Size step: 25
Maximum images: 3
Art-direction: Desktops
Upload your images one at a time:
pic-about-01.jpg
pic-article-01.jpg
pic-article-02.jpg
pic-article-03.jpg
Copy the markup for the <img> tags and replace your current <img> tags with it.
Download the images and place them into the images directory
Here’s an example on how to add different resolutions of the same image
</body></head>
</html>
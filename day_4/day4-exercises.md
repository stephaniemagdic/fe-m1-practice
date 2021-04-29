#Chapter 5 on Images HTML from HTML and CSS: Design and Build Websites


In an image element, why is the alt attribute important?

-An alt attribute provides a text description of the image which describes the image if you can't see it.


What determines if an image element is inline or block?

-If an <img> is followed by a block level element then the block level element will sit on a new line after the image. If the image is _inside_ of a block element, then the inline elements or text will flow around the image.


What are the benefits of jpg or png image file formats?


-JPEG are great for when you have many different colors in a picture.
-When there is flat color, a PNG (or GIF) is suitable. Flat colors are few colors or large areas with the same color.


Read Chapter 16 on Images CSS from HTML and CSS: Design and Build Websites

What is the benefit of specifying the height and width of images in CSS compared to specifying in the HTML?


-Often the HTML and CSS will load before the image, so it will tell the browser how much space to leave, which allows the rest of the page to render.
-You can use class attributes and CSS selectors.


What is an image sprite, and why is it useful?

-An image sprite is an image used many times, in several different parts of your interface. It is useful because the web browser only needs to request one image rather than many each time. This makes loading the web page faster. (book definition pg. 417)

-"In short: "CSS Sprites are a means of combining multiple images into a single image file for use on a website, to help with performance." It then will display just a portion of that image collection that it needs when calling that image. (google search definition)

-_OHHH!_ Now I get it! A sprite is one image which is really a collection of images. And the background position moves the image focus so that a specific part of that larger image shows up which ends up being a particular image of that collection! Interesting.

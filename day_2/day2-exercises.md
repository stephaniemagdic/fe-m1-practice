Answer these questions about the reading in your day2-exercises.md file:

#Chapters 2  & 3 HTML

There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
- _ordered lists_: lists where each item is numbered
- _unordered lists_: lists where each item is not numbered but begins with a bullet point
- _definition lists_: lists that are made up of a set of terms along with the definitions for each of the terms


What is the basic structure of an element used to link to another website?

- Links are created using the <a> element. Then the href attribute specifies the page the link takes you to. The text between the <a> tags is the text the user clicks on to go to that link.

Example:

```<a href="http://www.imdb.com">IMDB</a>```


What attribute should you include in a link to open a new tab when the link is clicked?

- To open a link in a new tab you should include the target attribute on the opening <a> tag and the value of the attribute should be _blank.


Example:

```<a href=http://imdb.com" target="_blank">Internet Movie Database</a>```


How do you link to a specific part of the same page?

- To link to a specific part of the same page you would need to identify the points in the page that you would like to go by using id attributes and placing those where you want to link to. Then to link to an element, you use the <a> element and the value of the href attribute starts with the # symbol and is then followed by the id attribute of the element you want to link to.

See below for an example.

```
<h1 id="top">Film-Making Terms</h1>
<p><a href="#top">Top</a></p>
```

##Chapters 10, 11, 12 CSS

What is the purpose of CSS?

- CSS allows you to create rules to specify how the content of an element should appear.


What does CSS stand for? What does cascading mean in this case?

- CSS stands for Cascading Style Sheets. The language is composed of cascading style sheets which are CSS files.
- Cascade means to arrange (a number of devices or objects) in a series or sequence.
- I believe that the cascade in CSS is an algorithm or set of rules that defines how to combine property values that come from different sources.
- A couple notes from pg. 239 and 240: "If there are two or more rules that apply to the same element, it is important to understand" that certain rules take precedence. There is also an idea of inheritance in CSS where some properties like font-family will be inherited and other properties like background-color is not inherited.


What is the basic structure of a CSS rule?

- A CSS rule contains two parts: a _selector_ and a _declaration_.
- A _selector_ indicates which element the rule applies to and the _declaration_ indicates how the elements referred to in the selector should be styled.
- Example:
          ```
          p {
              font-family: Arial; }
          ```
- The _declaration_ has a _property_ and a _value_. The _property_ indicates the aspect of the element you want to change like the color, font, width, etc. The _value_ specifies the settings you want to use for the chosen properties, for example the color you want to specify on the color property.


How do you link a CSS stylesheet to your HTML document?


-To link a CSS stylesheet to your HTML document you use the <link> element to tell the browser where to find the CSS file to style the page. You should include three attributes within the the link tag: href, type and rel. The link to the stylesheet lives inside the <head> element. (pg. 235)

-Example:
```
<head>
<link href="css/styles.css" type="text/css" rel="stylesheet" />
</head>
```


When is it useful to use external stylesheets as opposed to using interal CSS?

-It can be useful to use external stylesheets for the following reasons: all of your web pages can share the same style sheet and you do not have to repeat it in every page, which also means the stylesheet will load faster; If you want to make a change to how the site looks, then you only have to edit the single style sheet; and finally the HTML code will be easier to read and edit because it doesn't contain all the CSS rules in the same document.

(It's generally good practice to use external style sheets.)


Describe what a color hex code is.

- A color hex code is a six-digit code that represents the amount of red, green and blue in a color. (It is one of 4 ways -that I know of- of specifying colors.)


What are the three parts of an HSL color property?

- The HSL property includes hue, saturation, and lightness (not to be confused with brightness). (See page 255)


In the world of typeface, what are the three main categories of fonts? What are the differences between them?

- Serif: serif fonts have _extra details on the ends_ of the main strokes, known as serifs
- Sans-Serif: sans-serif fonts have _straight ends_ to letters (much cleaner design)
- Monospace: every letter in a monospace font is the same width (for a fixed width). Monospace fonts are commonly used for code because they align nicely


When specifying font-size, what are the main three units used?

-Pixels, percentages and ems are several ways to specify the size of the font.

1.  On a website, what is the purpose of HTML code?


  HTML stands for HyperText markup language. The purpose of HTML code is to describe the structure of the webpage. It uses elements to do this. There are tags that act like containers and tell us something about the the info that is held within the opening and closing tags. The tags are known as markup. There are two types of markup: structural and semantic. *Semantic* markup are the elements that provide extra information and *structural* markup are the elements we can use to describe or give information about the structure of the document (this can include both the headings and the paragraphs).


2.  What is the difference between an element and a tag?


  *Tag* and *element* are used interchangeably but the difference is that an element includes the opening and closing tag _and_ any content that lies between those tags.


3.  Why do we use attributes in HTML elements?


  We use attributes in HTML elements to provide additional information about the contents of an element.

  Some example attributes include the href attribute, the src attribute, the alt attribute, and the style, language and title attributes.


4.  Describe the purpose of the head, title, and body HTML elements.


  *_Head_: The head element comes before the body and includes information about the page. The information is not shown on the main part of the browser window to the user. Usually we will find a <title> element inside the <head> element.
  *_Title_: The title element holds contents that are either shown at the top of the browser or on the tab for the page. Similar to the head, it is not shown in the browser window itself. The title provides a title for when you add the page to favorites or displays a title when a search engine displays the result for a user.
  *_Body_: Finally, the <body> element on the other hand holds everything that is shown in the main browser window.

  ```
  <head>
    <title></title>
  <head>
  <body>


  </body>
  ```


5.  In your browser (Chrome), how do you view the source of a website?


  To view the source, you can simply go to your toolbar and click _view_, _develop_, and _view source_. You can also use your mousepad to double click and go to _view page source_.


6.  List five different HTML elements and what they are used for. For example, `<p></p>` is a paragraph element, and it is used to represent a paragraph of text.


  _<b> </b>_ is a bold tag and by enclosing words in these opening and closing tags we make those characters appear bold. It would be visually presented differently but does not necessarily imply any additional meaning.
  _<i> </i>_ is an italic tag and by enclosing words in the opening and closing tags we make those characters appear italic. These words words be said differently than the surrounding content.
  _<br />_ is a break tag that provides a line break. If you wanted to add a line break you can use this tag. This is helpful if you wanted to add a line break inside the middle of a paragraph where the browser doesn't automatically show a line break.
  _<strong>_: The strong element indicates that the contents within the opening and closing tags have strong importance. This is element provides _semantic markup_. By default, browsers will show the contents of this element in bold.
  _<q>_: the <q> element is used for short (shorter than what is put in blockquotes) quotes that will sit within a paragraph. The browser will put quotes around this element.


7.  What are empty elements?


  Elements that do not have any words between the opening and closing tags are _empty elements_. For example the <br /> element just described above is an empty element. They are written a bit differently (before the closing angled bracket there will often be a space and a forward slash) and they also usually only have one tag.


8.  What is semantic markup?


  _Semantic_ markup provides extra information to the pages. Unlike structural markup, the text elements are not meant to affect the structure of the web pages.


9.  What are three new semantic elements introduced in HTML 5? Use page 431 in the book to find more about these new elements.


HTML5 offers helpful alternatives to the <div> element. HTML5 introduce a new set of elements that allow you to divide up the parts of a page and the names of the element indicate the kind of content you will find in them.

For example instead of using a div element for the header, nav, article and footer, you now have HTML5 elements for each. We now have HTML5 layout elements for these. We now have <header>, <nav> and <article>.

Here are some examples below.

- Navigation (<nav>): The nav element contains the major navigational blocks, such as the primary site navigation, like links to individual pages on a website.

- Article (<article>): The article element contains any section of the page that can stand alone, such as an individual article or blog entry, a comment or forum post, or any other independent piece of content.

- Sections (<section>): The section element groups related content together (and typically each section should have its own heading).

Note: Divs are still an important way to group together related elements in HTML5. We should only use the new HTML5 layout elements for their explicitly stated purposes. Therefore when there is *no* suitable element to group a set of elements, the div element should be used.


[Codepen practice](https://codepen.io/stephaniemagdic/pen/QWdzyXo)

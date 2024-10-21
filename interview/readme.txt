1) difference between html4 and html5?
ans) HTML5 is the latest and most advanced version of HTML4. HTML5 has new features and tags, and it has simplified some functions. It also offers more flexibility to developers for creating websites. 


2) what is meta data ?
ans) The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data. <meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.


3) what is html?
ans) HTML stands for HyperText Markup Language. It is a standard text formatting language used for developing web pages released in 1993. HTML is a language that is interpreted by the browser and it tells the browser what to display and how to display.In simple words html is work as the structure of our websites.


4)  What are tags and attributes in HTML?
ans) Tags are the primary component of the HTML that defines how the content will be structured/ formatted, whereas Attributes are used along with the HTML tags to define the characteristics of the element. For example, <p align=” center”>Interview questions</p>, in this the ‘align’ is the attribute using which we will align the paragraph to show in the center of the view.

5) What are different types of lists in HTML?
ans) ordered ,unordered and description list.

6)  What is the ‘class’ attribute in HTML?
ans) The class attribute is used to specify the class name for an HTML element. Multiple elements in HTML can have the same class value. Also, it is mainly used to associate the styles written in the stylesheet with the HTML elements.


7) Describe HTML layout structure.
ans) Every web page has different components to display the intended content and a specific UI. But still, there are few things which are templated and are globally accepted way to structure the web page, such as:

<header>: Stores the starting information about the web page.
<footer>: Represents the last section of the page.
<nav>: The navigation menu of the HTML page.
<article>: It is a set of information.
<section>: It is used inside the article block to define the basic structure of a page.
<aside>: Sidebar content of the page.


8) Difference between Class annd Id ?
 ans) Class name can be used by multiple HTML elements, while an ID name must only be used by one HTML element within the page. 


 9) Difference between semantic and non- semantic ?
ans) Semantic tags convey meaning and structure to content, while non-semantic tags are used for formatting and styling.In simple words, Semantic HTML tags are tags that define the meaning of the content they contain. For example, tags like <header>, <article>, and <footer> are semantic HTML tags. They clearly indicate the role of the content they contain. On the other hand, tags like <div> and <span> are typical examples of non-semantic HTML elements.


10) what are block element and inline element?
ans) A block-level element always starts on a new line and takes up the full width available. An inline element does not start on a new line and it only takes up as much width as necessary.

11) In how many ways you can display HTML elements?
ans) inline: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.
block: using this, we can display any inline element as a block-level element. 
inline-block: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.
flex: It displays the container and element as a flexible structure. It follows flexbox property.
inline-flex: It displays the flex container as an inline element while its content follows the flexbox properties.
grid: It displays the HTML elements as a grid container.
none: Using this property we can hide the HTML element.


12) What is the difference between “display: none” and “visibility: hidden”, when used as attributes to the HTML element.
When we use the attribute “visibility: hidden” for an HTML element then that element will be hidden from the webpage but still takes up space. Whereas, if we use the “display: none” attribute for an HTML element then the element will be hidden, and also it won’t take up any space on the webpage.

13) In how many ways can we specify the CSS styles for the HTML element?

ans) There are three ways in which we can specify the styles for HTML elements:

Inline: Here we use the ‘style’ attribute inside the HTML element.
Internal: Here we use the <style> tag inside the <head> tag. To apply the style we bind the elements using ‘id’ or ‘class’ attributes.
External: Here we use the <link> tag inside <head> tag to reference the CSS file into our HTML code. Again the binding between elements and styles is done using ‘id’ or ‘class’ attributes.


14) Difference between link tag <link> and anchor tag <a>?
The anchor tag <a> is used to create a hyperlink to another webpage or to a certain part of the webpage and these links are clickable, whereas, link tag <link> defines a link between a document and an external resource and these are not clickable.


15) What are forms and how to create forms in HTML?
The HTML form is used to collect the user inputs. HTML provides a <form> tag to create forms. To take input from the user we use the <input> tag inside the form so that all collected user data can be sent to the server for processing. There are different input types like ‘button’, ‘checkbox’, ‘number’, ‘text’, ‘password’, ‘submit’ etc.


16) What are some of the advantages of HTML5 over its previous versions?
Some advantages of HTML5 are:-

It has Multimedia Support.
It has the capabilities to store offline data using SQL databases and application cache.
Javascript can be run in the background.
HTML5 also allows users to draw various shapes like rectangles, circles, triangles, etc.
Included new Semantic tags and form control tags.

17) What is the difference between HTML and CSS?
HTML is used to create the structure and content of a web page, while CSS is used to define the appearance and layout of the page.

18) How do you create a hyperlink in HTML?
We use the anchor tag <a> to create a hyperlink in HTML that links one page to another page. The hyperlink can be added to images too.

19) What is the difference between an absolute and relative URL?
An absolute URL includes the full web address, the protocol (such as http or https) and the domain name (such as www.example.com). A relative URL, on the other hand, specifies the location of a resource relative to the current web page. For example, a relative URL might include the file path (such as /images/picture.jpg) or the relative path (such as ../images/picture.jpg).

20) What do you understand by the universal sector?
A universal selector is a selector that matches any element type's name instead of selecting elements of a particular type.

21) Differentiate between CSS3 and CSS2.
The main difference between CSS3 and CSS2 is that CSS divides different sections into modules and supports many browsers. It also contains new General Sibling Combinators responsible for matching similar elements.

22)  Define z-index.
This is one of the most frequently asked CSS interview questions. Z-index is used to specify the stack order of elements that overlap each other. Its default value is zero and can take both negative and positive values. A higher z-index value is stacked above the lower index element. It takes the following values- auto, number, initial, and inherit.

23) . Explain responsive web design. 
Responsive Design is a web page creation approach that uses flexible images, flexible layouts, and CSS media queries. This design approach aims to build web pages that detect the orientation and screen size of the visitors so that the layout can be changed accordingly.

24)What is a CSS Preprocessor? What are Sass, Less, and Stylus? Why do people use them?
CSS preprocessor is a tool used to enhance the basic functionality and let us use the complex logical syntax such as variables, functions, mixins, and code nesting within vanilla CSS scripts themselves.

Sass (Syntactically Awesome Style Sheets) uses .sass extension. It is used for indentation; it doesn’t use semicolons or curly brackets.
Less (Leener Stylesheets) uses .less extension. It is easy to add to any JavaScript Project by using NPM or less.js file. Here, @ is used to define the variables. 
Stylus provides great flexibility in writing syntax. It is able to use native CSS as well as the exclusion of brackets, colons, and semicolons. There is no need to use @ or $ to define the variables.
People use SASS, LESS, and Stylus in order to extend the basic functionality of vanilla CSS.

25) What is VH/VW (viewport height/ viewport width) in CSS?
VH and VW are CSS units used to measure viewport height and viewport width respectively in percentage form in the responsive design techniques. E.g. If the height of the browser is 1000px, then VH is 1/100 of the height of the viewport that is 1000px*(1/100) = 10px, which is the height of the browser.  The same applies to VW (viewport width).

26) What is the difference between inline, inline-block, and block?
Block Elements are <div> and <p>. They usually start on a new line and can take space for an entire row or width.
Inline elements are <a>, <span>, <strong>, and <img> tags. They don't start on a new line. However, they appear on the same line as the content and tags beside them.
Inline block elements have padding and margins and set height and width values. Though, they are similar to inline elements.

27)What are Pseudo classes?
Pseudo-classes are the type of pseudo-elements that don’t exist in a normal document tree. It allows selecting the regular elements under certain conditions especially when we try to hover over the link; the anchor tags are :link, :visited, :hover, :active, :focus.

28) . Differentiate between absolute and relative in CSS. 
The main difference is that relative is used for the same tag in CSS. If we write right:20 px, then padding shifts 20 px in the right. Whereas absolute is relative to the non-static parent, i.e., if we write right:20 px, the result will be 20 px far from the right edge of the parent element.


29)What is CSS Box Model?
A rectangle box is wrapped around every HTML element. The box model is used to determine the height and width of the rectangular box. The CSS Box consists of Width and height (or in the absence of that, default values and the content inside), padding, borders, margin.

Content:  Actual Content of the box where the text or image is placed.
Padding: Area surrounding the content (Space between the border and content).
Border: Area surrounding the padding.
Margin: Area surrounding the border


32). How to create a nested webpage in HTML?
ans ) The HTML iframe tag is used to display a nested webpage. In other words, it represents a webpage within a webpage.


33)How do you center an element horizontally in CSS?

To center an element horizontally in CSS, you can use one of the following methods:

Set the left and right margins to "auto" and specify a width for the element.
Use the flexbox layout by setting the parent container's "display" property to "flex" and using the "justify-content" property with a value of "center

34)In CSS, padding and margin are properties that control the space around an element, but they serve different purposes:

Padding: This property defines the space between the content of an element and its border. It is usually used to create extra space around the content inside an element. Padding is included within the background color or background image of the element and holds the border outside the actual content.
Margin: This property defines the space around the outside of an element, between the element and its surrounding elements. It is used for creating space between elements, and it is transparent. Margin is situated outside the border, so if an element has a background color or image, it won't influence the margin.

35)Explain the difference between px, %, em, and rem units in CSS.

In CSS, different units of measurement are used to define lengths, dimensions, and sizes. Some commonly used units are px, %, em, and rem. Each has its own unique characteristics:

px (pixels): One of the most commonly used units, a px represents an absolute length or size in terms of screen pixels. 1px is equal to one dot on the screen. The actual physical size of a pixel may vary depending on screen resolution, but px provides a consistent measurement across devices and displays.
% (percentage): Percentage values are relative to another value, such as the width or height of a parent element. As a result, they offer a more fluid and responsive approach to sizing elements.
em: The em unit is relative to the font size of the element itself or the nearest parent element with a specified font size. 1em is equal to the current font size, so if the font-size of the document is 16px, then 1em will equal 16px.
rem: Similar to em, the rem unit is relative to the font size. However, rem is always relative to the base (root) font size of the document, usually defined on the element. This unit provides a consistent way to scale elements based on the overall font size of the page, without being affected by the font size of parent elements.


36)The CSS opacity property is used to control the transparency of an element. It accepts a value between 0 (completely transparent) and 1 (fully opaque). It can be used to create subtle transparency effects or fade animations.


37)Explain the difference between nth-child() and:nth-of-type() selectors.

Hide Answer
Both :nth-child() and :nth-of-type() are CSS pseudo-class selectors that allow you to target specific elements based on their position in a group of siblings. However, they differ in the way they determine which elements to select.

:nth-child() selects elements based on their position in the group of all sibling elements, regardless of their type (e.g., < div >, < p >, < li >). The syntax is :nth-child(an+b), where a and b are integers and n is a counter that starts from 0.

:nth-of-type() selects elements based on their position in a group of siblings with the same element type. The syntax for :nth-of-type() is almost identical to :nth-child(): :nth-of-type(an+b).

38)The CSS calc() function allows you to perform calculations to determine the value of a property. It is particularly useful for sizing and positioning elements. Some examples of its use include:

Setting the width of an element based on a percentage minus a fixed pixel value: "width: calc(50% - 20px);"
Calculating the height of an element based on the viewport height minus a specific value: "height: calc(100vh - 100px);".

39)CSS specificity determines which styles are applied when conflicting styles are present. Specificity is calculated based on the type of selectors used and their order of appearance. Inheritance, on the other hand, allows certain properties of an element to be inherited by its children.

The !important rule is a declaration that gives a style the highest specificity and overrides any conflicting styles. However, it is generally recommended to avoid using !important as it can make styles harder to maintain and override.

40)The two steps are selection and declaration.
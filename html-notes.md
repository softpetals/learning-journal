
# HTML- the bones of the webpage!

The HTML code is made up of charecters that live inside angled brackets - these are called elements. Elements are usuallt made up of two tags: an opening tag and a closing tag. Each html element tells the browser something about the information that sits between its opening and closing tags. 
Tags act like container. They tell you something about the information that lies between their opening and closing tags. 
Attributes provide additional information about the contents of an element. They appear on the opening tag of the element and are made up of two parts: a name and a value, seperated by an equals sign. 
The attribute name indicated what kind of extra info you are supplying about the elements content. It should be written in lowercase. 
The value is the information setting for the attribute. It should be placed in double quotes. Diff attributes can have different values. 

when we make comments in html5 we use this code

<!-- comment goes here, this will be visible to the coder but not the viewer -->


the CHARECTERS in the brackets indicate the tags purpose.

ELEMENT is the same thing as a tag, but strictly speaking it compromises of an opening tag a closing tag and all the content that lies between them

ATTRIBUTES provide additional information about the contents of an element.
Attributes appear in the opening tag of the element and made up of two parts: a name and value, seperated by and equals sign.

VALUE is the information or setting for the attribute. it should be placed in double quotes. diff attributes can have diff values 

use text wrangler to start writing your html code on mac 

header element, main element and footer element
body 

head is stuff to help you render the body of the website that you expect to see


## How to start and HTML page.

<!DOCTYPE html>
<html lang="en">
<head>
 <title> Document</title>
</head>
<body>
<header>
 <h1> Krystyna Solodenko Photography </h1>
ELEMENTS

<body>: What you see on the wb browser page.

<head>: All the information about the page.

<p>: Paragraph

<ul>: Unordered List

<ol>: Ordered List

<h1>: Level 1 Header

<nav>: Navigation

 (Links to an external site.)HTML5 Layout (Chapter 17)
The <div> element is used to group together related elements on the page.
The class or id attributes indicate the role of the <div> element in the structure of the page.
 (Links to an external site.)HTML5 Layout Elements:
The <header> and <footer> elements can be used for:
The main header or footer that appears at the top or bottom of every page on the site.
A header or footer for an individual <article> or <section> within the page.
The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.
The <article> element acts as a container for any section of a page that could stand alone.
The <aside> element has two purposes depending on whether it is inside an <article> element or not.
When the <aside> element is used inside a <article> element. it should contain info that is related to the article but not essential to its overall meaning. Ex.) a pullquote or glossary.
When the <aside> element is used outside of an <article>, it acts as a container for content that is related to the entire page. Ex.) links to other sections of the site or a search box.
The <section> element groups related content together.
The <hgroup> element groups together a set of one or more <h1> through <h6> elements so they are treated as a single heading.
The <figure> element is used to contain any content that is referenced in the main flow of an article (not just images.) Examples of usage are images, videos, graphs, diagrams, code samples, and text that supports the main body of an article.
THe <figure> element should also contain a <figcaption> element which provides a text description for the content in the figure element.
 (Links to an external site.)Extra Markup (Chapter 8)
Because there are several versions of HTML, each web page should begin with a DOCTYPE declaration on top to tell what type it is.
If you want to add a comment in the code that isn't visible in the user's browser use: <!--comment goes here-->
The id attribute is used to uniquely identify an element from other elements on the page. Its value should start with a letter or an underscore. The id attribute is known as a global attribute because it can be used on any element.
The class attribute gives a way to identify several elements as being different from the other elements on the page. Its value should describe the class it belongs to.
Block Elements are elements that will always appear to start on a new line in the browser window. Examples of block elements are: <h1>, <p>,<ul>, and <li>.
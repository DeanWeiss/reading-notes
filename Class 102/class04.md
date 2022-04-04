# Structure Web Pages

## WireFrames

Wireframes - Define and plan the information hierachy of their design for a website, app, or product. Get to know how a user interacts with your interface, through the positioning of buttons and menus on the diagrams.

You can use paper and pencil or a white board, it is easier to change.
Paper prototypes - you can test with end users.
Software - keep track of more detailed decisions.

Before starting your wireframe consider the following. how much emphasis is there on the visual design in a project, and how much uncertaintiy there is with respect as to what is being designed.

Differen process that can be used.
Wireframe > Interactive Prototype > Visual > Design
Sketch > Code
Sketch > Wireframe > Hi-Def Wireframe > Visual > Code
Sketch > Wireframe > Visual > Code

UXpin, InVision and Wireframe.cc are all tools that are free that can be used.

## HTML Basics

HTML - HyperText Markup Language

It is a markup language that defines the structure of your content. It uses a series of elements which you use to enclose different parts of the content to make it appear in a different way. What we enclose with are called tags. 

The four main part of our element is as follows.

1. Opening Tag
2. Closing Tag
3. The content
4. The Element - Is the Opening, closing and content all together.

Elements can have attributes, which adds on different information that doesn't appear in the actual content.

Empty elements have no content. The prime example beint the `<img>` element.

### The Anatomy of the HTML document

`<!DOCTYPE html>` — doctype. It is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.
`<html></html>` — the `<html>` element. This element wraps all the content on the entire page and is sometimes known as the root element.
`<head></head>` — the `<head>` element. This element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.
`<meta charset="utf-8">` — This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.
`<title></title>` — the `<title>` element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.
`<body></body>` — the `<body>` element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

### Marking up text

`<H1>` to `<H6>` for headings
`<p>` for paragraph
`<ul>` Unordered list `<ol>` Ordered list
`<li>` list item
`<a>` is an anchor Links usually with the element href. Example `<a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</a>`

## Semantics

Semantics refers to the meaning of a piece of code. What effect does running that line of Javascript have? or what purpose does that HTML element have? rather than 'what does it look like?'

HTML should be coded to represent the data that will be populated and not based on its default presenting sytling. Presentation is the sole responsibility of CSS.

Some of the benefits from writing semantic markup are as follows:

1. Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
2. Screen readers can use it as a signpost to help visually impaired users navigate a page
3. Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
4. Suggests to the developer the type of data that will be populated
5. Semantic naming mirrors proper custom element/component naming

[<===BACK](README.md)
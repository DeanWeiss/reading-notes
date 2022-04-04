# Class 05 Reading

## What is CSS?

CSS = Cascading Style Sheet. 
CSS allows you to create web pages that look good. It is specifically for how the web-page is presented to the users.
CSS is a rules based language. 
It starts with a Selector, which is part of a rule that describes what elements in a document the rule will match. 
CSS uses curly brackets `{}`
The CSS language is broken down into modules. 
CSS is developed by a group within the W3C called the CSS Working Group.

## How to Add CSS

Thre ways of inserting a style sheet.
    External CSS
    Internall CSS
    Inline CSS

External CSS

    An external style sheet. Able to change the look of the website from a single file. Each HTML page must have a reference to the external seet inside the the head section.
    Must be saved with the .css extension and should not contain any HTML tags.

Internal CSS

    Internal style sheet can be used if one single HTML page has a unique style. It is defined inside the `<head>` section of the HTML Page.

Inline CSS

    An inline style may be used to apply a unique style to a single element.
    The style attribute to the relevant element. The style attribute can contain any CSS property.

Cascading Order

    What style will be used when there is more than one style specified for an HTML element?
    All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

    1. Inline style (inside an HTML element)
    2. External and internal style sheets (in the head section)
    3. Browser default
    So, an inline style has the highest priority, and will override external and internal styles and browser defaults

    ## CSS Color Property

    Definition and Usage - The color propery specifies the color of the text. 
    Color - Specifies the text color.
    Initial - Sets this propery to its default value
    inherit - Inherits this property from its parent element.

[<===BACK](README.md)
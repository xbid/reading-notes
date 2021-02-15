# CSS Layout

> CSS layouts are used to, well, **layout your content**. CSS being respoinsible for the *styling* of your site, positioning falls under that umbrella of style. From *positining* left to right, top to bottom, margin, padding, floats, grid systems, etc.

***CSS has a myriad of ways to position and move elements on a webpage.***

![ ](https://sabe.io/classes/css/hero.png)
Photo by [sabe.io](https://sabe.io/classes/css/hero.png)

Here is a list of types of CSS Layouts and a handy little CSS framework.

- Fixed Width
- Fluid (or liquid)
- Grid Layout
- Flex*box*
- BootStrap

![ ](https://www.touchmediaads.com/myimg/b1.3.gif)

Gif by [Touchmedia](https://www.touchmediaads.com/myimg/b1.3.gif)

## Layout in Css:-

CSS treats each HTML element as if it is in its own *box*. This *box* will either be a ***block-level box*** or an inline *box*. CSS treats each HTML element as if it is in its own *box*. This *box* will either be a ***block-level box*** or an inline *box*.

***The float*** property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined ***width***).

Pages can be *fixed width* or *liquid* (stretchy) layouts.

> ***Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.***

Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

***Fixed width layout*** designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.

Many designers use a ***grid structure*** to help them position items on a page, and the same is true for web designers.

*CSS Frameworks provide rules for common tasks*.

### Layout

We will Cover The following :

- In this chapter we are going to learn how to control where each element sits on a page and how to create attractive page layouts.

- Controlling the position of elements.

- creating site layout.

- Designing for different sized screens.

### Position Concept

Css treat each element in html doc. as a *box*, this *box* could be a block level *box* so will sit and take the whole area or the whole width and start on a new line. or it could be inline *box* and these boxes flow in between surrounding text and you can manage the spaces that this *box* will sit on it, by some properities (***width, height, padding, margin, borders***).

If one ***block-level*** element sits inside another **block-level** element then the outer *box* is known as the containing or parent element.

- **inline Element**

- **Block Element**

Controling the layout of page will be by using positioning schemes in differents ways: normal, relative absolute, static, …

devices have diffrenets screen sizes, So the web disginer should take the different layouts grids into considreation.

![ ](https://www.logicalposition.com/img/websites/responsive-white-bg.gif)

Gif by [LP](https://www.logicalposition.com/)

#### Summary

> elements are often used as containing elements to group together sections of a page.

> Browser display pages in normal flow, unless you changed the position for another value.

> float property can float the content of the container to the left or to the right, and it needs a clear property after using it avoiding to transfer the floating affect to the next elements. and we need to define the width when we use float property to see the affect.

> Pages can be fixed width or liquid (stretchy) layouts.

> Designers keep pages within 960-1000 pixels wide, and indicate  what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).

> Using grids we can create profassional and flexable designs.

> CSS Frameworks provide rules for common tasks.

> You can make a multiple css files and see their affect in one page.

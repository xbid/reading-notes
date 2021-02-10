# HTML Links, JS Functions, and Intro to CSS Layout

![H&J](https://swall.teahub.io/photos/small/22-220767_web-developer-wallpaper-4k.jpg)

Photo by [Tea Hub](https://swall.teahub.io)

## LINKS

Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

***Types of links***

- links from websites

- links from pages

- links from part of the web page

- links open in new window

- links that start up the email program and addres a new email to someone

***Writing Links***

Links are created using the ```<a>``` element. Users can click on anything between the opening ```<a>``` tag and the closing ```</a>``` tag. You specify which page you want to link to using the *href* attribute.

![  ](class04\fr1.JPG)

Photo by Ducket Book

The text between the opening ```<a>``` tag and closing ```</a>``` tag is known as link text. Where possible, It should explain where visitors will be taken if they click on it.

### Linking to other sites

```<a>```

Links are created using the ```<a>``` element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.

*chapter-04/linking-to-other-sites.html*

~~~
<p>Movie Reviews:
  <ul>
        <li><a href="http://www.empireonline.com">Empire</a></li>
        <li><a href="http://www.metacritic.com">Metacritic</a></li>
        <li><a href="http://www.rottentomatoes.com">Rotten Tomatoes</a></li>    
        <li><a href="http://www.variety.com">Variety</a></li>
  </ul>
</p>
~~~

URL stands for Uniform Resource Locator.

Users can click on anything that appears between the opening ```<a>``` tag and the closing ```</a>``` tag and will be taken to the page specified in the href attribute.

### Linking to other pages on the same site

```<a>```When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.

All the pages of the site are in the same folder, the value of the href attribute is just the name of the file.

*chapter-04/linking-to-other-pages.html*


~~~
<p>
  <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about-us.html">About</a></li>
        <li><a href="movies.html">Movies</a></li>
        <li><a href="contact.html">Contact</a></li>
  </ul>
</p>
~~~


### Relative URLS

Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

### EmaiL Links

mailto:

To create a link that starts up the user's email program and addresses an email to a specified email address, you use the ```<a>``` element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.

### Opening Links in A new Window

target

If you want a link to open in a new window, you can use the target attribute on the opening tag. The value of this attribute should be _blank.

### Linking to A specific part oF the same page

To link to an element that uses an id attribute you use the element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to.

### Linking to A specific part of Another page

If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique.

As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page.

## Layout

### Key Concepts in positioning elements

We are going to look at how to control where each element sits on a page and hpw tp create attractive page latouts.

You will be learning.

- Different ways to position elements using normal flow, relative positioning, absolute positioning and floats.

- Discover how various devices have different screen sizes and resolution, and how this affects the design process

- Learn the difference between fixed width and liquid layouts, ●and how they are created.

- Find out how designers use grids to make their page ●designs look more professional.

**Key Concepts in positioning eLements**

**Building Blocks**

![  ](class04\se2.JPG)

Photo by Ducket Book

**Containing Elements**

![  ](class04\th3.JPG)

Photo by Ducket Book

**ControLLing the position of eLements**

CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the positionproperty in CSS. You can also float elements using the float property.

![  ](class04\fo4.JPG)

Photo by Ducket Book

### Screen Sizes

Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

![  ](class04\fi5.JPG)

### Screen Resolution

Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

### Page Sizes

Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens)

### Fixed Width Layouts

![  ](class04\si6.JPG)

### Liquid Layouts

![  ](class04\si7.JPG)

## JAVASCRIPT 
*Functions, Methods, and Objects*

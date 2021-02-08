# Basics of HTML, CSS & JS

![web](https://pocketnow.com/files/2017/01/PN-Complete-Web-Programming.jpg)

Photo by [Pocket Now](https://pocketnow.com)

- [Headings and paragraphs](#headings)

- [Bold, italic, emphasis](#bold-and-italic)

- [Structural and semantic markup](#bold-and-italic)

- [What CSS does](#introducing-css)

- [How CSS works](#introducing-css)



## Text

![html](https://i.pinimg.com/originals/37/1d/b8/371db84b01a8b6ecc9add7131abba6dd.gif)

Photo by [Pin img](https://i.pinimg.com)

# HEADINGS

```<h1> <h2> <h3> <h4> <h5> <h6>```

Each one of these heading tags has its purpose.

- ```<h1>``` is used for main headings

- ```<h2>``` is used for subheadings

If there are further sections under the subheadings then the ```<h3>``` element is used, and so on...

*The Html Heading Tags*

~~~
<h1>This is a Main Heading</h1>
<h2>This is a Level 2 Heading</h2>
<h3>This is a Level 3 Heading</h3>
<h4>This is a Level 4 Heading</h4>
<h5>This is a Level 5 Heading</h5>
<h6>This is a Level 6 Heading</h6>
~~~

![header](class02\hres1.JPG)

**PARAGRAPHS**

```<p>```

To create a paragraph.

The browser will show each paragraph on new line, by default,

*The Html paragraph Tag*

~~~
<p>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, quos. Officiis, magnam!
</p>
<p>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, quos. Officiis, magnam!
</p>
~~~

*Result*

Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, quos. Officiis, magnam!

Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, quos. Officiis, magnam!

# BOLD and ITALIC


**Bold**

```<b>```

 By enclosing words in the tags ```<b>``` and ```</b>``` we can make characters appear bold.

*Italic*

```<i>```

By enclosing words in the tags ```<i>``` and ```</i>``` we can make characters appear italic.

![b&i](class02\bi.JPG)

# SUPERSCRIPT and SUBSCRIPT

**```<sup>```**

The ````<sup>``` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

**```<sub>```**

The ```<sub>``` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.

![sub sup](class02\spb.JPG)

# WHITE SPACE

When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as white space collapsing.

![ws](class02\ws.JPG)

# LINE BREAKS & HORIZONTAL RULES

**```<br />```**

if you wanted to add a line break inside the middle of a paragraph you can use the line break tag ```<br />```.

**```<hr />```**

To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the ```<hr />``` tag.

![brhr](class02\brhr.JPG)

# STRONG and EMPHASIS

**```<strong>```**

The use of the ```<strong>``` element indicates that its content has strong importance. 

**```<em>```**

The ```<em>``` element indicates emphasis that subtly changes the meaning of a sentence.

![sem](class02\sem.JPG)

# QUOTATIONS

**```<blockquote>```**

The ```<blockquote>``` element is used for longer quotes that take up an entire paragraph. Note how the ```<p>``` element is still used inside the ```<blockquote>``` element.

**```<q>```**

The ```<q>``` element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the ```<q>``` element, however Internet Explorer does not — therefore many people avoid using the ```<q>``` element.

![quote](class02\quote.JPG)

# ABBREVIATIONS & ACRONYMS

```<abbr>```

If you use an abbreviation or an acronym, then the ```<abbr>``` element can be used. A titleattribute on the opening tag is used to specify the full term.

# CITATIONS & DEFINITIONS

**```<cite>```**

 the  **```<cite>```** element can be used to indicate where the citation is from.

 **```<dfn>```**

 The **```<dfn>```** element is used to indicate the defining instance of a new term.

# AUTHOR DETAILS

**```<address>```**

The ```<address>``` element has quite a specific use: to contain contact details for the author of the page.

# CHANGES To CONTENT

**```<ins>```**

**```<del>```**

The **```<ins>```** element can be used to show content that has been inserted into a document, while the **```<del>```** element can show text that has been deleted from it.

**```<s>```**

The **```<s>```** element indicates something that is no longer accurate or relevant (but that should not be deleted).

# Introducing CSS

**UNDERSTANDING CSS:** Thinking Inside the Box.

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

![css](class02\css.JPG)

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon

![css](class02\css2.JPG)

# JAVASCRIPT

*Basic Instructions*

**STATEMENTS**

A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

![js](class02\js.JPG)

**COMMENTS**

Write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.

![js](class02\js2.JPG)


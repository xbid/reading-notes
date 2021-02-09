# HTML Lists, CSS Boxes, JS Control Flow

# lists

![html lists](https://careerkarma.com/blog/wp-content/uploads/2020/02/HTML-LISTS.jpg)

- **Ordered lists** are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.

```<ol>```

The ordered list is created with the ```<ol>``` element.

```<li>```

Each item in the list is placed between an opening ```<li>``` tag and a closing ```</li>``` tag. (The listands for list item.)

- **Unordered lists** are lists that begin with a bullet point (rather than characters that indicate order).

```<ul>```

The unordered list is created with the ```<ul>``` element.

```<li>```

Each item in the list is placed between an opening ```<li>``` tag and a closing ```</li>``` tag. (The listands for list item.)Browsers indent lists by default

- **Definition lists** are made up of a set of terms along with the definitions for each of those terms.

```<dl>```

The definition list is created with the ```<dl>``` element and usually consists of a series of terms and their definitions.

Inside the ```<dl>``` element you will usually see pairs of ```<dt>``` and ```<dd>``` elements.

```<dt>```

This is used to contain the term being defined (the definition term).

```<dd>```

This is used to contain the definition.

**Nested Lists**

You can put a second list inside an ```<li>``` element to create a sub-list or nested list.

**Summary** *Lists*

- There are three types of HTML lists: ordered, unordered, and definition. 

- Ordered lists use numbers.

- Unordered lists use bullets.

- Definition lists are used to define terminology.

- Lists can be nested inside one another.

## CSS Box

![css](https://hackernoon.com/hn-images/1*mocAy3KRzjTs0Oc2mUz9Sg.jpeg)

You can set several properties that affect the appearance of these boxes. In this chapter you will see how to:Control the dimensions of your boxes

- Create borders around boxes

- Set margins and padding for boxes●

- Show and hide boxes

**Box Dimensions** width, height

**Limiting Width** min-width, max-width

**limiting height** min-height, max-height

**overflowing content** overflow

- hidden

This property simply hides any extra content that does not fit in the box.

- scroll

This property adds a scrollbar to the box so that users can scroll to see the missing content.

**Border, Margin & Padding**

Every box has three available properties that can be adjusted to control its appearance:

If you specify a width for a box, then the borders, margin, and padding are added to its width and height.

- 1. Border

Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

- 2. Margin

Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

- 3. Padding

Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

**White Space & Vertical Margin**

The padding and margin properties are very helpful in adding space between various items on the page.

**Summary** *Boxes*

- CSS treats each HTML element as if it has its own box. 

- You can use CSS to control the dimensions of a box.

- You can also control the borders, margin and padding for each box with CSS.

- It is possible to hide elements using the display and visibility properties.

- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.

- Legibility can be improved by controlling the width of boxes containing text and the leading.

- CSS3 has introduced the ability to create image Xborders and rounded borders.


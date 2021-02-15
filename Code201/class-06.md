# JS Object Literals; The DOM

![  ](https://res.cloudinary.com/practicaldev/image/fetch/s--fzU9Q772--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://thepracticaldev.s3.amazonaws.com/i/ern57e4pds7jpp9oq5xy.png)

Photo by [Cloudinary](https://res.cloudinary.com/practicaldev/image/fetch/s--fzU9Q772--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://thepracticaldev.s3.amazonaws.com/i/ern57e4pds7jpp9oq5xy.png)

## Understanding The Problem Domain *is The Hardest Part Of Programming*

What is the hardest thing about writing code?

- Learning a new technology

- Naming things

- Testing your code

- Debugging

- Fixing bugs

- Making software maintainable

and the list goes on and on.

But what is really hard about programming is learning the problem domain.

And if you want to see more about [Understanding The Problem Domain][1], I recommend this article it is really helpful.

[1]: https://dzone.com/articles/understanding-problem-domain "Dzone: Dom"

Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

### What can you do about it?

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

- 1. Make the problem domain easier.

- 2. Get better at understanding the problem domain.

You can often make the problem domain easier by **cutting out cases and narrowing your focus to a particular part of the problem.**

The meaning it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

The other choice is to become better at understanding problem domains.  As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time.

> **It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it.**  Make sure you understand a problem inside and out before you try and solve it with code. It is much more expensive and time consuming to do things over than it is to do them right the first time.

## Object Literals

### What is an object?

Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

### Creating an Object
*Literal Notation*

leteral notation is the easiest and most popular way to create objects.

![ ](class06\objects1.JPG)

### Accessing an object and dot notation

You access the properties or methods of an object using dot notation, you can also access properties using square brackets.

![ ](class06\objects2.JPG)

This notation is used most commonly when:

- The name of the property is a number. (but should be avoided)
- A varible is being used in place of the property name (you will see this technique later on).

## Document Object Model

The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

![ ](class06\dom1.JPG)

## Caching DOM Queries

Methods that find elements in the DOM tree are called DOM queries.

When you need to work with an element more than once ,you should use a variable to store the result of this query.

![ ](class06\dom2.JPG)

## Methods that select individual elements

get ElementById() and querySelector() can both search an entire document and return individual elements. Both use a similar syntex.

![ ](class06\dom3.JPG)

## Selecting An Element from a NodeList

There are two ways to select an element from a NodeList:

The item() method and array syntax.

Both require the index number of the element you want.

![ ](class06\dom4.JPG)

![ ](class06\dom5.JPG)

## Repeating actions for an entire nodelist

When you have a NodeList, you can loop through each collection and apply the same statements to each.

![ ](class06\dom6.JPG)

## Looping through a Nodelist: play by play

![ ](class06\dom7.JPG)

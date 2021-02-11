# HTML Images; CSS Color & Text

## Images

![  ](https://community-cdn-digitalocean-com.global.ssl.fastly.net/variants/N3xeBRWr2VvCKpvYPKwnP6jM/035575f2985fe451d86e717d73691e533a1a00545d7230900ed786341dc3c882)

Photo by [Fastly.com](https://community-cdn-digitalocean-com.global.ssl.fastly.net/variants/N3xeBRWr2VvCKpvYPKwnP6jM/035575f2985fe451d86e717d73691e533a1a00545d7230900ed786341dc3c882)

### Adding Images

```<img>```

To add an image into the page you need to use an ```<img>```element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:

*src*

This tells the browser where it can find the image file

*alt*

This provides a text description of the image which describes the image if you cannot see it.

*title*

You can also use the titleattribute with the ```<img>``` element to provide additional information about the image

as this example:

~~~
<img src="images/quokka.jpg" alt="A family of    quokka" title="The quokka is an Australian    marsupial that is similar in size to the    domestic cat." />
~~~

![  ](class05\fr1.JPG)

### Height & Width of Images

You will also often see an ```<img>```element use two other attributes that specify its size:

*height*

This specifies the height of the image in pixels.

*width*

This specifies the width of the image in pixels.

~~~
<img src="images/quokka.jpg" alt="A family of    quokka" width="600" height="450" />
~~~

![  ](class05\fr1.JPG)

### Where to place Images In Your Code

- 1: Before a paragraph.

- 2: Inside the start of a paragraph.

- 3: I  n the mIddle of a paragraph

~~~
<img src="images/bird.gif" alt="Bird" width="100"    height="100" />
<p>There are around 10,000 living species of birds    that inhabit different ecosystems from the    Arctic to the Antarctic. Many species undertake    long distance annual migrations, and many more    perform shorter irregular journeys.</p>
<hr />
<p><img src="images/bird.gif" alt="Bird" width="100" height="100" />
There are around 10,000 living    species of birds that inhabit different    ecosystems from the Arctic to the Antarctic. Many    species undertake long distance annual    migrations, and many more perform shorter    irregular journeys.</p>
<hr />
<p>There are around 10,000 living species of birds    that inhabit different ecosystems from the    Arctic to the Antarctic.
<img src="images/bird.gif" alt="Bird" width="100" height="100" />Many species undertake long    distance annual migrations, and many more perform    shorter irregular journeys.
</p>
~~~

### html5:Figure and Figure Capion

```<figure>```Images often come with captions. HTML5 has introduced a new ```<figure>``` element to contain images and their caption so that the two are associated.

```<figcaption>``` The ```<figcaption>``` element has been added to HTML5 in order to allow web page authors to add a caption to an image.

~~~
<figure>
  <img src="images/otters.jpg" alt="Photograph of  two sea otters floating in water">
  <br />
  <figcaption>Sea otters hold hands when they  sleep so they don't drift away from each  other.
  </figcaption>
</figure>
~~~

#### Summary Images

- The ```<img>``` element is used to add images to a web page.

- Always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.

- Save images at the size you will be using them on the web page and in the appropriate format.

- Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

## Color

### Foreground Color 
*color*

The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

**rgb values**

These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

**hex Codes**

These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80

**Color names**

There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

~~~
/* color name */
h1 {  
    color: DarkCyan;}
    
/* hex code */
h2 {
    color: #ee3e80;}
/* rgb value */
p {  
    color: rgb(100,100,90);}
~~~

![  ](class05\tw2.JPG)

### Background Color
*background-color*

CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

~~~
body {
  background-color: rgb(200,200,200);}
h1 {
  background-color: DarkCyan;}
h2 {
  background-color: #ee3e80;}
p {
  background-color: white;}
~~~

![  ](class05\tr3.JPG)

Understanding Color

Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.

![  ](class05\col.JPG)

![  ](class05\col1.JPG)

### Css3: opacity 
*opacity, rgba*

CSS3 introduces the opacityproperty which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5is 50% opacity and 0.15 is 15% opacity).

~~~
p.one {
  background-color: rgb(0,0,0);
  opacity: 0.5;}
p.two {
  background-color: rgb(0,0,0);
  background-color: rgba(0,0,0,0.5);}
~~~

![  ](class05\col2.JPG)

### Css3: 
*hsl Colors*

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.

![  ](class05\col3.JPG)

### Css3: hsl & hsla
*hsl, hsla*

The hsl color property has been introduced in CSS3 as an alternative way to specify colors. The value of the property starts with the letters hsl, followed by individual values inside parentheses for:

- hue

This is expressed as an angle (between 0 and 360 degrees)

- saturation

This is expressed as a percentage.

- lightness

This is expressed as a percentage with 0% being white, 50% being normal, and 100% being black

- alpha

This is expressed as a number between 0 and 1.0. For example, 0.5 represents 50% transparency, and 0.75represents 75% transparency

~~~
body {
    background-color: #C8C8C8;
    background-color: hsl(0,0%,78%);}
p {  
    background-color: #ffffff; 
    background-color: hsla(0,100%,100%,0.5);}
~~~

![  ](class05\tr3.JPG)

#### Summary
*Color*

- Color not only brings your site to life, but also helps convey the mood and evokes reactions.

- There are three ways to specify colors in CSS:            RGB values, hex codes, and color names.

- Color pickers can help you find the color you want.

- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).

- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.

- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.


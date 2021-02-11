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

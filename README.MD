> # SIGMA WEB DEVELOPMENT

    Client
    Browser
    Server

We Can use emmet ! for HTML boilerplate...

> CSS ----> For Styling...Give Beauty...
> Javascript ----> Brain ... For Functionality...

> # <mark>DAY-01</mark>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hello</title>
  </head>
  <body>
    Hey, I have started learning Sigma Web Development...
    <br />
    <video src="Motivation.mp4" controls></video>
  </body>
</html>
```

> # <mark> DAY-02</mark>

## HTML:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sigma Web Development</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    Hey, this is my first website....I love Learning Sigma WebDev...

    <script src="script.js"></script>
  </body>
</html>
```

## CSS :

```css
body {
  background-color: purple;
  color: white;
}
```

## JavaScript :

```js
alert("Welcome to Sigma Web Development Course");
```

> # <mark> Day-03:</mark>

## HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Used for SEO -->
    <meta name="description" content="" />
    <title>tittle of the page</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    content
    <script src="script.js"></script>
  </body>
</html>
```

## CSS :

```
body{
    background-color: red;
}
```

## JavaScript :

```
alert("Hello!")
```

> # <mark>Day-04</mark>

## HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Bookmarks -SRHridoy</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1>My Bookmarks - SRHridoy using h1</h1>
    <h2>Main Bookmarks - SRHridoy using h2</h2>
    <h3>Secondary Bookmarks - SRHridoy using h3</h3>
    <h4>Secondary Bookmarks - SRHridoy using h4</h4>
    <h5>Secondary Bookmarks - SRHridoy using h5</h5>
    <h6>Secondary Bookmarks - SRHridoy using h6</h6>

    <!-- p>lorem23 -->
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum debitis
      autem dolorem corrupti doloremque atque, quae minima ea, dolores
      distinctio amet nemo molestias!
    </p>
    <!-- Inline css used ...we avoid in Industry ...style p er ekta attibute ...An attribute gives a property of a tag or elements... -->
    <p style="background-color: thistle;">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis,
      dolorem!
    </p>
  </body>
</html>
```

## CSS :

```css
body {
  background-color: rgb(229, 125, 177);
}
```

> ## <mark>Bookmark Project</mark>

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bookmark Manager - SRHridoy</title>
  </head>

  <body>
    <h1>My Bookmarks</h1>
    <h2>Primary Bookmarks</h2>

    <p><a target="_blank" href="https://www.google.com">Open Google</a></p>
    <p><a target="_blank" href="https://www.facebook.com">Open Facebook</a></p>
    <p><a target="_blank" href="https://www.youtube.com">Open Youtube</a></p>

    <h2>Secondary Bookmarks</h2>
    <p><a href="https://chat.openai.com/chat">ChatGpt</a></p>
    <p><a href="https://quora.com">Quora</a></p>
  </body>
</html>
```

> # <mark>Day-05</mark>

## <mark>Image and Table Tag :</mark>

### HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Images</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <!-- <img width="230" src="train.jpg" alt="Train Image"> -->
    <!-- Height or width er jekono ekta dile arekta automatic fixed hoye jai ar egula pixel e hoi ar px ba kono kisu likha lage nah automatic hoi sudhu valu dilei hoi -->
    <img height="640" src="train.jpg" alt="Train Image" />
    <br />
    <!-- Tables : -->
    <table>
      <caption>
        Friend Details :
      </caption>
      <thead>
        <tr>
          <th>Name</th>
          <th>Designation</th>
          <th>Favourite Language</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>Hridoy</td>
          <td>Programmer</td>
          <td>JavaScript</td>
        </tr>

        <tr>
          <!-- Arnob ekhon 2 column er jaiga nibe -->
          <td colspan="2">Arnob</td>
          <!-- <td>Programmer</td> -->
          <!-- Python ekhon 2 ta row er jaiga nibe -->
          <td rowspan="2">Python</td>
        </tr>
        <tr>
          <!-- Ozaer ekhon 2 column er jaiga nibe -->
          <td colspan="2">Ozaer</td>
        </tr>
      </tbody>

      <tfoot>
        <tr>
          <td colspan="2">Robi</td>
          <td rowspan="2">Foot</td>
        </tr>
      </tfoot>
    </table>
  </body>
</html>
```

### CSS :

```css
td {
  border: 2px solid black;
}
```

## <mark> List Tag : </mark>

### HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>List</title>
  </head>
  <body>
    <h1>Unordered List :</h1>
    <ul>
      <li>Mango</li>
      <li>Banana</li>
      <li>Orange</li>
      <li>Water Milon</li>
      <li>Apple</li>
    </ul>
    <ul type="square">
      <li>Mango</li>
      <li>Banana</li>
      <li>Orange</li>
      <li>Water Milon</li>
      <li>Apple</li>
    </ul>
    <ul type="circle">
      <li>Mango</li>
      <li>Banana</li>
      <li>Orange</li>
      <li>Water Milon</li>
      <li>Apple</li>
    </ul>

    <h1>Ordered List :</h1>
    <ol>
      <li>Dog</li>
      <li>Cat</li>
      <li>Donkey</li>
    </ol>
    <ol type="I">
      <li>Dog</li>
      <li>Cat</li>
      <li>Donkey</li>
    </ol>
    <ol type="A">
      <li>Dog</li>
      <li>Cat</li>
      <li>Donkey</li>
    </ol>
    <ol type="a">
      <li>Dog</li>
      <li>Cat</li>
      <li>Donkey</li>
    </ol>
    <ol type="i">
      <li>Dog</li>
      <li>Cat</li>
      <li>Donkey</li>
    </ol>

    <h1>HTML Defination List</h1>
    <dl>
      <dt>HTML</dt>
      <dd>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique,
        assumenda?
      </dd>
    </dl>
    <dl>
      <dt>CSS</dt>
      <dd>
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugiat,
        aspernatur.
      </dd>
    </dl>
    <dl>
      <dt>JavaScript</dt>
      <dd>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Beatae, iure!
      </dd>
    </dl>
  </body>
</html>
```

> # <mark>Day-06</mark>

## SEO and Core Web Vitals in HTML:

```html
<!-- Core Web Vitals
        ---- CLS-Cumulative Layer Shift(CLS)
        ---- LCP-Largest Contextual Paint(2.5s er moddhe boro file load howa valo)
        ----FID(First Input Delay) input e tip dile kokhn e process hoi....100 miliseconds e standard...

        Lighthouse--- chrome er inspection e thake ar oikhan theke page er somossa thik kora jabe performance o jana jabe...
-->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="This is a page which description about Hridoy"
    />
    <title>About Hridoy</title>
  </head>
  <body>
    <h1>Hridoy</h1>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corrupti,
      architecto delectus voluptatibus maiores, officiis beatae voluptas a iusto
      placeat voluptatum qui labore ipsa provident impedit tempora suscipit,
      quisquam perspiciatis omnis. Rerum, facilis suscipit? Ad exercitationem,
      numquam dolorem dicta quibusdam in voluptate natus iure eos asperiores.
    </p>
  </body>
</html>
```

> # <mark>Day-07</mark>

## Forms :

### HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Forms - Lets learn</title>
  </head>

  <body>
    <!--get and post are method... Get request is simple and post request is complex etar madhoome boro boro data pathano hoi...-->
    <h1>Form to apply for Sigma Web Development Course - TA</h1>
    <form action="post">
      <div>
        <label for="username">Enter your Username :</label>
        <input
          type="text"
          id="username"
          name="username"
          placeholder="Enter your username"
          autofocus
        />
      </div>
      <!-- Radio -->
      <div>
        <!-- Ekhane 2 tar name e same tai at a time jekono ekta select hobe... -->
        <!-- Id er value laber er for e hobe...Er kaj holo label er vitorer text e tap korlei oita select hobe -->
        <input type="radio" name="gender" id="male" value="male" />
        <label for="male">Male</label>
        <input type="radio" name="gender" id="female" value="female" />
        <label for="female">Female</label>
      </div>
      <!-- CheckBox -->
      <div>
        <input
          type="checkbox"
          id="subscribe"
          name="subscribe"
          id="subscribe"
          value="yes"
        />
        <label for="subscribe">Subscribe to newsletter</label>
      </div>
      <!-- Text area -->
      <div>
        <label for="comment">Enter your comment:</label>
        <br />
        <!-- br is not recommended... -->
        <textarea name="comment" id="comment" cols="30" rows="10"></textarea>
      </div>
      <!-- Select Tag -->
      <div>
        <select name="fruits" id="fruits">
          <option value="apple">Apple</option>
          <option value="banana">Banana</option>
          <option value="orange">Orange</option>
        </select>
      </div>
    </form>
  </body>
</html>
```

> # Common Attributes:

## action

The action attribute specifies the URL where the form data should be sent after submission.

```html
<form action="/submit.php" method="POST"></form>
```

## method

The method attribute defines how data is sent. The two most common methods are GET and POST.

```html
<form action="/submit.php" method="POST"></form>
```

## name

The name attribute specifies the name for the form element, making it easier to reference in scripts or the server-side code.

```html
<input type="text" name="username" />
```

## placeholder

This attribute provides a hint to the user as to what can be entered in the field.

```html
<input type="text" placeholder="Enter your username" />
```

## required

The required attribute makes a field mandatory to fill out.

```html
<input type="text" required />
```

## autofocus

The autofocus attribute automatically focuses the cursor on the particular input when the page loads.

```html
<input type="text" autofocus />
```

> ## HTML5 Validation Attributes:

## required

As mentioned above, this attribute makes a field mandatory.

```html
<input type="text" required />
```

## pattern

The pattern attribute specifies a regular expression that the input must match to be valid.

```html
<input type="text" pattern="[a-zA-Z0-9]+" />
```

> # <mark>Day-08</mark>

## Inline & Block Elements in HTML :

### HTML :

```html
<!-- Inline Elements : Jototuk dorkar tototuk jaiga nei... -->
<!-- Block Elements : Pura Jaiga dokhol kore... -->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inline & Block Elements - HTML</title>
    <link rel="stylesheet" href="style.css" />
  </head>

  <body>
    <p>Hey, this is Paragraph tag...</p>
    <a href="https://google.com">Google</a>
    <div>I am Div and I am a block element...</div>
    <span>I am span and I am inline..</span>
    <a href="">Yes he is inline</a>
  </body>
</html>
```

```css
p {
  background-color: rgb(129, 223, 223);
}

a {
  background-color: rgb(255, 119, 0);
}

div {
  background-color: rgb(255, 247, 0);
}

span {
  background-color: pink;
}
```

> ## <mark> Block Elements (Most Commonly Used First) </mark>

```html
<div>: A generic container for flow content.
<p>: Paragraph.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Headings.
<ul>: Unordered list.
<ol>: Ordered list.
<li>: List item.
<form>: A section containing form controls.
<table>: Table.
<section>: A standalone section of a document.
<header>: A container for introductory content or a set of navigational links.
<footer>: Footer of a section or page.
<nav>: A section of a page that contains navigation links.
<article>: A self-contained composition in a document.
<aside>: A section of a page that contains information indirectly related to the main content.
<main>: The main content of a document.
<fieldset>: A set of form controls grouped under a common name.
<blockquote>: A block of text that is a quotation from another source.
<pre>: Preformatted text.
<canvas>: A container used to draw graphics via JavaScript.
<dl>: Description list.
<dt>: Term in a description list.
<dd>: Description in a description list.
<figure>: Any content that is referenced from the main content.
<figcaption>: A caption for a <figure> element.
<address>: Contact information for the author or owner of the document.
<hr>: A thematic break or a horizontal rule.
<tfoot>: Footer of a table.
```

> ## <mark> Inline Elements (Most Commonly Used First)</mark>

```html
<a
  >: Anchor or hyperlink. <img />: Image.
  <span
    >: Generic inline container. <input />: Input field.
    <label
      >: Label for a form element.
      <strong
        >: Strong emphasis.
        <em
          >: Emphasized text. <br />: Line break.
          <code
            >: Code snippet.
            <b
              >: Bold text.
              <i
                >: Italic text.
                <u
                  >: Underlined text.
                  <small
                    >: Smaller text.
                    <sub
                      >: Subscript.
                      <sup
                        >: Superscript.
                        <mark
                          >: Marked or highlighted text.
                          <q
                            >: Short inline quotation.
                            <cite
                              >: Citation.
                              <kbd
                                >: Keyboard input.
                                <samp
                                  >: Sample output.
                                  <var
                                    >: Variable in a mathematical expression or
                                    programming context.
                                    <time
                                      >: Time.
                                      <abbr
                                        >: Abbreviation.
                                        <data
                                          >: Machine-readable translation of
                                          content.
                                          <acronym
                                            >: Acronym (Not supported in
                                            HTML5).</acronym
                                          ></data
                                        ></abbr
                                      ></time
                                    ></var
                                  ></samp
                                ></kbd
                              ></cite
                            ></q
                          ></mark
                        ></sup
                      ></sub
                    ></small
                  ></u
                ></i
              ></b
            ></code
          ></em
        ></strong
      ></label
    ></span
  ></a
>
```

> ## <mark> Quick Quiz -01 : <mark>

```html
<!-- Quick Quiz 
Without using br tag, write a vertically aligned form asking for name, city and pincode of a user.
-->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Quik_Quiz_01</title>
  </head>

  <body>
    <form action="post">
      <div>
        <label for="name">Enter your name :</label>
        <div>
          <input type="text" name="name" id="name" />
        </div>
      </div>
      <div>
        <label for="city">Enter your city : </label>
        <div>
          <select name="city" id="city">
            <option value="Rajshahi">Rajshahi</option>
            <option value="Dhaka">Dhaka</option>
            <option value="Dinajpur">Dinajpur</option>
            <option value="Chattogram">Chattogram</option>
          </select>
        </div>
      </div>
      <div>
        <label for="pincode">Enter your pincode</label>
        <div>
          <input type="password" name="pincode" id="pincode" />
        </div>
        <div>
          <input type="submit" value="Sumbit" />
        </div>
      </div>
    </form>
  </body>
</html>
```

> # <mark>Day-09</mark>

## Id & Classes in HTML:

> ### ID:

```
An ID is an attribute, a unique identifier assigned to only one HTML element within a page. It is often used for unique styling and JavaScript manipulations.

Id linking eo kaj kore ...
```

> ### Class :
>
> '''
> Eta general. Ekta property oneker moddhe dite chaile tader class same hobe...
> '''

### HTML :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ID and Classes in HTML</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!-- same elements ke multiple class dite chaile ekta space dilei hobe...Kintu id ekjoner ektai and unique.... -->
    <!-- Id and class are attributes of elements -->

    <div id="firstDiv" class="red bg-yellow">firstDiv</div>
    <div id="secondDiv">secondDiv</div>

    <span class="red"></span>
  </body>
</html>
```

### CSS :

```css
/* class er jonne (.) use korte hoi...*/
.red {
  color: red;
}

.bg-yellow {
  background-color: yellowgreen;
}
/* id er jonne (#) use korte hoi... */
#firstDiv {
  background-color: yellow;
}

#secondDiv {
  background-color: green;
}
```

> # <mark>Day-10</mark>

## Video, Audio & Media in HTML:

### The <video> Tag

```html
<video src="video.mp4" controls></video>
```

### Attributes for <video> Tag:

1. src: Specifies the path to the video file.
2. controls: Adds video controls, like play, pause, and volume.
3. autoplay: Automatically starts playing the video when the page loads.
4. loop: Repeats the video once it ends.
5. muted: Mutes the video by default.
6. poster: Specifies an image to be displayed before the video starts playing.Like Thumbnail
7. width and height: Specifies the dimensions of the video.

### The <audio> Tag:

```html
<audio src="audio.mp3" controls></audio>
```

### Attributes for <audio> Tag:

1. src: Specifies the path to the audio file.
2. controls: Adds audio controls, like play, pause, and volume.
3. autoplay: Automatically starts playing the audio when the page loads.
4. loop: Repeats the audio once it ends.
5. muted: Mutes the audio by default.
6. preload: Specifies if and how the audio should be loaded when the page loads ('auto', 'metadata', 'none').

> The "preload" attribute can have the following values:

1. none: This is the default value. It indicates that the browser should not preload the audio file at all. The audio file will only start downloading when the user initiates playback.

2. metadata: This value tells the browser to preload only the metadata of the audio file, such as its duration and basic information about the audio. This can be useful if you want to display the audio duration to the user without fully loading the audio data.

3. auto: This value instructs the browser to preload the entire audio file as much as possible without delaying the loading of other important page content. The browser will try to load the audio file in the background so that it's ready to play when the user decides to start it.

## SVG in HTML:

### What is SVG?

`SVG stands for Scalable Vector Graphics. Unlike raster images like PNGs or JPGs, SVGs are not pixel-based. They're composed of vectors—mathematical formulas that describe shapes, paths, and fills. This means SVGs can be resized without losing quality.`

<!-- xmlns="http://www.w3.org/2000/svg"> -->

This is a solution for svg not found...

## iFrames in HTML:

### What is an iFrame?

An iFrame is an HTML element that enables an inline frame for the embedding of external content. Essentially, you can load another web page within a designated area of your current webpage.

### Basic Syntax:

```html
<iframe src="URL" width="width" height="height"></iframe>
```

## HTML of Todays's Class :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Video and Audio</title>
  </head>

  <body>
    <video
      src="Motivation.mp4"
      height="255"
      controls
      loop
      muted
      autoplay
      poster="train.jpg"
    ></video>

    <audio src="" controls autoplay loop muted></audio>
    <svg height="100" width="100">
      <circle
        cx="50"
        cy="50"
        r="40"
        stroke="black"
        stroke-width="3"
        fill="red"
      />
    </svg>
    <img src="img.svg" alt="my svg" />

    <iframe
      src="https://chat.openai.com/c/5190150a-0087-4b39-91a6-0f755358b970"
      width="322"
      height="444"
    ></iframe>

    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/XZwBNDGuWGU?si=-KZFKQeHXyhT6IHo&amp;start=786"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen
    ></iframe>
  </body>
</html>
```

> # <mark>Day-11</mark>

## Semantic Tags in HTML :

![Alt text](semantic-tags-1.png)
## What are Semantic Tags?

    Semantic tags add meaning to your HTML. They tell both the browser and the developer what kind of content is being presented.

Here are some of the key semantic tags you must know about:

1. <header>: Used to represent the top section of a web page, often containing headings, logos, and navigation.

2. <nav>: Signifies a navigation menu on a web page.

3. <article>: Indicates a self-contained piece of content, such as a blog post or news article.

4. <section>: Represents a thematic grouping of content on a web page.

5. <aside>: Typically used for sidebars or content that is tangentially related to the main content.

6. <footer>: Represents the footer of a web page, usually containing copyright information and contact details.

7. <figure> and <figcaption>: Used for embedding images, diagrams, or charts, along with a caption.

8. <main>: Signifies the main content area of a web page.

9. <time>: Used to represent time-related information, like dates and times.


### Why Use Semantic Tags?
  ```They enhance SEO, improve accessibility, and make your code easier to read and maintain.```


### Today's HTML Code : 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Tags</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Contact</li>
            </ul>
        </nav>
    </header>
    <main>

    </main>
        <h1>What are Semantic Tags</h1>
    <img src="semantic-tags.png" alt="This is semantic-tags">
    <footer>
        Copyright SR | All rights reserved
    </footer>
</body>
</html>
```


> # <mark>Day-14</mark>

## HTML : 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS</title>
    <style>
    /* here div is selector :*/
        /* div{
            color: red;
            background-color: yellow;
        } */
    /* Using multiple selectors:  */
        div,span{
            color: red;
            background-color: yellow;
        }
    </style>
</head>
<body>
    <div>
        Hey I am Hridoy and today I am in CSS Mood
    </div>
    <div>
        I am Good
    </div>
    <span>
        I am also Good...
    </span>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi deserunt cupiditate sapiente veritatis autem reiciendis!</p>
</body>
</html>
```


> # <mark>Day-15</mark>
## HTML : 

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline, Internal & External CSS</title>
    <!-- This is Internal CSS -->
    <!-- <style>
        h1{
            color: green;
            background-color: yellow;
        }
    </style> -->

    <!-- This is best and this is External CSS -->
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- This is inline CSS and it's not good -->
    <!-- <h1 style="color: green; background-color: yellow;">Three ways to add CSS to HTML</h1> -->
    <h1>Three ways to add CSS to HTML</h1>
    <div>
        <ol>
            <li>Inline CSS</li>
            <li>Internal CSS</li>
            <li>External CSS</li>
        </ol>
    </div>
    <p>Lorem ipsum dolor sit amet.</p>
</body>

</html>
```

## CSS : 
```css
h1 {
    color: green;
    background-color: yellow;
}

```

> # <mark>Day-17</mark>
## HTML : 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors MasterClass</title>
    <style>
        /* Element Selector */
        div{
            background-color: red;
        }
        /* Class Selector */
        .red{
            background-color: greenyellow;
        }
        /* ID Selector */
        #blue{
            background-color: blue
            ;
        }
        /* Child Selector ---> Direct Child hoba lagbe...*/
        div > p {
            background-color: yellow;
        }
        /* Descendant Selector ----> Direct Child na holeo hobe... */
        div p {
            background-color: palevioletred;
        }

        /* Universal Selector */
        *{
            background-color: black;
            color: white;
        }

        /* Pseudo Selector */
        a:visited{
            color: red;
        }
        a:link{
            color:greenyellow;
        }
        a:active{
            background-color: greenyellow;
        }

        a:hover{
            background-color: aqua;
        }
        P:first-child{
            background-color: yellow;
            color: black;
        }
    </style>
</head>
<body>
    <main class="one">
        <p>I am first in main</p>
        <p>I am second in main</p>
    </main>
    <div class="red">
        I am div...
    </div>
    <div>
        I am another div...
    </div>
    <div id = "blue">
        I am a another div...
        <p>I am Para Inside DIV...</p>
        <article>
            <p>
                I am from para which is in article and article is in div...
            </p>
        </article>
    </div>
    <a href="http://www.google.com">Google</a>
    <a href="http://www.facebook.com">Facebook</a>
</body>
</html>
```

> # <mark>Day-18</mark>

## CSS Box Model - Margin, Padding & Borders :

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Boxmodel</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .box {
            background-color: aqua;
        }

        /* Background color padding area te thake but margin area te thake nah... */
        /* Total Width = Width + Left Padding + Right Padding + Left Border + Right Border + Left Margin + Right Margin

        Total Height = Height + Top Padding + Bottom Padding +  Top Border + Bottom Border + Top Margin + Bottom Margin */
        .box1 {
            color: yellow;
            padding: 10px;
            margin: 35px;
            border: 2px solid blue;
            height: 200px;
            /* Boxsizing border-box dile mot height 200 orthat content and padding and border sob milai height 200....ar an dile sudhud content 200 height... */
            box-sizing: border-box;
        }

        .box2 {
            color: red;
            padding: 10px;
            /* Margin collapse : 2 ta box er margin alada hole jeta max seta hobe... */
            margin: 25px;
            border: 2px solid black;
            height: 200px;
            box-sizing: border-box;
        }
    </style>
</head>

<body>
    <div class="box box1">I am a box</div>
    <div class="box box2">I am another box</div>
</body>

</html>
```

> # <mark>Day-19</mark>

## CSS Fonts, Text & Color Properties :

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Fonts, Text & Color Properties </title>
    <style>
    /* External fonts */
        @import url('https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Poppins:wght@300&display=swap');
        h1{
            font-family: 'Poppins' 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            letter-spacing: 20px;
        }
        p{
            /* font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; */
            font-family: 'Baloo Bhai 2', sans-serif;
            font-size: 20px;
            /* line-height: 5; */
            /* font-style: oblique;
            font-weight: bolder; */
            /* text-decoration:underline; */
            /* text-decoration: overline; */
            /* Important link for fonts */
            /* https://codepen.io/web-dot-dev/pen/yLojraG  */
        }
        h2{
            text-align: center;
            text-transform:capitalize;
            text-decoration: underline;
            text-decoration-color: brown;
            /* text-decoration-style: wavy; */
            /* text-decoration-thickness: 4px; */
            /* text-indent: 45px; */
        }
        .lorem{
            border: 2px solid red;
            width: 145px;
            /* word-break: break-all; */
            /* text-overflow: clip;
            overflow: hidden; */
        }
    </style>
</head>
<body>
    <div>
        <h1>Fonts</h1>
        <h2>About Fonts:</h2>
        <p>This is paragraph...</p>
        <p class="lorem">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Commodi iste fugiat tempora quaerat molestiae! Minima molestiae odit dolorem, voluptas repellendus voluptatum cupiditate corrupti molestias atque quibusdam delectus, accusamus non culpa dolore fugiat iure voluptate, vel reprehenderit. Error cumque doloribus eligendi debitis quisquam, temporibus at dignissimos.</p>
    </div>
</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colors</title>
    <style>
        h1{
        /* https://codepen.io/web-dot-dev/pen/ZELGraM */
            /* color: darkred; */
            /* color: #08abcd; */
            /* color: rgb(255, 25, 0); */
            /* color: rgb(212, 37, 25, .12); */
            color: hsl(85, 100%, 50%);
            background-color: black;
        }
    </style>
</head>
<body>
    <h1>Let's learn about colors</h1>
    <p>
        Color can be represented in : 
        <ol>
            <li>Color Keywords</li>
            <li>Hex Color Code</li>
            <li>RBG</li>
            <li>RGBA</li>
            <li>HSL</li>
        </ol>
    </p>
</body>
</html>
```


> # <mark>Day-22</mark>
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>

        html{
            font-size: 12px;
        }
        *{
            margin: 0;
            padding: 0;
        }
        /* rem er jonne */
        .box{
            box-sizing: border-box;
            border: 2px solid black;
            /* width: 2048px; */
            width: 80vw;
            height: 10vh;
            /* Margin auto diye centre hoye jabe karon 80 vw ace ar block element hoilei hobe centre... */
            margin: auto;
            background-color: aquamarine;
        }

        .container{
            box-sizing: border-box;
            border: 2px solid black;
            width: 80vw;
            /* height: 80vh; */
            min-height: 80vh;
            /* min height adjust all the contents any lenght of text */
            margin: 23px auto;
            font-size: 18px;
            background-color: aquamarine;
        }
        .container p{
        /* Ja ace tar koto gun ta em dara bujhai */
            font-size: 2em;
            /* root  ja tar koto gun rem */
            /* font-size: 2rem; */

            /* Parent er 50% */
            border: 2px solid blue;
            width: 50%;
        }

        .mycont{
            border: 2px solid black;
            box-sizing: border-box;
            margin: 23px auto;
            color: red;
            font-size: 22px;
            width: 80vw;
        }
    </style>
</head>

<body>

    <div class="box">This is a box</div>
    <div class="container">
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consectetur esse quam, maxime eius ipsa, autem commodi omnis quia totam dolorem perferendis pariatur officia nobis voluptatem harum soluta reprehenderit illum ex beatae, ea optio praesentium voluptates? Tenetur labore voluptate voluptatem aspernatur eos quidem aut! Quam earum, nulla culpa quaerat saepe, voluptatem non ipsa voluptate adipisci modi asperiores.</p>
    </div>
    <dev class="mycont">
        I am another container...
    </dev>
</body>

</html>
```



> # <mark>Day-23</mark>
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Display Property</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .box {
            border: 2px solid blue;
            display: inline-block;
            width: 344px;
            padding:45px;
            margin: 34px; 
        }

        .box1{
            /* display: none; */
            /* visibility: hidden; */
        }
    </style>
</head>

<body>
    <!-- https://developer.mozilla.org/en-US/docs/Web/CSS/display -->
    <div class="box box1">
        I am a box
    </div>
    <div class="box">also a nice box</div>

    <span>I am a good</span>
    <span>boy</span>
</body>

</html>
```

> # <mark>Day-24</mark>
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Shadows and Outlines</title>
    <style>
        .box {
            border: 2px solid black;
            padding: 34px;
            box-shadow: 5px 15px 5px #70a711;
        }

        .text-element {
            text-shadow: 1px 4px 4px rgba(255, 2, 196, 0.903);
            outline: 2px solid black;
            border: 2px solid green;
            border-radius: 34px;
            outline-offset: 10px;
        }
    </style>
</head>

<body>
    <div class="box">
        I am a box
    </div>

    <p class="text-element">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatum architecto alias ducimus dolorum voluptatem
        optio consectetur. Sunt assumenda laboriosam quam molestiae laudantium vero nostrum iure, dolor, aliquam
        blanditiis ipsum eos reprehenderit! Hic, voluptas adipisci.
    </p>
</body>

</html>
```

> # <mark>Day-25</mark>
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Lists</title>
    <style>
        nav ul li{
            /* list-style: devanagari; */
            list-style: none;
            padding: 23px;
            background-color: yellow;
            list-style-position: inside;
            border: 2px solid black;
            /* list-style-image: url("https://images.pexels.com/photos/18686438/pexels-photo-18686438.jpeg?auto=compress&cs=tinysrgb&w=300&lazy=load"); */
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Contract</li>
        </ul>
    </nav>
</body>
</html>
```

> # <mark>Day-26</mark>
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Overflow property</title>
    <style>
        .box{
            width: 30vw;
            height: 10vw;
            border: 2px solid black;
            overflow: auto;
            /* overflow: hidden; */
            /* overflow: clip; */
            /* overflow-x: hidden;
            overflow-y: scroll; */
            overflow: scroll scroll;
            /* white-space: nowrap;
            text-overflow: ellipsis; */
        }
    </style>
</head>
<body>
    <div class="box">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae quod commodi culpa id fugiat, quam excepturi. Maiores porro obcaecati non corrupti cum! Tempore, saepe dignissimos tempora odio modi aut necessitatibus, reprehenderit eligendi quaerat animi magni temporibus nam esse aliquam libero debitis! Illum ducimus velit dolores.
    </div>
</body>
</html>
```

> # <mark>Day-27</mark>
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        p{
            background-color: blue;
            color: white;
        }

        div p:first-child{ 
            background-color: yellow;
            color: red;
        }
    </style>
</head>

<body>
    <!-- Write html and css code to style a paragraph inside a div which contains 5 other paragraphs. The first paragraph must have background color yellow and text color red. The other paragraphs must have background color blue and text color white. The HMTL is written below for your reference. Do not change this html -->
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita explicabo consectetur dicta fuga ea at
            vitae suscipit, repellendus illum deleniti laboriosam ipsa distinctio.</p>
        <p>I am another para</p>
        <p>I am also another para</p>
    </div>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita explicabo consectetur dicta fuga ea at
            vitae suscipit, repellendus illum deleniti laboriosam ipsa distinctio.</p>
        <p>I am another para</p>
        <p>I am also another para</p>
    </div>
</body>

</html>
```

> # <mark>Day-28</mark>

```html

```
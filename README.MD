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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello</title>
</head>
<body>
    Hey, I have started learning Sigma Web Development...
    <br>
    <video src="Motivation.mp4"controls></video>
</body>
</html>
```

> # <mark> DAY-02</mark>
## HTML:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sigma Web Development</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    Hey, this is my first website....I love Learning Sigma WebDev...

    <script src="script.js"></script>
</body>
</html>
```
## CSS : 
```css
body{
    background-color: purple;
    color: white;
}
```
## JavaScript : 
```js
alert("Welcome to Sigma Web Development Course")
```
> # <mark> Day-03:</mark>

## HTML :
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Used for SEO -->
    <meta name="description" content="">
    <title>tittle of the page</title>
    <link rel="stylesheet" href="style.css">
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

># <mark>Day-04</mark>

## HTML : 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Bookmarks -SRHridoy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>My Bookmarks - SRHridoy using h1</h1>
    <h2>Main Bookmarks - SRHridoy using h2</h2>
    <h3>Secondary Bookmarks - SRHridoy using h3</h3>
    <h4>Secondary Bookmarks - SRHridoy using h4</h4>
    <h5>Secondary Bookmarks - SRHridoy using h5</h5>
    <h6>Secondary Bookmarks - SRHridoy using h6</h6>

    <!-- p>lorem23 -->
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum debitis autem dolorem corrupti doloremque atque, quae minima ea, dolores distinctio amet nemo molestias!</p>
    <!-- Inline css used ...we avoid in Industry ...style p er ekta attibute ...An attribute gives a property of a tag or elements... -->
    <p style="background-color: thistle;">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis, dolorem!</p>
    
    
</body>
</html>
```

## CSS : 
```css
body{
    background-color: rgb(229, 125, 177);
}
```
> ## <mark>Bookmark Project</mark>

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bookmark Manager - SRHridoy</title>
</head>

<body>
    <h1>My Bookmarks</h1>
    <h2>Primary Bookmarks</h2>

    <p> <a target="_blank" href="https://www.google.com">Open Google</a></p>
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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- <img width="230" src="train.jpg" alt="Train Image"> -->
    <!-- Height or width er jekono ekta dile arekta automatic fixed hoye jai ar egula pixel e hoi ar px ba kono kisu likha lage nah automatic hoi sudhu valu dilei hoi -->
    <img height="640" src="train.jpg" alt="Train Image">
    <br>
    <!-- Tables : -->
    <table>
        <caption>Friend Details : </caption>
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
td{
    border: 2px solid black;
}
```

## <mark> List Tag : </mark>

### HTML : 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
    <ul type = "square">
        <li>Mango</li>
        <li>Banana</li>
        <li>Orange</li>
        <li>Water Milon</li>
        <li>Apple</li>
    </ul>
    <ul type = "circle">
        <li>Mango</li>
        <li>Banana</li>
        <li>Orange</li>
        <li>Water Milon</li>
        <li>Apple</li>
    </ul>
    
    <h1>Ordered List : </h1>
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
        <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique, assumenda?</dd>
    </dl>
    <dl>
        <dt>CSS</dt>
        <dd>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fugiat, aspernatur.</dd>
    </dl>
    <dl>
        <dt>JavaScript</dt>
        <dd>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Beatae, iure!</dd>
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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="This is a page which description about Hridoy">
    <title>About Hridoy</title>
</head>
<body>
    <h1>Hridoy</h1>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corrupti, architecto delectus voluptatibus maiores, officiis beatae voluptas a iusto placeat voluptatum qui labore ipsa provident impedit tempora suscipit, quisquam perspiciatis omnis. Rerum, facilis suscipit? Ad exercitationem, numquam dolorem dicta quibusdam in voluptate natus iure eos asperiores.</p>
</body>
</html>
```
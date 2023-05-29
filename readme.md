# HTML Forms: From Beginner to Pro

## Let's Code This form(Project -01) ->

![Alt text](Project-01/Event-Management-Form.png)


### Here is the HTML code for this:

``` html
 <h3>Event Registration:</h3>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">

        <br><br>

        <label for="emailID">Email:</label>
        <input type="email" id="emailID" name="emailID">

        <br><br>

        <label for="phoneID">Phone:</label>
        <input type="tel" name="phoneID" id="Phone">

        <br><br>

        <label for="occupationType">Occupation:</label>
        <select name="occupationType" id="occupationType">
            <option value="student">Student</option>
            <option value="professional">Professional</option>
            <option value="other">Other</option>
        </select>

        <fieldset>
            <legend>Topics of Interest</legend>
            <label for="checkbox1">HTML</label>
            <input type="checkbox" name="checkbox" id="checkbox1">


            <label for="checkbox2">CSS</label>
            <input type="checkbox" name="checkbox" id="checkbox2">

            <label for="checkbox3">JavaScript</label>
            <input type="checkbox" name="checkbox" id="checkbox3">

        </fieldset>

        <label for="textarea1">Comments:</label>
        <br>
        <textarea name="textarea1" id="textarea1" cols="30" rows="10"></textarea>

        <input type="submit" value="Register">


    </form>
```

## Let's Code another form(Project-02):

![Alt text](Project-02/Job-Application.png)

### Here is the HTML code for this :

```html
<h3>Job Application</h3>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">

        <br><br>

        <label for="emailID">Email:</label>
        <input type="email" id="emailID" name="emailID">

        <br><br>

        <label for="phoneID">Phone:</label>
        <input type="tel" name="phoneID" id="Phone">

        <br><br>

        <label for="fileUpload">Resume:</label>
        <input type="file" name="fileUpload" id="fileUpload">

        <br><br>
        
        <label for="exp">Experience(in years):</label>
        <input type="number" name="exp" id="exp" min="0" max="50">

        <br><br>

        <fieldset>
            <legend>Skills:</legend>
            <input type="checkbox" name="checkbox" id="checkbox1">
            <label for="checkbox1">HTML</label>


            <input type="checkbox" name="checkbox" id="checkbox2">
            <label for="checkbox2">CSS</label>

            <input type="checkbox" name="checkbox" id="checkbox3">
            <label for="checkbox3">JavaScript</label>
        </fieldset>

        <br><br>

        <label for="hEdu">Highet Education:</label>
        <select name="hEdu" id="hEdu">
            <option value="associate's degree">Associate's Degree</option>
            <option value="bachelor's degree">Bachelor's Degre</option>
            <option value="master's degree">Mastes's Degree</option>
            <option value="phd">PhD</option>
        </select>

        <br><br>

        <fieldset>
            <legend>Availablity:</legend>
            <!-- Here if we use same name then we can check only one one option otherwise all -->
            <label for="rd1">FUll-time</label>
            <input type="radio" name="rd" id="rd1">
            
            <br>

            <label for="rd2">Part-time</label><input type="radio" name="rd" id="rd2">
        </fieldset>

        <br>

        <label for="textarea1">Additional Comments:</label>
        <br>
        <textarea name="textarea1" id="textarea1" cols="30" rows="10"></textarea>
        <br>
        <input type="submit" value="Submit Application">
    </form>
```

## Let's Code a Complex Form (Project-03):

![Alt text](Project-03/Complex-Form.png)

### Here is the HTML code for this:

```html
<h2>Complex Form</h2>
    <form>
        <fieldset>
            <legend><strong>Personal Information</strong></legend>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" />

            <br /><br />

            <label for="emailID">Email:</label>
            <input type="email" id="emailID" name="emailID" />

            <br /><br />

            <label for="phoneID">Phone:</label>
            <input type="tel" name="phoneID" id="Phone" />

            <br /><br />

            <label for="dof">Date of Birth:</label>
            <input type="date" name="dof" id="dof">

            <br><br>

            <!-- We can easily use span here -->
            <p style="display: inline;">Gender:</p>

            <input type="radio" name="gender" id="male">
            <label for="male">Male</label>

            <input type="radio" name="gender" id="female">
            <label for="female">Female</label>

            <br><br>

            <label for="country">Country:</label>
            <select name="country" id="country">
                <option value="bangladesh">Bangladesh</option>
                <option value="india">India</option>
                <option value="us">USA</option>
                <option value="uk">Japan</option>
            </select>
        </fieldset>

        <br><br>

        <fieldset>
            <legend><strong>Address</strong></legend>

            <label for="street">Street:</label>
            <input type="text" name="street" id="street">

            <br><br>

            <label for="city">City:</label>
            <input type="text" name="city" id="city">

            <br><br>

            <label for="state">State:</label>
            <input type="text" name="state" id="state">

            <br><br>

            <label for="zipcode">Zip Code:</label>
            <input type="text" name="zipcode" id="zipcode">
        </fieldset>

        <br><br>

        <fieldset>
            <legend><strong>Other Information</strong></legend>

            <label for="textarea1">Comments:</label>
            <br>
            <textarea name="textarea1" id="textarea1" cols="30" rows="10"></textarea>

            <label for="terms">I agree to the terms of service:</label>
            <input type="checkbox" name="terms" id="terms">
        </fieldset>

        <br>

        <input type="submit" value="Submit">
    </form>
```
## Homework:

![Alt text](Homework/Homework-Form.png)

### Code ---->

```html
<h1>RannaBanna Login</h1>
    <form>

        <label for="username">Username:</label>
        <input type="text" name="username" id="username">

        <br><br>

        <label for="pass">Password:</label>
        <input type="password" name="pass" id="pass">

        <br><br>

        <label for="Location:">Location:</label>
        <input type="text" name="Location" id="Location">

        <br><br>

        <label for="mainfood">Main
            Food</label>
        <select name="mainfood" id="mainfood">
            <option value="">--Please choose an option--</option>
            <option value="Rice">Rice</option>
            <option value="Bread">Bread</option>
            <option value="Corn">Corn</option>
            <option value="Fish">Fish</option>
        </select>

        <br><br>

        <fieldset>
            <legend>Please Specify Your Role:</legend>

            <input type="radio" name="roles" id="fv">
            <label for="fv">Food Vlogger</label>

            <input type="radio" name="roles" id="Cook">
            <label for="Cook">Cook</label>

            <input type="radio" name="roles" id="assistant">
            <label for="assistant">Assistant</label>

            <input type="radio" name="roles" id="waiter">
            <label for="waiter">Waiter</label>
        </fieldset>

        <br><br>

        <fieldset>
            <legend>Do you have?</legend>

            <label for="mail">Email</label>
            <input type="checkbox" name="email" id="email">

            <br>

            <label for="fb">Facebook</label>
            <input type="checkbox" name="fb" id="fb">

            <br>

            <label for="whatsapp">WhatsApp</label>
            <input type="checkbox" name="whatsapp" id="whatsapp">

            <br><br>

            <input type="submit" value="Login">
            <input type="submit" value="Reset">
        </fieldset>
    </form>
```


# Project 1: HTML Resume Project || Complete Web Development Series 2023 || Episode - 10

## How to insert spaces/tabs in text using HTML/CSS?
     Regular space: &nbsp;
     Two spaces gap: &ensp;
     Four spaces gap: &emsp;

># How to add FAQS:

![Alt text](10_Project%201:%20HTML%20Resume%20Project%20%7C%7C%20Complete%20Web%20Development%20Series%202023%20%7C%7C%20Episode%20-%2010/Resume-Project_FAQs.png)

![Alt text](10_Project%201:%20HTML%20Resume%20Project%20%7C%7C%20Complete%20Web%20Development%20Series%202023%20%7C%7C%20Episode%20-%2010/FAQs.png)

```html
<section>
            <h2>Frequently Asked Questions: </h2>

            <details>
                <summary>What is Yout Name ?</summary>
                <p>My name is SRHridoy.</p>
            </details>

            <details>
                <summary>What is your favourite programming laguage></summary>
                <p>My favourite programming laguage is Python.</p>
            </details>

            <details>
                <summary>What is C?</summary>
                <p>C is a Structured Programming Language.</p>
            </details>

            <details>
                <summary>What is static?</summary>
                <p>static is a storage class.</p>
            </details>

        </section>
```

>>## Project -01:

![Alt text](10_Project%201:%20HTML%20Resume%20Project%20%7C%7C%20Complete%20Web%20Development%20Series%202023%20%7C%7C%20Episode%20-%2010/Resume-Project.png)


> Code For this project :

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume Project</title>
</head>

<body>
    <div>
        <div>
            <h1>Md. Sohanur Rahman Hridoy</h1>
            <p>Contact: <a href="mailto:sohanurrahmanhridoy007@gmail.com">sohanurrahmanhridoy007@gmail.com</a></p>
            <p>LinkedIn: <a
                    href="https://www.linkedin.com/in/md-sohanur-rahman-hridoy-2385ab257/">linkedin.com/in/md-sohanur-rahman-hridoy</a>
            </p>
            <p>github: <a href="https://github.com/SRHridoy">https://github.com/SRHridoy</a></p>
        </div>

        <table>
            <tr>
                <td>
                    <img src="profile.png" width="120px" alt="profile pic">
                </td>
                <td>
                    I am a passionate software engineer with ecpertise in problem-solving and algorithmic thinking.I
                    love to explore various techniologies and frameworks to devlop efficient and scable solutions. A
                    highly motivated and dedicated CSE undergraduate student seeking opportunities to apply my technical
                    knowledge and skills in a challenging industry environment. Committed to contributing to innovative
                    projects and leveraging my problem-solving abilities to drive technological advancements.
                </td>
            </tr>
        </table>

        <section>
            <h2>Education</h2>

            <ul>
                <li>Higher School Cirtificate
                    <br> &emsp; GPA: 5.00
                </li>

                <li>B.Sc.(Engineering) in CSE</li>
            </ul>

        </section>

        <section>
            <h2>Work Experience</h2>

        <div>
            <h3>Passionate Competittive Programmer</h3>
            <ul>
                <li>Solved Around 400+ Problems in Online Judges</li>
                <li>Give Contest at CODEFORCES in regular basis</li>
            </ul>
        </div>

        <div>
            <h3>Web Devloper</h3>
            <ul>
                <li>Developed and maintained web applications using HTML, CSS and JavaScript</li>
                <li>Collaborate with cross-functional teams to design and implement software solutions</li>
                <li>Optimize code performance and improved application efficiency</li>
            </ul>
        </div>
        </section>

        <section>
            <h2>Skills</h2>
            <ul>
                <li>C</li>
                <li>C++</li>
                <li>Python</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>SQL</li>
            </ul>
        </section>

        <section>
            <h>Achievements</h>
            <ul>
                <li>Participate in CSE FEST - 2k23</li>
                <li>Made a HSTU HAES website</li>
            </ul>
        </section>

        <section>
            <h2>Projects</h2>
            <ul>
                <li>
                    <h3>HSTU Alumni Employment Solution</h3>
                    <p>A Job Finding website for hstu alumni.</p>
                    <p>Hosted Link: <a href="abcd.com">hstu.com</a></p>
                    <p>Github Link: <a href="abc.com">github?hstu</a></p>
                </li>
                <li>
                    <h3>Friendly Chat App</h3>
                    <p>Friendly Chat - An android application making use of firebase, to help people connect and chat by sending messages and images also having login options.</p>
                    <p>Hosted Link: <a href="abcd.com">friendly.com</a></p>
                    <p>Github Link: <a href="abc.com">github.firiendly.com</a></p>
                </li>
                <li>
                    <h3>Secure Messenger AppSecure</h3>
                    <p>Secure Messenger App - An android application to have secure communication between the sender and recipient, using a number of cryptography algorithms like ASE, DES, RSA techniques for encryption and decryption.</p>
                    <p>Hosted Link: <a href="abcd.com">secureMessenger.com</a></p>
                    <p>Github Link: <a href="abc.com">github/secureMessage.com</a></p>
                </li>
            </ul>



        </section>

        <section>
            <h2>Frequently Asked Questions: </h2>

            <details>
                <summary>What is Yout Name ?</summary>
                <p>My name is SRHridoy.</p>
            </details>

            <details>
                <summary>What is your favourite programming laguage?</summary>
                <p>My favourite programming laguage is Python.</p>
            </details>

            <details>
                <summary>What is C?</summary>
                <p>C is a Structured Programming Language.</p>
            </details>

            <details>
                <summary>What is static?</summary>
                <p>static is a storage class.</p>
            </details>

        </section>

        <footer>
            <p>&copy; 2023 SRHridoy, All rights reserved.</p>
        </footer>

    </div>
</body>

</html>
```


## Homework Catalog Project :

![Alt text](10_Project%201:%20HTML%20Resume%20Project%20%7C%7C%20Complete%20Web%20Development%20Series%202023%20%7C%7C%20Episode%20-%2010/HomeWork/resources/HomeWork-Project.png)

>> Code for this Project :

```html
    <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=``, initial-scale=1.0">
    <title>HomeWork Project</title>
</head>

<body>
    <div>
        <section>
            <h1>Product Catalog</h1>
            <ul>
                <li><a href="#electronics">Electronics</a></li>
                <li><a href="#clothing">Clothing</a></li>
                <li><a href="#home">Home</a></li>
            </ul>
        </section>

        <section id="electronics">
            <h2>Electronics</h2>
            <section>
                <h3>Laptop</h3>
                <strong>Description:</strong>
                <span>High-Performance laptop with the latest processor and ample storage.</span>
                <br><br>
                <strong>Price: </strong>
                <span>$999.99</span>
                <br><br>
                <strong>Availability: </strong>
                <span>In Stock</span>
                <br><br>
                <img src="http://clipart-library.com/images_k/laptop-png-transparent/laptop-png-transparent-7.png"
                    width="200px" alt="laptop img">
                <br><br>
                <a href="www.details.com">View Details</a>
                <ul>
                    <li><strong>Brands:</strong>XYZ Electronics</li>
                    <li><strong>Screen Size:</strong> 15.6 inches</li>
                    <li><strong>RAM:</strong> 8GN</li>
                    <li><strong>Storage:</strong> 512GB SSD</li>
                </ul>
            </section>

            <br><br>

            <section>
                <h3>AntiquePhone</h3>
                <strong>Description:</strong>
                <span>Rare version of Nokia phone Nokia-1600</span>
                <br><br>
                <strong>Price: </strong>
                <span>$699.99</span>
                <br><br>
                <strong>Availability: </strong>
                <span>Out of Stock</span>
                <br><br>
                <img src="resources/product-500x500-1-removebg-preview.png" width="200px" alt="mobile img">
                <br><br>
                <a href="www.details.com">View Details</a>
                <ul>
                    <li><strong>Brands:</strong>Nokia</li>
                    <li><strong>Screen Size:</strong> 2 inches</li>
                    <li><strong>Camera: </strong>No</li>
                </ul>
            </section>
        </section>

        <section id="clothing">
            <h2>Clothing</h2>
            <section>
                <h3>T-Shirt</h3>
                <strong>Description:</strong>
                <span>Casual and comfortable t-shirt made from premium quality cotton.</span>
                <br><br>
                <strong>Price: </strong>
                <span>$19.99</span>
                <br><br>
                <strong>Availability: </strong>
                <span>In Stock</span>
                <br><br>
                <img src="https://static.vecteezy.com/system/resources/previews/008/847/318/original/isolated-black-t-shirt-front-free-png.png"
                    alt="t-shirt image" width="200px">
                <br><br>
                <a href="www.details.com">View Details</a>
                <ul>
                    <li><strong>Brand:</strong> Easy</li>
                    <li><strong>Color:</strong> Black, Cyan, Nevy Blue</li>
                    <li><strong>Size:</strong> S, M, L</li>
                    <li><strong>Material:</strong> 100% Cotton</li>
                </ul>
            </section>

            <br><br>

            <section>
                <h3>Jeans</h3>
                <strong>Description:</strong>
                <span>Classic jeans with a slim fit and stylish design.</span>
                <br><br>
                <strong>Price: </strong>
                <span>$49.99</span>
                <br><br>
                <strong>Availability: </strong>
                <span>In Stock</span>
                <br><br>
                <img src="https://www.pngmart.com/files/22/Jeans-PNG-Transparent.png" alt="jeans image" width="100px">
                <br><br>
                <a href="www.details.com">View Details</a>
                <ul>
                    <li><strong>Brand:</strong> Easy</li>
                    <li><strong>Color:</strong> Blue</li>
                    <li><strong>Size:</strong> 30, 32, 34</li>
                    <li><strong>Material:</strong> Denim</li>
                </ul>
            </section>

        </section>
        
        <br><br>

        <section id="home">
            <h2>Home</h2>
            <section>
                <h3>Table Lamp</h3>
                <strong>Description:</strong>
                <span>Modern and stylish table lamp to enhance your home decoration.</span>
                <br><br>
                <strong>Price: </strong>
                <span>$39.99</span>
                <br><br>
                <strong>Availability: </strong>
                <span>In Stock</span>
                <br><br>
                <img src="https://pngimg.com/d/lamp_PNG108688.png" alt="lamp image" width="100px">
                <br><br>
                <a href="www.details.com">View Details</a>
                <ul>
                    <li><strong>Brand:</strong> Home Essentials</li>
                    <li><strong>Color:</strong> White</li>
                    <li><strong>Dimension:</strong> 12 inches (height)</li>
                    <li><strong>Material:</strong> Ceramic, Metal</li>
                </ul>
            </section>

            <br><br>

            <section>
                <h3>Throw Pillow</h3>
                <strong>Description:</strong>
                <span>Soft and comfortable throw pillo for your living room or bedroom.</span>
                <br><br>
                <strong>Price: </strong>
                <span>$24.99</span>
                <br><br>
                <strong>Availability: </strong>
                <span>In Stock</span>
                <br><br>
                <img src="resources/pngimg.com - pillow_PNG103028.png" width="150px" alt="pilow imag">
                <br><br>
                <a href="www.details.com">View Details</a>
                <ul>
                    <li><strong>Brand:</strong> Home Essentials</li>
                    <li><strong>Color:</strong> Multiple</li>
                    <li><strong>Dimension:</strong> 18 x 18 inches</li>
                    <li><strong>Material:</strong> Cotton, Polyster</li>
                </ul>
            </section>
        </section>

        <footer>
            <p>© 2023 Product Catalaog. All rights reserved.</p>
        </footer>

    </div>
</body>

</html>
```
<br><br>

># Project 2: HTML Media Project || Media tags, Modern HTML and iframes || Episode - 11

<br>

## Media in HTML:
1. Image
2. Audio
3. Video

>### Inserting Images :
```html
<img src="resources/channel logo.jpg" alt="logo" height="50px" loading="lazy">
```
<br>

**What **is Easy Loading?****
Lazy loading is a strategy to identify resources as non-blocking (non-critical) and load these only when needed.

<br>

>## Inserting Audios :

```html
<audio src="resources/Real-Estate.mp3"></audio>
```
***But this doesn't work if we don't give control attribute***
```html
<audio src="resources/Real-Estate.mp3" controls></audio>
```

<br>

>### Another Method:

```html
<audio controls>
        <source src="resources/Real-Estate.mp3" type="audio/mp3">
</audio>
```

<br><br>

>## Inserting Video :
```html
<audio controls>
        <source src="resources/Real-Estate.mp3" type="audio/mp3">
</audio>
```

>### Another Method : 

``` html
<video controls height="500px">
        <source src="resources/ Intro Video.mp4" type="video/mp4">
</video>
``` 

<br> <br>

>## iframe: The Inline Frame element
        An HTML iframe is used to display a web page within a web page.

>### Adding my another html project to this html file :

```html
<iframe src="/10_Project 1: HTML Resume Project || Complete Web Development Series 2023 || Episode - 10/index.html" width="800px" height="720px"></iframe>
```
<br>

>### Adding a map on my page : 

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3595.1734628269196!2d88.65360114047354!3d25.69868017748577!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39e4ad0b5d200fa7%3A0x2e0c8f8bb049efa2!2sHajee%20Mohammad%20Danesh%20Science%20%26%20Technology%20University!5e0!3m2!1sen!2sbd!4v1685549697407!5m2!1sen!2sbd" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```
I copy the upper inframe code from Google Maps and share embedded HTML.

In the same way, we can embed youtube videos from the youtube share embed link: 

```html
<iframe src="https://www.youtube.com/embed/dw6vREeeTXE" width="560" height="315" allowfullscreen></iframe>
```

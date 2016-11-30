<pre>
This is the reference Document for HTML Workshop conducted in KSRM College Of Engineering
Author : Kunchala Anil
Email : anilkunchalaece@gmail.com
</pre>
**<p align="center"> HTML Introduction</p>**
What is HTML ? <br>
HTML [HYPER TEXT MARKUP LANGUAGE] is language for Specifying how text and graphics appear on the webpage
<br>

**Your First Webpage** <br>
Open your favourate Text editor and type <br>
```
Hello World
```
and save it as <em>helloWorld<strong>.html</strong></em> <br>
Dont forget the .html extension

and open the Doument with firefox or chrome. it will display something like This
![helloWorld Output](docImages/helloWorld.png)

Well.. eventhough browser able to render it without proper markup <br>
Before moving on we need to understand how browser understand input file
<br>
go to the developer console by **pressing F12**
then you can see something like This
![helloWorld Debug Console](docImages/helloWorldF12.png)

if you see clearly you can see that.. eventhough you didnt added any markup...<br>
Web browser addded it for you.. it is quite forgiving sometimes....

**<p align="center"> Simple HTML Document </p> **
So.. the proper form of html Document is
```html
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    Hello World
  </body>
</html>
```

Now you are wondering what are those weird angular brackets with names in it..

from MDN
>HTML is not a programming language; it is a markup language, >and is used to tell your browser how to display the webpages you visit
 HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way

If to Explain:

```
    The <html> element is the root element of an HTML page
    The <head> element contains meta information about the document
    The <body> element contains the visible page content
and The <!DOCTYPE html> declaration defines this document to be HTML5

```

so whatever we wanted to display in the **webpage** we need to put into the **body element**. And whatever the browser required to _understand our webpage_ it goes to the _Head Element_.

By the End of Workshop we are going to created three Three Webpages
those are

![IndexPage](docImages/index.png)
<p> page 1 : Index Page </p>
<br>
![loginPage](docImages/loginPage.png)
<p> page 2 : Login Page </p>
<br>
![testPage](docImages/testPage.png)
<p> page 3 : Test Page </p>
<br>

Ok.. We are gonna Implement them Step by Step <br>

So If we look at the Index Page <br>
In the webpage some text is displaying.. so lets modify the helloworld example to disply the first two lines.

```html
<!-- ex1.html -->
<html>
  <head>
  </head>
<body>
Online Examination

This is a simple online Examination interface Developed By Kunchala Anil Working in KSRM College Of Engineering as a part of the HTML Workshop on 7 Dec 2016.
</body>
```
The output is
![ex1.html output](docImages/ex1.png)
</p>
So eventhough we put space in the Code.. The Browser didn't display it like that.. so it is unable to understand what we are trying to say to it....
</p>

</p>
To ask browser properly to display them seperately we need to use a paragragh **tag** denoted by _p_


</p>

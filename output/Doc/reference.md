<pre>
This is the reference Document for HTML Workshop conducted in KSRM College Of Engineering
Author : Kunchala Anil
Email : anilkunchalaece@gmail.com
</pre>
<center> **HTML Introduction**</center>
What is HTML ? <br>
HTML [HYPER TEXT MARKUP LANGUAGE] is language for Specifying how text and graphics appear on the webpage
<br>

**Your First Webpage** <br>
<p>
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
Web browser addded it for you..

<center> **simple HTML Document** </center>
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

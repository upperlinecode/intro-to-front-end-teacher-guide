# Welcome to the World of Web Development!


## Motivation (i.e. What is this, and why should you care?)

In this mini-lab you will be learning the basics of HTML--and creating your very first web page!
HTML is the language of the web--every time you load a web page you are loading a long page of HTML code, and being able to write and understand HTML is the very first step in becoming a real developer.
Not only that, but HTML is here to stay. You've probably head about a lot of computer languages, but HTML has been **the** language of the web for the last ~25 years, and it's not going anywhere.

The pages you make in this activity will seem very basic, but if you master the skills it covers, you can go on to create amazing things. Happy coding!

## Directions

Follow the steps below in order, and be sure to read the descriptions of each step so that you know the purpose of each line of code you will be adding. Additionally, ***avoid copying and pasting***; sure, copying and pasting will speed things up, but when you take the time to write the line of code out by yourself you will better engrain it in your memory.  

-----------------



### Step one--tell the web browser that you're about to give it a bunch of HTML.

Ready to write your first line of HTML? The **very** first tag you will need to write is one that should be at the top of **every** page--the `<!DOCTYPE html>` tag. This tag doesn't appear to do much, but
it tells your browser that the rest of text that is about to follow is apart of an HTML document. If you leave it out, some browsers won't 'know' what type of document they are looking at (computers are dumb), and the page will break. It's a little boring, but you should have it.

**Add** `<!DOCTYPE html>` **at the very top of your page.**


### Step two--Add the 'root' element.

All HTML elements come into existence by writing 'tags.' Tags have an opening tag surrounded by angle brackets (e.g. `<tag>`) and a closing tag that has a slash after the first bracket (e.g. `</tag>`).
The most basic HTML tags are simply `<html>` and `</html>`, and **all the content of your pages will be written inside these tags.**


** Add the `<html>` tags to your page. Your code should look like the code below: **

```
<!DOCTYPE html>
<html>
</html>
```

### Step Three-- Add the `<body>` and `<head>` tags inside the html element.

On the good stuff. Inside your  `<html>` tags, add  `<head>` tags, and then after the head tags, add `<body>` tags--and remember that every tag also needs a closing tag.

+ The `<head>` contains information *about* your website, but not actual content that will show up on the page (think of it as the 'brains' of your webpage.) It will contain things like the title of your page --later on--links to stylesheets and code that will make your page beautiful and interactive.
+ The `<body>` contains all the content of your page that will actually show up on the screen. 90% of the HTML you write will go inside the `<head>`

At this point, it's good to make sure that your code is still 'clean' and readable. To show that the  `<body>` and `<head>` tags are ***inside*** the html tags, press `TAB` to indent them over like you would a paragraph. Look at the three examples below.


<table>
  <tr>
    <th> Gross :scream: </th>
    <th> Still needs work--tags are not indented :confused: </th>
    <th> Go work at google! :heart_eyes: </th>
  </tr>
  <tr>
    <td>  &lt;!DOCTYPE html&gt; &lt;html&gt;&lt;head&gt;&lt;body&gt;&lt;/body&gt;&lt;/html&gt; </td>
    <td>  
      &lt;!DOCTYPE html&gt;

      <br>
      &lt;html&gt;

      <br>
      &lt;head&gt;&lt;/head&gt;

      <br>  
      &lt;body&gt;&lt;/body&gt;

      <br>
      &lt;/html&gt;  

    </td>
    <td>  
      &lt;!DOCTYPE html&gt;
      <br>
      &lt;html&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;head&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;/head&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;body&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;/body&gt;
      <br>
      &lt;/html&gt;  
    </td>
  </tr>
</table>



## Step Four--Add content and experiment to create a hobby page.

At this point, you're ready to add content to your first web page! For starters, just try typing text in side the body of your page. If your tags are written correctly, it should show up! For this first project, your task to to create a **hobby** page that explains something your like to, or just something you happen to know a lot about.  

The `<head>` element, however, is different--any information here is information for the web browser about the page (a.k.a "metadata")--but it's **not** the content itself. One clear example is the `<title>` tag, which will give your page a title on the tab of the browser; Try giving your page a title by adding a title inside the head now:

```
<!DOCTYPE html>
<html>
  <head>
    <title> Painting Murals of Koalas: A How to Guide </title>
  </head>
  <body>
  </body>
</html>
```

If we want, we could just type text into the `<body>` element of the page, but that's not ideal--let's add some HTML elements to keep our content organized.

Experiment with the following tags by adding them inside the body of your html document! what do each of them do? What do you think they stand for?
+ `<h1> This text is big and bold! Like my paintings of koalas. </h1>`
+ `<h2> What about this text? </h2>`
+ `<h3> And what about this text?? </h3>`
+ `<p> What do you think p stands for? Here I will write a paragraph about the various things I find interesting about Koalas.  </p>`
+ `<span>Think you can figure out how the SPAN tag is different from the P tag???  Try putting multiple of each to see the difference. </span>`
+ `<div> The DIV tag exists to make a "divider" to keep your page organized, but you'll be surprised at how often you'll end up using it </div>`
+ This next tag closes itself (note the slash right at the end of the tag) and it doesn't have anything that goes inside it: `<hr />`
+ Same here: `<br />`

### Challenge 1: Make a bulleted list.

A bulleted, or 'unordered', list, is a very common HTML element, and to make one you need to both  `<ul>` ... `</ul>` tags to define where your list starts and ends, as well as `<li>...</li>` tags that determine what the actual items on your list are. Copy the list below and 'hack' it to change the items of your list and add some more items. 

```
<h3> Things I like about Koalas </h3>
<ul>
  <li> They're fuzzy </li>
  <li> They're vegetarian </li>
  <li> They're grumpy </li>
</ul>
```

### Challenge 2: Tables

Looking for challenge: how do you make a table in HTML?

Go to [this link about tables in HTML](https://www.tutorialspoint.com/html/html_tables.htm) and see if you can make a table out of html.


----------------
---------------
# Mini-Lab Part II: HTML Attributes.

### The Image tag

Some tags require extra information, or **attributes** to accomplish their purpose. The image tag, for instance, needs a **source**, abbreviated as 'src' to direct the web browser where to get the image. To get the source of an image, find any image online, and right/alt click it and select "copy source," which will be in the form of a long url (e.g. "http://thecatapi.com/api/images/get?format=src&type=gif")

try adding `<img src="http://thecatapi.com/api/images/get?format=src&type=gif" />` to your page. You can add all sorts of images! Try experimenting!


### Linking to other pages.

The `<a>` tag allows you to link to other pages, both on the web, and on your own. The `href` attribute specifies where the link will take you, and the text inbetween the opening and closing tag is what the user sees.
+ Try adding `<a href="http://www.google.com/"> Go to Google! </a>  ` To your page!

If you're linking to the pages on your own site, you won't need to type out the whole "http://www.example..."; you only need to type to file name of the document you're linking to. Try it out!
+ First, create a separate file in your folder, and be sure to make sure the name ends in .html, for example `page-two.html`
+ Add the basic `<!DOCTYPE html>, <html>, <head>, and <body>` tags to your site, as well as some basic text or other content in your second page.
+ Create an a tag that links to your other page! For example: `<a href="page-two.html"> Go to page two! </a>`

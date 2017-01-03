# Welcome to the World of Web Development!


## Motivation (i.e. What is this, and why should you care?)

In this mini-lab you will be learning the basics of HTML--and creating your very first web page!
HTML is the language of the web--every time you load a web page you are loading a long page of HTML code, and being able to write and understand HTML is the very first step in becoming a real developer.
Not only that, but HTML is here to stay. You've probably head about a lot of computer languages, but HTML has been **the** language of the web for the last ~25 years, and it's not going anywhere.

The pages you make in this activity will seem very basic, but if you master the skills it covers, you can go on to create amazing things. Happy coding!

## Directions

Follow the steps below in order, and be sure to read the descriptions of each step so that you know the purpose of each line of code you will be adding. Additionally, ***avoid copying and pasting***; sure, copying and pasting will speed things up, but when you take the time to write the line of code out by yourself you will better engrain it in your memory.  

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

On the good stuff. Inside your  `<html>` tags, add  `<head>` tags, and then after the head tags, add `<body>` tags--and remember that every tag also needs a closing tag. At this point, it's good to make sure that your code is still 'clean' and readable. To show that the  `<body>` and `<head>` tags are ***inside*** the html tags, press `TAB` to indent them over like you would a paragraph. Look at the three examples below.


<table>
  <tr>
    <th> Gross :scream: </th>
    <th> Still needs work :confused: </th>
    <th> Go work at google! :heart_eyes: </th>
  </tr>
  <tr>
    <td>  &lt;!DOCTYPE html&gt; &lt;html&gt;&lt;head&gt;&lt;body&gt;&lt;/body&gt;&lt;/html&gt; </td>
    <td>  
      &lt;!DOCTYPE html&gt;
      &lt;html&gt;
      &lt;head&gt;
      &lt;body&gt;
      &lt;/body&gt;
      &lt;/html&gt;  
    </td>
    <td>  &lt;!DOCTYPE html&gt;&lt;html&gt;&lt;head&gt;&lt;body&gt;&lt;/body&gt;&lt;/html&gt;  </td>
  </tr>
</table>

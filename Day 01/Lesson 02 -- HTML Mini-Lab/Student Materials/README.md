# HTML Mini-Lab: Write Clean Code Across Multiple pages

## Motivation (i.e. What is this, and why should you care?)

As you become a proficient web developer, you will end up writing some *very* complex web pages, perhaps with 100s of html elements each. The more complicated your web pages get, the more important it will become to keep your code organized and easy to work with. This mini-lab will help you to write better code that will make your life easier and give you a better understanding of the html code you will encounter as a web developer.

In Part-2, you will work on writing functioning links, a crucial skill in the web. Afterall, what is the web without links!?

[Part 1](https://github.com/upperlinecode/intro-to-front-end-teacher-guide/tree/master/Day%2001/Lesson%2002%20--%20HTML%20Mini-Lab/Student%20Materials#part-1-code-unscramble)

[Part 2](https://github.com/upperlinecode/intro-to-front-end-teacher-guide/tree/master/Day%2001/Lesson%2002%20--%20HTML%20Mini-Lab/Student%20Materials#part-2-links)


-------------------------------
# Part 1: Code Unscramble

**Directions:** In Step 1, you will see three comparisons of good and bad code--look them over carefully before moving on to step 2.


### Step 1: Look at good code examples--what do you notice about them?  

#### Example 1: Always close your tags where the element should end!
<table>
  <tr>
    <th> Tags don't close--bad! :scream: </th>
    <th> BEAUTIFUL! :heart_eyes: </th>
  </tr>
  <tr>
    <td>
      &lt;p&gt; This is a paragraph.
      &lt;p&gt;  This is a different paragraph.
    </td>

    <td>
      &lt;p&gt; This is paragraph. &lt;/p&gt;
      <br>
      &lt;p&gt;  This is a different paragraph.   &lt;/p&gt;
    </td>
  </tr>
</table>


#### Example 2: "child" elements should always be indented from their parent.
An element that contains another element is the "Parent" to the "child" element it contains. Child elements should always be indented away from their parent to clearly show that they are a child element.
As you will frequently have elements within elements within elements, make sure to indent every time you add a layer to clearly show what each element contains.

<table>
  <tr>
    <th> No indentation--Gross! :scream: </th>
    <th> BEAUTIFUL! :heart_eyes: </th>
  </tr>
  <tr>
    <td>
      &lt;article&gt;
      <br>
      &lt;section&gt;  
      <br>
      &lt;p&gt; This is a paragraph 1 inside the first section.  &lt;/p&gt;
      <br>
      &lt;p&gt; This is paragraph 2 inside the first section.  &lt;/p&gt;
      <br>
      &lt;/section&gt;
      <br>
      &lt;section&gt;  
      <br>
      &lt;p&gt; This is paragraph 1 inside the first section.  &lt;/p&gt;
      <br>
      &lt;p&gt; This is paragraph 2 inside the first section.  &lt;/p&gt;
      <br>
      &lt;/section&gt;
      <br>&lt;/article&gt;
    </td>

    <td>
      &lt;article&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;section&gt;  
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;p&gt; This is paragraph 1 inside the first section.  &lt;/p&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;p&gt; This is paragrah  2 inside the first section.  &lt;/p&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;/section&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;section&gt;  
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;p&gt; This is a paragraph 1inside the second section.  &lt;/p&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;p&gt; This is a paragraph 2 inside the second section.  &lt;/p&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;/section&gt;
      <br>&lt;/article&gt;
    </td>
  </tr>
</table>



#### Example 3: If a parent-child combo is really short, it's better to write it all the same line.
In general, if an element has a child element, you should 1. Put the child element on a new line, and 2. Be sure to indent the new line over.

If the parent-child combo is really short, however, save yourself some extra lines and write it all on the same line.

<table>
  <tr>
    <th> Totally OK, but a little unnecessary :expressionless:</th>
    <th> Pro :squirrel: </th>
  </tr>
  <tr>
    <td>
      &lt;div&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;a&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;img src="cat.gif" /&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt; /a&gt;
      <br>
      &lt;/div&gt;
    </td>

    <td>
      &lt;div&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;a&gt;  &lt;img src="cat.gif" /&gt;     &lt;/a&gt;
      <br>
      &lt;/div&gt;
    </td>
  </tr>
</table>

## Step 2: Your mission....

In the folder, you should find '**unscramble-basic.html**'.

Technically, it's valid HTML, but it's nearly impossible to make sense of--what elements are in what??

Your mission is to organize the HTML by properly indenting it so it's structure its clear to read and every child is indented away from its parent.

***ready for a challenge???***

Open the file "unscramble-challenge.html" and see if you can handle a *real* mess--this file goes a little over the top in showing how much a pain poorly formatted code can be.
You'll see all sorts of unfamiliar elements, but feel free to explore and google new things you haven't seen before!


<br><br>
-------------------------------------
# Part 2: Links

You have been hired as a freelance developer for Upperline's new website, but the site is a total mess. For one, there's hardly any content of the site, but more importantly, none of the links work!

### Step 1: Fix the broken in-page links.

When you load the homepage, you'll see a number of a broken links written within `<a>` tags.
+ Some are broken because the `<a>` tags are missing `href=""` attributes
+ Some are broken because event though the `<a>` tags are fine, the elements they're supposed to be linking to are missing `id=""` attributes.


***key points to remember***

1. Make any element on the page 'findable' by giving it an id.

For example: `<div id="thingy"> Link to this div plz!! </div>` .

2. Make a link to that element by using an `<a>` tag with an **href** value of a hashtag followed by the id of the thing you're linking to.

**Example of an in-page link.**
```
<div id="thingy"> This is the thingy!! <div>
<a href="#thingy"> Click here to up the thingy! </a>

```

### Step Two: add a new link!

Now that you've fixed all the existing `<a>` tags, create a new section--copy code, if you'd like, or write one from scratch--and link to from within the `<nav>` section like the other links.


### Step Three: At the botttom of the page, add a link to the top of the page.

If you give an `<a>` tag an href attribute of just "#", it will link to the very top of the page.

Add some new div or section at the bottom of your page, and within it, add an `<a href="#"> Go to the top </a>` link that will link you up to the top of the page.

### Step Four: Link to Page Two.

The author of this page was starting to write a second page, which she made in a file called "page2.html", but there's no way to get to it!

+ Somewhere on the homepage, add a link to the second page by creating a link with `href="page2.html"`
+ Once you can navigate to page two, add a link back to the homepage on page 2.

### Step Five: Add More Pages!

Now that you have a homepage and a page 2 which you can navigate back and forth from, make some more pages!
+ To create a new page, make a new file in your project folder, and be sure to end its filename in **.html**. For example, `page3.html`
+ Add some HTML content to your new page, and make sure the user has a way to get to it from the homepage. If you'd like, you can copy and page the HTML from "page2.hmtl" to give you a starting point, but if you write your own, make sure to include all the HTML basics (`<!DOCTYPE html>, <html>, <head>, <title> and <body>`)


### In the remainder of the time, add content to your pages!

Now that you have functioning links, put your HTML skills to the test by adding new content!

Here's a review of some of the HTML elements we've covered so far. If you'd like to see an example of them at work, just google the element. For example, if you want to learn more about the `<h3>` element, google "HTML h3 element"

List of HTML elements to use
+ `<img>`
+ `<a>`
+ `<div>`
+ `<p>`
+ `<ul>` and it's pal `<li>`. Google "html unordered list" if you need to see an example!
+ h1, h2, h3, etc.
+ `<title>` --- remember that the `<title>` tag goes in the head, not the body!!!
+ "Semantic" (has-meaning) tags that don't add styling but help to organize your code: `<section>`, `<article>`, `<nav>`,  `<header>`, `<header>`, `<footer>`, `<details>`

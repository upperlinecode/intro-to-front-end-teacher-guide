# HTML Mini-Lab: Write Clean Code Across Multiple pages

**[Part 1](#Part_1:_Code Unscramble:)**
**[Part 2](#Part 2: Links)**

## Motivation (i.e. What is this, and why should you care?)


# Part 1: Code Unscramble:
-------------------------------


As you become a proficient web developer, you will end up writing some *very* complex web pages, perhaps with 100s of html elements each. The more complicated your web pages get, the more important it will become to keep your code organized and easy to work with. This mini-lab will help you to write better code that will make your life easier and give you a better understanding of the html code you will encounter as a web developer.


### Step 1: Look at good code examples--what do you notice about them?  

#### Example 1: Always close your tags where the element should end. !
<table>
  <tr>
    <th> BAD! :scream: </th>
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
    <th> No indent --BAD! :scream: </th>
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
      &lt;a&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;img src="cat.gif" /&gt;
      <br>
      &lt; /a&gt;
    </td>

    <td>
      &lt;a&gt; &#160;&#160;&#160;&#160;&#160;    &lt;img src="cat.gif" /&gt;     &lt;/a&gt;
    </td>
  </tr>
</table>

## Your mission....

In the folder, you should find 'unscramble-basic.html'.

Technically, it's valid HTML, but it's nearly impossible to make sense of--what elements are in what??

Your mission is to organize the HTML by properly indenting it so it's structure its clear to read and every child is indented away from its parent.

***ready for a challenge???***

Open the file "unscramble-challenge.html" and see if you can handle a *real* mess--this file goes a little over the top in showing how much a pain poorly foramtted code can be.
You'll see all sorts of unfamiliar elements, but feel free to explore and google new things you haven't seen before!


# Part 2: Links

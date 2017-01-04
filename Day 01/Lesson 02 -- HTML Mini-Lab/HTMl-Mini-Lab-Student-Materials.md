# HTML Mini-Lab: Write Clean Code Across Multiple pages


## Motivation (i.e. What is this, and why should you care?)

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
      &lt;p&gt; This is a paragraph inside a section of the article.  &lt;/p&gt;
      <br>
      &lt;/section&gt;
      <br>
      &lt;section&gt;  
      <br>
      &lt;p&gt; This is a paragraph inside a section of the article.  &lt;/p&gt;
      <br>
      &lt;/section&gt;
      <br>&lt;/article&gt;
    </td>

    <td>
      &lt;article&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;section&gt;  
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;p&gt; This is a paragraph inside the section.  &lt;/p&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;/section&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;section&gt;  
      <br>
      &#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&lt;p&gt; This is a paragraph inside the section.  &lt;/p&gt;
      <br>
      &#160;&#160;&#160;&#160;&#160;&lt;/section&gt;
      <br>&lt;/article&gt;
    </td>
  </tr>
</table>

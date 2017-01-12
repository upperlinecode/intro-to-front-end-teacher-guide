# Day 2 Lesson 1: The CSS Diner

#### Intro to Front-End Web Development


### Objectives and Plan for Assessment

<table>

  <!-- Head -->
	<tr>
		<th> Focus Question </th>
   	<th> Objective / SWBAT:</th>
   	<th> Students will know that... </th>
   	<th> Students will think about...</th>
  </tr>

  <!-- Second Row  -->

  <tr>
		<!-- Focus Question -->
	  <td valign="top">
      	How do we select and style specific elements in our pages using a variety of CSS selectors?
    </td>

    <!-- SWBAT -->
    <td valign="top">
       <ul>
          <li>  Use multiple different types of CSS selectors to select elements in their pages. </li>
          <li>  Add multiple classes to HTML elements </li>
          <li>  Add Google Fonts to their web pages  </li>
          <li> Add background images  </li>
       </ul>
    </td>

    <!-- Students will know that...  -->
    <td valign="top">
      <ul>
        <li> An HTML element can have multiple classes  </li>
        <li> There are a variety of powerful CSS selectors available to allow styling of specific elements.  </li>
        <!-- <li>  </li> -->
      </ul>
    </td>

    <!-- Students will think about  -->
    <td valign="top">
      <ul>
        <li> How they can get better at CSS by using a cheat sheet.  </li>
      	<li> How they should always be writing clean code in keeping with conventions  </li>
       </ul>
    </td>
  </tr>

  <!-- assessment headings -->
  <tr>
    <th colspan="2">
      Assessment of Lesson Objective
    </th>
    <th colspan="2">
      Characteristics of model assessment product
    </th>
  </tr>

  <!-- assessment details  -->
  <tr>

    <!-- Assessment description -->
    <td colspan="2">
      <li> Review of Student's Diner Pages </li>
    </td>

    <td colspan="2">
      <ul>
        <li> Students employ multiple different types of selectors to style their diner pages  </li>
        <li> Students target elements with multiple classes.  </li>
      </ul>
    </td>
  </tr>
</table>

### Materials
+ Slides
+ Index cards
+ Computers
+ Student Guide

### Code Snippets for Do-Now

#### 1. Spot the two errors.
```
.potato
  color: white
}

```
#### 2. Correct for conventions
```
.potato{backkground-color:brown;font-family:helvetica}

```

### Lesson Agenda in Brief (50 minutes)
<table>
  <tr>
    <td> 1. </td>
    <td> 05 minutes </td>
    <td colspan="7"> Do-Now: Spot error in CSS. Correct for style conventions.  </td>
  </tr>
  <tr>
    <td> 2. </td>
    <td> 07 minutes </td>

    <td colspan="7">  Mini-Lesson: Overview of how to use the CSS diner activity. </td>
  </tr>

  <tr>
    <td> 3. </td>
    <td> 15 minutes </td>

    <td colspan="7"> Work-Time: Student  </td>
  </tr>


  <tr>
    <td> 6. </td>
    <td> 05 minutes </td>
    <td colspan="7"> Checkin for Part II: CSS cheat sheet  </td>
  </tr>

  <tr>
    <td> 3. </td>
    <td> 15 minutes </td>

    <td colspan="7"> Work-Time Part II:  Using a cheat sheet to add style to a page.  </td>
  </tr>

  <tr>
    <td> 3. </td>
    <td> 03 minutes </td>

    <td colspan="7"> Closing   </td>
  </tr>


</table>

### Procedure
<table>
	<!-- Headings  -->
  <tr>
    <th> Lesson Segment  </th>
    <th colspan="4"> Teacher Actions </th>
    <th colspan="4"> Student Actions </th>
  </tr>

	<!-- Do now -->
  <tr>
    <td>
			<p> <b> Do Now </b></p>
			<p> (5 min) </p>
		</td>

		<!-- Do-Now Teacher  -->
    <td colspan="4">
			<ul>
				<li> Teacher Welcomes Students, directs them to take an index card, have a seat, and start the do now</li>
				<li> Teacher directs students to correct the error in the first CSS snippet before going on to correct the style of the second according to CSS conventions (Selector on first line, properties indented, etc. )</li>
				<li> </li>
			</ul>
		</td>

		<!-- Do-Now Student  -->
    <td colspan="4">
			<ul>
				<li> Students come into class, grab an index card, and begin writing their do-now responses on the index card. </li>
				<li> Students correct the errors they see in the first snippet and then go on to rewrite the second according to propper formatting conventions . </li>
			</ul>
		</td>
  </tr>


	<!-- Mini-Lesson -->
  <tr>
    <td>
			<p> <b> Mini-Lesson </b></p>
			<p> (7 min) </p>
		</td>

		<!-- Mini Lesson Teacher  -->
    <td colspan="4">
			<ul>
				<li> Teacher takes a minute to hear responses to the do-now and shows visual of what the properly written CSS should look like.  </li>
				<li> Teacher reiterates that the first line of CSS is the 'selector' and it selects elements (in the DOM, for any why did the welcome problem) to style before asking the class what types of selectors they know up to this point (class: uses a period, selects all elements with a given classname; id: uses a # to select the one element with a particular id; and tag, which is just the name of the tag and selects all of that type of element.  )</li>
				<li> Teacher goes on to explain that today students will learn a variety of new CSS selectors through a fun activity called the CSS diner. Not all of the selectors are essential to memorize, especially the advanced ones, but the general concept, that there are a variety of powerful selectors to target exactly what you want, is very useful as you go forward  and have specific tasks you want to accomplish.  </li>
				<li> Teacher boots up the [CSS Diner](https://flukeout.github.io/)  and explains the general layout of the site: the prompt, which tells the students what to select; the example and help section, where student should go to for help and examples; the HTML, which shows the elements (some of which, like &lt;plate&gt; are made up but treat them like real tags); and lastly the CSS selection, where the user types the selector that would slect the elements </li>
        <li> Teacher explains that students will not actually style the elements, pointing to the "styles would go here" section, but that the goal is just to get familiar using a variety of different selectors so that when they do go on to style real code, they're familiar with the selectors that allow them to pinpoint particular elementns<li.
        <li> Teacher models the first two examples and asks class what the selectors would be before entering them </li>
			</ul>
		</td>

		<!-- Mini-Lesson Student -->
    <td colspan="4">
			<ul>
				<li> Students observe and listen to brief Mini-Lesson; students may take notes if they wish. </li>
			</ul>
		</td>
  </tr>


	<!-- Work Time  -->
  <tr>
    <td> <p><b>Student Work Time </b></p> <p> (15 mins)</p>  </td>

		<!-- Worktime Teacher -->
    <td colspan="4">
			<ul>
				<li>As students begin working, teacher sets a 15 minute timer on the board to keep the lesson on pace. </li>
				<li>Teacher(s) circulate and provide assistance as necessary; teachers should push students to address their own misunderstandings, where possible, by referencing the example section of the CSS diner activity. </li>
			</ul>
		</td>


		<!-- Worktime Student -->
    <td colspan="4">
			<ul>
				<li> Students access the CSS diner link from the student guide and begin working.  </li>
				<li> Students work independently at their own pace, trying to get as far as possible in the allotted time.   </li>
			</ul>
		</td>
  </tr>

	<!-- Checkin  -->
  <tr>
    <td> <p><b>Checkin </b></p> <p> (5 mins)</p>   </td>

		<!-- Checkin Teacher-->
    <td colspan="4">
			<ul>
				<li> Teacher tells students to draw work to a close and bring attention to the front and put screens at 45 degrees. </li>

				<li>  
          Teacher praises students for good work habits where appropriate and asks students how  far they got, telling students that anything past the 15th level would be fairly rare to see in the professional world and that 90% of their code  will involve basic class and children selectors
        </li>

				<li>
          Teacher explains that while students were just exposed to a lot of material, one great thing about being web developers is that they always get to use online resources whenever they want to remember or figure out how to do anything.
        </li>

				<li>
          Teacher pulls up [the w3 Schools comprehensive reference](http://www.w3schools.com/cssref/default.asp) (linked in their materials for part two) gives a comprehensive list of <i>every</i> single CSS property and that while they will never use many of the properties listed there, they will definitely need to see the reference materials for many others.
        </li>

				<li>
          To show students how to read the documentation, teacher picks a property (recommended:  'position') and shows how the page lists an example of how the porperty is used, with the 'try it yourself button' and the list of acceptable values separated by the | symbol and then lastly the list of values with the "play it button"
        </li>

        <li>
          Teacher explains how clicking the 'play it' button can take you to a site which gives a number of examples to play around with and figure out the property and that as they go on to develop web pages, they will need to be constantly referencing this documentation to figure things out.
        </li>

			</ul>
		 </td>

		 <!-- Checkin Student -->
    <td colspan="4">
			<ul>
				<li> Students put laptop screens at 45 and watch as the teacher takes them through the documentation </li>
				<li> Students may take notes if they wish.  </li>				
			</ul>
		</td>
  </tr>

  <!-- Work Time Part II   -->
  <tr>
    <td> <p><b>Student Work Time II </b></p> <p> (15 mins)</p>  </td>

    <!-- Worktime Teacher -->
    <td colspan="4">
      <ul>
        <li>  </li>
        <li>Teacher(s) circulate and provide assistance as necessary; teachers should push students to address their own misunderstandings, where possible, by referencing the student guide. </li>
      </ul>
    </td>


    <!-- Worktime Student -->
    <td colspan="4">
      <ul>
        <li>  </li>
        <li>  </li>
      </ul>
    </td>
  </tr>


<!-- closing -->
  <tr>
    <td>  <p><b>Closing </b></p> <p> (3 mins)</p>  </td>

		<!-- Closing teacher -->
    <td colspan="4">
			<ul>
				<li>  </li>
				<li>  </li>
 			<ul>
		 </td>

		 <!-- Closing Student -->
    <td colspan="4">
			<ul>
				<li>Students review code; write necessary changes on index card </li>
				<li>Students  hand in card and are dismissed </li>
			</ul>
		</td>
  </tr>

</table>

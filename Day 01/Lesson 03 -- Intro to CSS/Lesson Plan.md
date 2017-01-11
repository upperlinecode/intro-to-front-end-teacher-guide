# Lesson 03: CSS Basics


### Objectives and Plan for Assessment

<table>

  <!-- Head -->
	<tr>
		<th>Focus Question </th>
   	<th>Objective / SWBAT:</th>
   	<th> Students will know that... </th>
   	<th> Students will think about...</th>
  </tr>

  <!-- Second Row  -->

  <tr>
		<!-- Focus Question -->
	  <td valign="top">
      	How do add STLYE to our webpages using "Cascading Style Sheets" (a.k.a CSS)
    </td>

    <!-- SWBAT -->
    <td valign="top">
       <ul>
          <li> Link to a CSS sheet. </li>
          <li> Use tag, class, and id selectors to select HTML elements.  </li>
          <li> Use a variety of properties to add style to their pages </li>
       </ul>
    </td>

    <!-- Students will know that...  -->
    <td valign="top">
      <ul>
        <li> They need to link to the stylesheet in order for any changes to come into effect </li>
        <li> CSS requires proper syntax: <b> [selector] { [property-name] : [value] ; }  </b></li>
        <li> The best way to learn is to experiment and explore with new properties. </li>
      </ul>
    </td>

    <!-- Students will think about  -->
    <td valign="top">
      <ul>
      	 <li> How they can experiment with different properties </li>
         <li> How  they could get their pages to look like one of the exemplars. </li>
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
  <td colspan="2">
    <li> Review of student "Zen Garden Challenge" </li>
  </td>

  <td colspan="2">
    <ul>
      <li> Proper syntax and formatting of CSS </li>
      <li> A variety of CSS selectors and properties are used--some of which were not explicitly listed in the guide. </li>
    </ul>
  </td>
</table>

### Materials
+ Slides
+ Index cards
+ Computers
+ Student Guide

### Lesson Agenda in Brief (50 minutes)
<table>
  <tr>
    <td> 1. </td>
    <td> 05 minutes </td>
    <td colspan="7"> Do-Now: Code sample: record observations and inferences. </td>
  </tr>
  <tr>
    <td> 2. </td>
    <td> 07 minutes </td>

    <td colspan="7">  Mini-Lesson: Overview of CSS: what it is, how to use it </td>
  </tr>

  <tr>
    <td> 3. </td>
    <td> 30 minutes </td>

    <td colspan="7"> Work-Time: Students work to style a sample of four div elements before moving on the the <b> CSS Zen Garden </b> challenge.   </td>
  </tr>

  <tr>
    <td> 6. </td>
    <td> 05 minutes </td>
    <td colspan="7"> Shoutouts and Exit-Ticket </td>
  </tr>

</table>

### Procedure
<table>

  <tr>
    <th> Lesson Segment  </th>
    <th colspan="4"> Teacher Actions </th>
    <th colspan="4"> Student Actions </th>
  </tr>


  <tr>
  <!-- Do now -->
    <td>
			<p> <b> Do Now </b></p>
			<p> (5 min) </p>
		</td>

    <!-- Do now teacher -->
    <td colspan="4">
			<ul>
				<li> Teacher Welcomes Students, directs them to take an index card, have a seat, and start the do now</li>
				<li> Teacher instructs students to look at the code sample on the slides, and make at least <i>three</i> observations about what they see and <i>one</i>  inference as to what it might do</li>
        <li> As students complete do-now, teacher calls class to attention and leads shareout, praising keen observations and insightful inferences while using the shareout as an informal assessment of student prior knowledge and aptitude for the coming material. </i>
			</ul>
		</td>

    <!-- Do now Student -->
    <td colspan="4">
			<ul>
				<li> Students enter class and take a blank index card</li>
				<li> Students look at the code sample and make three observations and one inference.  </li>
        <li> When called to attention, students shareout observations and inferences. </i>
			</ul>
		</td>
  </tr>

  <tr>
    <td>
			<p> <b> Mini-Lesson </b></p>
			<p> (7 min) </p>
		</td>
		<!-- Mini Lesson Teacher  -->
    <td colspan="4">
			<ul>
				<li> Teacher reiterates some the insightful products of the share-out they noticed as a transition in explaining that what they were actually looking at was a sample of a "Cascading Style Sheet" or just "CSS"; a separate file of code which will add style to an existing HTML document.  </li>
				<li> Teacher reiterates that a stylesheet is a completely separate file from the HTML document that generates the elements, and as such it needs to be linked to from the html</li>
				<li> Teacher livecodes creating a stylesheet and linking to it from an existing HTML document</li>
				<li>  Teacher goes on to explain that since the stylesheet is separate from the HTML, we will need to be very specific when writing CSS--it operates under the principle of <b> Find an element in the document; add properties to it.</b> </li>
        <li> Live Code: In the css document the teacher just created, the teacher demonstrates this principle; first, I need to decide which element I want to add style to. Let's say I want to style these paragraphs, I see in the HTML document that they are contained in p tags, so in my css document I will start by simply writing 'p'. This first line is a called a "selector," and it "selects" all of the p elements on the page.
        <p> Next, will add the 'curly brackets'-- which are next to the p key on your keyboard; and create a line of space inbetween them so my code keeps organized. Any code I write between these two curly braces will apply only to the P elements I specified with my slector. </p>
        <p> Now that I have my selector and curly braces set up, I'm ready to add some properties. The best way to do this is cheat--good developers make use of their resources, and so I'm going to find a property in my cheat sheet, and start by copying the example and experiment with it to get what I want. For example, backkground-color seems like a pretty self explanatory property so I'll start with that and try changing the color...</p>
        <p> Now, before you go on to the challenge, it's important to stress that you don't forget the colon after the propert name and the semicolon after its value! This is a mistake that is <b> really </b> easy to make and it can be frustrating <p> </li>

        <li> Teacher directs students to begin working on their 'box-model' challenge </li>
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
				<li>As students begin, teacher sets a 15 minute timer on the board to keep the lesson on pace. </li>
				<li>Teacher(s) circulate and provide assistance as necessary; teachers should push students to address their own misunderstandings, where possible, by referencing the student guide. </li>
			</ul>
		</td>


		<!-- Worktime Student -->
    <td colspan="4">
			<ul>
				<li> Students access the student guide and start working according to the directions given on the student guide </li>
			</ul>
		</td>
  </tr>

  <tr>



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

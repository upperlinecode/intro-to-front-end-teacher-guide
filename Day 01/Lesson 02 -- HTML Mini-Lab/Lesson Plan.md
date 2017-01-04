# Lesson 02: HTML Practice Mini-Lab


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
      	How do we write good, clean HTML across multiple pages?
    </td>

    <!-- SWBAT -->
    <td valign="top">
       <ul>
          <li> Properly refactor poorly written HTML according to conventions </li>
          <li> Write links that navigate within a page.  </li>
          <li> Use links across multiple local pages.  </li>
       </ul>
    </td>

    <!-- Students will know that...  -->
    <td valign="top">
      <ul>
        <li> Child elements  should be indented one tab over to indicate their position as a child element. </li>
        <li> No element should have a closing tag that is outside the closing tag of its parent. </li>
        <li> a tags can be used to link to other pages in a student side.  </li>
      </ul>
    </td>

    <!-- Students will think about  -->
    <td valign="top">
      <ul>
      	 <li> How they should always be writing clean code in keeping with conventions  </li>
         <li> How they could use their skills to have a multi-paged website.  </li>
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
      <ul>
        <li> Review of students' HTML unscrambles </li>
        <li> Review of Student's Link Pages </li>
      </ul>
    </td>

    <!-- Characteristics of model assessment -->
    <td colspan="2">
      <ul>
        <li> Proper indentation of HTML in unscrambles</li>
        <li> Students correctly link to locations within a page and seperate local pages. </li>
      </ul>
    </td>
  </tr>
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
    <td colspan="7"> Do-Now: Share out of experience during first activity </td>
  </tr>
  <tr>
    <td> 2. </td>
    <td> 07 minutes </td>

    <td colspan="7">  Mini-Lesson: Overview of today's activity, style conventions, and live-coding of links.</td>
  </tr>

  <tr>
    <td> 3. </td>
    <td> 30 minutes </td>

    <td colspan="7"> Work-Time: Part 1, Indenting Scrambled HTML; Part 2, Linking in and between pages</td>
  </tr>

  <tr>
    <td> 6. </td>
    <td> 05 minutes </td>
    <td colspan="7"> Shoutouts and Exit-Ticket: code refactor. </td>
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
    <td>
			<p> <b> Do Now </b></p>
			<p> (5 min) </p>
		</td>


    <!-- Do-now teacher -->
    <td colspan="4">
			<ul>
				<li> Teacher Welcomes Students, directs them to take an index card, have a seat, and start the do now</li>
				<li> Teachers should direct students to write at least 2 glows (areas they feel good) at and 2 grows (areas they need to work at) </li>
				<li>Teacher facilitates share-out and makes note of student progress and confidence. </li>
			</ul>
		</td>

    <!-- Do- student  -->
    <td colspan="4">
			<ul>
				<li>Students enter the class , taking a blank index card on their way in,. </li>
				<li> Students write their do-nows., recording grows and glows. </li>
        <li> Students share out at teacher direction </li>
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
				<li> If deemed necessary, teacher may address a specific area of confusion presented by the share-out of the do-now.  </li>
				<li>Teacher explains that today’s activity will involve two parts: the first, proper formatting of HTML; the second, linking to pages and parts of a document, and it will serve to reinforce the new skills they have just learned in the last activity.   </li>
				<li>Teacher illustrates how a child element is contained in its parent parent, referencing example. ```Example``` and  calls to attention the proper indentation of the child.   </li>
				<li>Teacher goes on to explain the formatting of the HTML according to these conventions is very important, even though the browser can sometimes compensate for mistakes as it will make their code more readable.   </li>
        <li> Teacher explains that  for the  second part of their lab they will have to   write links to other pages in their projects as well to other parts of the page. </li>
        <li> Switching to the Cloud9 environment, the teacher live-codes how to make two links, the first being to an existing html document in the project. The teacher should stress that they is adding a src attribute and simply adding the file name. </li>
        <li> For the second link, the teacher demonstrates how to add a link to a place in the page, explaining that  in order for the href to have any meaning, we need to the element  the class is going to navigate an “id attribute”-- e.g. id=”example”. Teacher should note  that the value of this id attribute could be anything. Then, for the href attribute of the a tag, the teacher should note that to direct the browser to the element just given an id, the href should  start with a hashtag (like in twitter) to call out that element specifically. </li>
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
				<li> Students work through the challenges presented in the student guide , and time permitting,  work on some of the challenges. </li>
			</ul>
		</td>
  </tr>

  <tr>
		<!-- Checkin  -->
    <td> <p><b>Checkin </b></p> <p> (1 mins)</p>   </td>

		<!-- Checkin Teacher-->
    <td colspan="4">
			<ul>
				<li> Teacher calls class to attention and gives some shoutouts of good work habbits they notivved before  signaling that stduents should begin moving on to part two, even if they weren't able to complete all of part 1. </li>
			</ul>
		 </td>

		 <!-- Checkin Student -->
    <td colspan="4">
			<ul>
				<li> Students move on to part two of the challenge by closing out of their code unscrambles, navigating to the  Part 2 section of the student guide, and opening the "HTML-lesson-two-link-challenge.html" file. </li>			
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

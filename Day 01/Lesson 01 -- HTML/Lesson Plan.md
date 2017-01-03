# Introduction to Web Development, Lesson One: HTML

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
      	How do we use "Hyper-Text Markup Language" to create a basic webpage ?
    </td>

    <!-- SWBAT -->
    <td valign="top">
       By the end of the lesson, students will be able to create a basic website properly using a variety of HTML tags.
    </td>

    <!-- Students will know that...  -->
    <td valign="top">
      <ul>
        <li> Web browsers take in text (in the form of HTML, and render it into a visual page)</li>
        <li> HTML elements are the fundmental building blocks of webpages</li>
        <li> Elements are defined by "tags" enclosed in angle brackets (eg. `<span> Hello! </span>` )</li>
        <!-- <li> Elements act as containers, and each subsequent element they contain are their 'child' elements</li>   -->
      </ul>
    </td>

    <!-- Students will think about  -->
    <td valign="top">
      <ul>
      	 <li> The need to keep within conventions when writing HTML </li>
         <li> New elements to experiment with </li>
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
  	Review of work product and exit ticket.
  </td>

  <td colspan="2">
    <ul>
      <li> Accurately recreated boilerplate </li>
      <li> Use of at least eight different html tags</li>
			<li>Exit ticket spots both errors: the tag needs to be in the body, and its source should be written as an src attribute. </li>
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
    <td colspan="7"> Observational Do-Now</td>
  </tr>
  <tr>
    <td> 2. </td>
    <td> 07 minutes </td>

    <td colspan="7">  Mini-Lesson: How HTML works</td>
  </tr>

  <tr>
    <td> 3. </td>
    <td> 15 minutes </td>

    <td colspan="7"> Work-Time: Students recreate boilerplate and add several attribute-less elements as time permits </td>
  </tr>

  <tr>
    <td> 4. </td>
    <td> 05 minutes </td>

    <td colspan="7"> Shoutouts and overview of attributes. </td>
  </tr>

  <tr>
    <td> 5. </td>
    <td> 15 minutes </td>
    <td colspan="7"> Students add <b>&lt;img&gt; </b>and <b>&lt;a&gt; </b>and add attributes. </td>
  </tr>

  <tr>
    <td> 6. </td>
    <td> 03 minutes </td>
    <td colspan="7"> Exit-Ticket: spot the error. </td>
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
    <td colspan="4">
			<ul>
				<li> Teacher Welcomes Students, directs them to take an index card, have a seat, and start the do now</li>
				<li> As students settle, teacher tells students that they aren't supposed to be familiar with the code they're looking at, but encourages them to make at least three observations (on their index card) about the boilerplate and at least one inference as to what it might do; look closely, and take a guess</li>
				<li> ~4 mminutes, teacher calls on one to two students to share their responses to take an initial informal assessment of student prior knowledge and transition to the Mini-Lesson</li>
			</ul>
		</td>
    <td colspan="4">
			<ul>
				<li> Students enter classroom,  take an index card and have a seat</li>
				<li> Students observe the unfamiliar code and make three observations about what they are seeing and one inference as to what it does (on index card). </li>
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
				<li> Teacher praises close observations from students and explains that the skill they just practiced--observing and making inferences about unknown code--is crucial to the proficient coder's skillset, and part of learning to code is always feeling a little lost as you try to figure out a new language   </li>
				<li> Teacher reveals that what they were looking at was actually "Hyper-Text Markup Language", a long and fancy way of saying "text with extra stuff in it", that nearly everyone just refers to as <b>HTML.</b> </li>
				<li> HTML is necessary because computers don't communicate with pictures; when you go online, your computer makes a request to a website, and that website's servers send back a long chunk of text that is 'read' by your computer and rendered into all the sorts of fancy memes and facebook posts you love to see.  </li>
				<li> Teacher explains that all HTML is contained within blocks of code called <b> elements </b> which, are opened with an opening tag in angle brackets, eg. &lt;html&gt; and closed with an identical tag that has a / in it. For example

				<br>
				<p>
				 <b> &lt;body&gt;  &lt;p&gt; </b> I am a paragraph tag (get it--"p" for paragraph? ) inside a "body" tag  <b> &lt;/p&gt;   &lt;/body&gt; </b>
				</p>

				 </li>
				<li> Teacher explains that today, their task will be to recreate the basic code they are given according to the directions of the activity; remember, it's ok to feel a little lost, and the goal is to experiment modifying and expanding on existing code though experimentation with the help of the student guide. </li>
				<li> Teacher directs students to the repository and to being the activity. </li>
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
				<li> Students' first order of business will be to copy the boilerplate identically as given in the guide. They then can go on to add various elements according to the directions.  </li>
			</ul>
		</td>
  </tr>

  <tr>
		<!-- Checkin  -->
    <td> <p><b>Checkin </b></p> <p> (5 mins)</p>   </td>

		<!-- Checkin Teacher-->
    <td colspan="4">
			<ul>
				<li> At end of timer; teacher calls students to attention and asks for laptop screens at 45 degrees. </li>
				<li> Teacher gives a couple of shoutouts to call attention to good practices they witnessed during the initial amount worktime; in particular, how students were working to figure out and work with unfamiliar material and how they used proper formatting.  </li>
				<li>
					Teacher shows slide of of html tag, and highlights how up to this point, students have only been able to make elements entirely out of text, but there's so much more they'll be able to do and the next step is to be able to add links and images.
					<p>
					  Links and Images have their own tags; &lt;a&gt; is for links, and &lt;img&gt; is for images, but these tags are useless by their own --why is that ?
					</p>
				</li>
				<li> Teacher explains that to give these tags more meaning, they need attributes which gives the image a source to find the image, and a link or "Hyper-Text reference" for the link. </li>
				<li> Teacher live codes adding an image source and link href . </li>
			</ul>
		 </td>

		 <!-- Checkin Student -->
    <td colspan="4">
			<ul>
				<li>Students pause their work and put screens at 45 degrees. </li>
				<li>Students watch and listen as teacher demonstrates </li>				
			</ul>
		</td>
  </tr>

<!-- Worktime part two -->
  <tr>
    <td>  <p><b>Worktime </b></p> <p> (15 mins)</p>  </td>

		<!-- worktime part two teacher -->
    <td colspan="4">
			<ul>
				<li> Teacher explains that students will now access part two of the mini-lab, which will require them to add links and images to their page, and they should move on even if they haven't fully completed all the action items of the first challenge.   </li>
				<li> Teacher(s) circulate as necessary to provide support, directing students to use their resources and peers as appropiate.
			</ul>
		</td>
		<!-- worktime part two student  -->
    <td colspan="4">
			<ul>
				<li> Students stop working on part one of the challenge and access part two of the student materials about links and images.</li>
				<li> Students work on part two of the challenge and ask for assistance as needed</li>
			</ul>
		</td>
  </tr>


<!-- closing -->
  <tr>
    <td>  <p><b>Closing </b></p> <p> (3 mins)</p>  </td>

		<!-- Closing teacher -->
    <td colspan="4">
			<ul>
				<li> Teacher calls students to attention and gives brief praise of any positive work habits they noticed. </li>
				<li> Teacher asks student to look at the code on the screen and point out--in writing, on the reverse side of the index card they recieved when they entered--what two things (if they can) the author of the code would need to change in order for the image to appear on the screen. When students are done, they may turn in their index card and be dismissed.
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

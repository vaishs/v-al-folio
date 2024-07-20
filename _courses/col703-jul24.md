---
layout: page
title: COL703 &ndash; Logic for Computer Science
description: July 2024 &ndash; November 2024
# img: assets/img/12.jpg
importance: 1
# category: work
---

<header>
	<h2><strong>Course timings &amp; Venue:</strong> <p style="display:inline">B slot: Mondays &amp; Thursdays 0930 &ndash; 1100, in Block VI, LT II.</p></h2>
</header>

<hr style="border: 1px dashed; color: orange" />

<!-- <strong>
		If you want to but cannot register (perhaps because you do not fulfil the system-required prerequisites, which are different from the ones <a href="#prereq">here</a>), please fill out a General Request on the portal and mention me as the course coordinator. I will approve your request and the admin will eventually register you for the course.
</strong>

<hr style="border: 1px dashed; color: orange" /> -->

<br>

<header>
    <h2> <strong>What is this course about, and why should I take it?</strong> </h2>
</header>

<p>Logicians will often tell you that the primary raison d'être of logic is to systematically evaluate arguments for deductive validity, or something equally abstruse along those lines. So why should you, a computer scientist, bother with logic at all? Because, as anyone who has ever written a program beyond "Hello, world!" knows, writing code is hard. Writing <em>good</em> code is even harder, and this starts even before we have written any code at all! Are you sure that what you <em>think</em> you want is really what you want? Will your code actually work? How reasonable are the assumptions you have made along the way? These are questions that logic can help you think about in a systematic way.</p>

<p>The objective of this course is to learn fundamental ideas that help us create abstract models of systems in the real world, so we can then ensure that they behave as they should. This course will essentially cover concepts related to how to model complex systems abstractly while making good choices, as well as how to reason about these systems automatically, with a view to formal verification.
</p>

<br>

<header>
    <h2 id="prereq"><strong> Prerequisites </strong></h2>
</header>
<p> This fundamental material covered in this course is fairly abstract and theoretical, and will therefore require some mathematical acumen -- students should, at the very least, be able to write and understand rigorous formal proofs, especially those involving various kinds of induction. There will also be some programming involved to implement various concepts. You should have taken <strong>at least one</strong> of the following courses (or equivalents thereof):
<ul>
		<li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL106" target="_blank">COL106 (Data Structures & Algorithms)</a>.</p></li>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL202" target="_blank">COL202 (Discrete Mathematical Structures)</a></p></li>
</ul>
</p>

<br>

<header>
		<h2><strong> Evaluation policy </strong></h2>
</header>
<p>
	<ul>
			<li><p>Assignments: 20%. We will follow a graceful degradation policy: For every day that you use beyond the indicated deadline, you lose 20% of marks for that assignment -- if you submit anything later than 5 days past the deadline, it will not be evaluated.</p></li>
			<li><p>Minor: 20%. No re-minor will be conducted. If you miss the minor for a medical reason (with appropriate documentation produced within one week of the minor), the major marks will be scaled up accordingly.</p></li> 
			<li><p>Major: 40%. The syllabus for the major exam will include everything covered in the course.</p></li>
			<li><p>Quizzes: 15&ndash;20%. There will be some surprise quizzes conducted in class at various points during the semester. Absence in a quiz is directly marked 0. No make-up quizzes will be conducted.</p></li>
			<li><p>In-class participation, attendance etc: 0&ndash;5%.</p></li>
			<li><p>Pedagogical experiment surveys: 0&ndash;5% <strong>Bonus</strong>.</p></li>
			<li><p>"A few of my favourite things": 0&ndash;5% <strong>Bonus</strong>.</p></li>
	</ul>
</p>

<p>Audit pass needs at least a B- overall, including at least 10% out of the 15&ndash;20% earmarked for quizzes.</p>
	
<p>Deviation of any sort from the IIT Delhi honour code (copying, plagiarism, collaborating on gradable items where explicitly disallowed etc. &ndash; see <a href="https://t.ly/jACWG" target="_blank">here</a> for more examples) will summarily result in an F grade, or in case of audit, an NF, and potentially further disciplinary action.</p>

<header>
	<h2><strong> Reference material </strong></h2>
</header>
<p>
	We will follow notes presented in class, for the most part. Notes will be uploaded here. An overall external reference for much of the course can be found <a href="https://www.logicmatters.net/ifl/" target="_blank">here</a>.
</p>


<!-- <header>
    <h2><strong> Lecture Notes &amp; Reference Material </strong></h2>
</header>
<div class="table-responsive">
<table class="table table-sm table-bordered">
  <thead class="thead-dark">
    <tr>
      <th>Date</th>
      <th>Slides</th>
      <th>References (if any)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>24 July, 2023</td>
      <td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec1.pdf" target="_blank">Lecture 1</a></p></td>
      <td></td>
    </tr>
    <tr>
      <td>27 July, 2023</td>
      <td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec2.pdf" target="_blank">Lecture 2</a></p></td>
      <td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/normsub.pdf" target="_blank">Normalization and subterm property</a></p></td>
    </tr>
		<tr>
			<td>3 August, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec3.pdf" target="_blank">Lecture 3</a></p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/quiz1-with-answers.pdf" target="_blank">Quiz 1 (with solutions)</a></p></td>
		</tr>
		<tr>
			<td>7 August, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec4.pdf" target="_blank">Lecture 4</a></p></td>
			<td></td>
		</tr>
		<tr>
			<td>10 August, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec5.pdf" target="_blank">Lecture 5</a></p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/appliedpi.pdf" target="_blank">Notes on the applied-pi calculus</a></p></td>
		</tr>
		<tr>
			<td>14 August, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec6.pdf" target="_blank">Lecture 6</a></p></td>
			<td></td>
		</tr>
		<tr>
			<td>17 August, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec7.pdf" target="_blank">Lecture 7</a></p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/newns.pv" target="_blank">ProVerif code</a></p></td>
		</tr>
		<tr>
			<td>21 August, 2023</td>
			<td><p>Applied-pi Calculus Review</p></td>
			<td></td>
		</tr>
		<tr>
			<td>24 August, 2023</td>
			<td><p>ProVerif Review</p></td>
			<td></td>
		</tr>
		<tr>
			<td>28 August, 2023</td>
			<td><p>Review &amp; discussion</p></td>
			<td></td>
		</tr>
		<tr>
			<td>31 August, 2023</td>
			<td><p>Lecture 8, Undecidability of the secrecy problem</p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/undec-2count.pdf" target="_blank">Notes</a></p></td>
		</tr>
		<tr>
			<td>4 September, 2023</td>
			<td><p>Assignment 1 Review</p></td>
			<td></td>
		</tr>
		<tr>
			<td>18 September, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec9.pdf" target="_blank">Lecture 9</a></p></td>
			<td></td>
		</tr>
		<tr>
			<td>25 September, 2023</td>
			<td><p>More about multiset rewriting and Tamarin</p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/try.spthy" target="_blank">Tamarin Code</a></p></td>
		</tr>
		<tr>
			<td>28 September, 2023</td>
			<td><p>Some more Tamarin</p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/ns-toy.spthy" target="_blank">Tamarin Code</a></p></td>
		</tr>
		<tr>
			<td>9 October, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec10.pdf" target="_blank">Lecture 10</a>, Constraint satisfaction</p></td>
			<td></td>
		</tr>
		<tr>
			<td>12 October, 2023</td>
			<td><p>Guest lecture by Mr. Karl Normann, Ericsson Research</p></td>
			<td></td>
		</tr>
		<tr>
			<td>16 October, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec11.pdf" target="_blank">Lecture 11</a>, Computational soundness (part 1)</p></td>
			<td></td>
		</tr>
		<tr>
			<td>19 October, 2023</td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/lec12.pdf" target="_blank">Lecture 12</a>, Computational soundness (part 2)</p></td>
			<td><p><a href="../../assets/pdf/lecnotes/col876-diw23/ref/comp-sound.pdf" target="_blank">Original paper</a></p></td>
		</tr>
  </tbody>
</table>
</div>


<br> -->

---
layout: page
title: Formal Verification of Security Protocols <br> <h3>COL876 - Special Topics in Formal Methods</h3>
description: July 2023 &ndash; December 2023
# img: assets/img/12.jpg
importance: 1
# category: work
---

<header>
	<h2><strong>Course timings &amp; Venue:</strong> <p style="display:inline">Mondays &amp; Thursdays 1530 &ndash; 1700, in SIT006.</p></h2>
</header>

<hr style="border: 1px dashed; color: orange" />

<strong>
		If you want to but cannot register (perhaps because you do not fulfil the system-required prerequisites, which are different from the ones <a href="#prereq">here</a>), please fill out a General Request on the portal and mention me as the course coordinator. I will approve your request and the admin will eventually register you for the course.
</strong>

<hr style="border: 1px dashed; color: orange" />

<br>

<header>
    <h2> <strong>What is this course about?</strong> </h2>
</header>

<p>Nowadays, we use smart devices and the internet to do everything from chatting with friends to booking movie tickets to transferring large amounts of money to each other. How does one ensure that these cryptographic mechanisms (often called "security protocols") are secure (“nobody but me should be able to access my bank account”), private (“nobody should be able to link a payment from my anonymous Ethereum wallet to my real life identity”) etc? 
</p>

<p>It has been shown that even if the underlying cryptographic mechanisms are assumed to be perfectly correct, security protocols can often admit very problematic logical flaws. Attacks have been demonstrated on critical protocols ranging from those used for e-voting to those used in RFID passports. To get guarantees about safe operation, one can use formal verification, in which we mathematically model these protocols and the desired properties, and see if the model satisfies these properties. In this course, we will study how to formally model security protocols using various abstract systems, and how to express and verify properties over such models. In addition, since verification by hand is cumbersome and often error-prone, we will see how to code up protocols and verify properties using some specialized software.
</p> 

<p>
We will also see how this analysis, which is based mostly in abstract logic and theoretical computer science, fits into the engineering workflow of a protocol going from design to deployment, and what challenges arise during this process. While this course concentrates on the formal analysis and verification of security protocols, many of the techniques used here provide a good introduction to the field of formal verification as a whole.
</p>


<br>

<header>
    <h2> <strong>Who should take this course?</strong> </h2>
</header>
<p>
This course is for you if 
<ul>
    <li><p>you have ever wondered how messaging systems like Signal or Whatsapp ensure that messages are "end-to-end encrypted", or</p></li>
    <li><p>you worry about whether banking systems <i>really</i> are as secure and correct as one would hope and expect, or</p></li>
    <li><p>you just have an interest in combining abstract tools like logic and automata theory with programming to solve real life problems.</p></li>
</ul>
</p>

<br>

<header>
    <h2 id="prereq"><strong> Prerequisites </strong></h2>
</header>
<p> The course involves concepts from automata theory, algorithms, logic, proof theory, and programming languages. Understanding the material will, therefore, require some mathematical acumen -- students should, at the very least, be able to write and understand rigorous formal proofs, especially those involving induction. Students will also be required to be conversant with basic concepts of syntax/semantics, automata, and algorithms. A very basic idea of logic and of complexity theory is also necessary; notions like inference, reductions, and NP-completeness should not seem unfamiliar. You should have taken the following courses at IIT Delhi:
<ul>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL202">COL202 (Discrete Mathematical Structures)</a>, and</p></li>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL352">COL352 (Introduction to Automata & Theory of Computation)</a>.</p></li>
</ul>
</p>
<p>
These courses are not a hard prerequisite. If you do not fulfil the above prerequisites, but think you have the necessary background to attend this course, feel free to get in touch.
</p>

<br>

<header>
    <h2><strong> Lecture Notes &amp; Reference Material </strong></h2>
</header>
<ul>
		<li><p><a target="_blank" href="../../assets/pdf/lecnotes/col876-diw23/lec1.pdf">Lecture 1, 24 July 2023</a></p></li>
</ul>

<br>

<header>
    <h2><strong> Evaluation Policy </strong></h2>
</header>
<p>
<ul>
<li> In-class quizzes: 10% </li>
<li> Assignments: 40% </li>
<li> Project/Paper presentation: 50% </li>
</ul>
(Percentages subject to change)
</p>

<!-- For the project, two options exist:

- Team of two: Pick an RFC for a protocol in the wild (a list of potential suggestions will be provided), pick two properties (at least one "non-trivial"), and prove whether these properties hold of said protocol in some model. Justify your results and your choices. You will need to write a report and publicly host your code, based on which, there will be an individual oral exam.

- Individual: Read a paper related to the course (a list of potential suggestions will be provided) and make a presentation. In this presentation, you should convey what made you pick the paper, give an overview of what the paper is trying to achieve, set the contributions of the paper in the context of prior related work, and try to provide viable lines of future work, i.e. how the result of the paper might be extended. -->


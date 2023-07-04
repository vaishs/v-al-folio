---
layout: page
title: COL876 - Special Topics in Formal Methods
description: July 2023 &ndash; December 2023
# img: assets/img/12.jpg
importance: 1
# category: work
---

<header>
	<h2><strong>Course timings:</strong> <p style="display:inline">Tuesdays &amp; Fridays 1400 &ndash; 1550.</p></h2>
</header>

<br>

<header>
    <h2> <strong>What is this course about?</strong> </h2>
</header>

<p>Nowadays, we use smart devices and the internet to do everything from chatting with friends to booking movie tickets to transferring large amounts of money to each other. How does one ensure that these cryptographic mechanisms (often called "security protocols") are secure (“nobody but me should be able to access my bank account”), private (“nobody should be able to link a payment from my anonymous Ethereum wallet to my real life identity”) etc? 
</p>

<p>It has been shown that even if the underlying cryptographic mechanisms are assumed to be perfectly correct, security protocols can often admit very problematic logical flaws. Attacks have been demonstrated on critical protocols ranging from those used for e-voting to those used in RFID passports. To get guarantees about safe operation, one can use formal verification, in which we mathematically model these protocols and the desired properties, and see if the model satisfies these properties.
</p> 

<p>
In this course, we will study how to formally model security protocols using various abstract systems, and how to express and verify properties over such models. In addition, since verification by hand is cumbersome and often error-prone, we will see how to code up protocols and verify properties using some specialized software. We will also see how this analysis, which is based mostly in abstract logic and theoretical computer science, fits into the engineering workflow of a protocol going from design to deployment, and what challenges arise during this process. While this course concentrates on the formal analysis and verification of security protocols, many of the techniques used here provide a good introduction to the field of formal verification as a whole.
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
    <h2><strong> Prerequisites </strong></h2>
</header>
<p> The course involves concepts from automata theory, algorithms, logic, proof theory, and programming languages. Understanding the material will, therefore, require some mathematical acumen -- students should, at the very least, be able to write and understand rigorous formal proofs, especially those involving induction. Students will also be required to be conversant with basic concepts of syntax/semantics, automata, and algorithms. A very basic idea of complexity theory is also necessary; notions like reductions and NP-completeness should not seem unfamiliar. You should have taken the following courses at IIT Delhi:
<ul>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL202">COL202 (Discrete Mathematical Structures)</a>, and</p></li>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL352">COL352 (Introduction to Automata & Theory of Computation)</a>.</p></li>
</ul>
</p>
<p>
It will help if you have also taken COL226 (Programming Languages) and/or COL703 (Logic for Computer Science), but this is not a hard prerequisite. If you do not fulfil the above prerequisites, but think you have the necessary background to attend this course, feel free to get in touch over email.
</p>

<br>

<header>
    <h2><strong> Reference Material </strong></h2>
</header>
<p> Mostly notes and papers, some snippets from other published material. TBA.</p>

<br>

<header>
    <h2><strong> Evaluation Policy </strong></h2>
</header>
<p>
<ul>
<li> In-class quizzes: 10% </li>
<li> Assignments: 40% </li>
<li> Project: 50% </li>
</ul>
(Percentages subject to change)
</p>

<!-- For the project, two options exist:

- Team of two: Pick an RFC for a protocol in the wild (a list of potential suggestions will be provided), pick two properties (at least one "non-trivial"), and prove whether these properties hold of said protocol in some model. Justify your results and your choices. You will need to write a report and publicly host your code, based on which, there will be an individual oral exam.

- Individual: Read a paper related to the course (a list of potential suggestions will be provided) and make a presentation. In this presentation, you should convey what made you pick the paper, give an overview of what the paper is trying to achieve, set the contributions of the paper in the context of prior related work, and try to provide viable lines of future work, i.e. how the result of the paper might be extended.
 -->

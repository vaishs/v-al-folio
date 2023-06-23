---
layout: page
title: COL876 - Special Topics in Formal Methods
description: Course webpage for COL876 - Diwali 2023
# img: assets/img/12.jpg
importance: 1
# category: work
---

<header>
    <h2> What is this course about? </h2>
</header>
<p>
Nowadays, we use the internet to do everything from chatting with friends to booking movie tickets to transferring large amounts of money to each other. How does one ensure that these mechanisms (often called "security protocols") are secure (“nobody but me should be able to access my bank account”), private (“nobody should be able to link a payment from my anonymous ethereum wallet to my real life identity”) etc? 
</p>
<p>Formal verification is a technique by which we can comprehensively analyze a security protocol for bugs, and be assured that the protocol does satisfy the guarantees required of it. In this course, we will study how to formally model security protocols using various abstract systems, and how to express and verify properties over such models. In addition, since verification by hand is cumbersome and often error-prone, we will study tools that can be used to automate the process. We will study how this analysis, which is based mostly in abstract logic and theoretical computer science, fits into the engineering workflow of a protocol going from design to deployment, and what challenges arise during this process. While this course concentrates on the formal analysis and verification of security protocols, many of the techniques used here provide a good introduction to the field of formal verification as a whole.</p>

<br>

<header>
    <h2> Who should take this course? </h2>
</header>
<p>
This course is for you if 
<ul>
    <li><p>you have ever wondered how some messaging system like Signal or Whatsapp actually ensures that messages are "end-to-end encrypted", or</p></li>
    <li><p>you worry about whether our circuitous and confusing banking systems *really* are as secure and correct as one would hope and expect, or</p></li>
    <li><p>you want to learn more about how security protocols are developed and proved correct, or</p></li>
    <li><p>you just have an interest in combining abstract tools like logic and automata theory with programming to solve real life problems.</p></li>
</ul>
</p>

<br>

<header>
    <h2> Prerequisites </h2>
</header>
<p> This course is structured such that the first few weeks will be devoted to very theoretical material, upon which the programming part of the course will heavily depend. Grasping the former will require some mathematical acumen -- students should, at the very least, be able to write and understand rigorous formal proofs, especially those involving induction. Students will also be required to be conversant with basic concepts of syntax/semantics, automata theory, and algorithms. A basic idea of complexity theory is also necessary; notions like reductions and NP-completeness should not seem unfamiliar. You must have taken the following courses at IIT Delhi:
<ul>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL202">COL202 (Discrete Mathematical Structures)</a>, and</p></li>
    <li><p><a href="https://www.cse.iitd.ac.in/cse/newcurriculum-contents/newcourses.html#COL352">COL352 (Introduction to Automata & Theory of Computation)</a>.</p></li>
</ul>
</p>
<p>
It will help if you have also taken COL703 (Logic for Computer Science), but this is not a hard prerequisite. If you do not fulfil the above prerequisites, but think you have the necessary background to attend this course, feel free to get in touch over email.
</p>

<br>

<header>
    <h2> Reference Material </h2>
</header>
<p> Mostly notes and papers, some snippets from other published material. TBA.</p>

<br>

<header>
    <h2> Evaluation Policy </h2>
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

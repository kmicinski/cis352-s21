---
title: Syllabus
layout: default
---

## Programming Languages: Theory and Practice
(*CIS 352* at Syracuse U)

**Note**: parts of this syllabus are subject to change with adequate
notice to students.

An introduction to the design and implementation of programming
languages, focused on operational semantics and interpreters. This
course is heavily project-focused and usees a specification-based
grading rubric to teach both formal (written) and practical (coding)
skills.

**Workload**:
  - Asynchronous video lecture units (at most ~80min per week)
  - Participation points:
    - Quiz before each lecture (closes as lecture begins)
    - See other sources of participation below
  - 6 projects
  - 3 quizzes and a final, all cumulative (see grading note).
  - This will be a project intensive class. Approximately 6-10
    hours per week *outside* of class will be expected from
    students. I recommend against taking this course concurrent with
    other project-heavy courses.

## Grading

CIS352 employs a *specification-based grading* methodology. There are
three categories of assignments:

- Participation Credit (at least 30+ available)
  - &gt;50% participation quiz (on Blackboard) before each class gives 1 point, closes when class begins.
  - Volunteering to livecode in class gives 2 points. Students are
    encouraged to present, and we will work to establish a positive
    environment where all students can make progress even if they
    don't at first succeed. However, if you feel you simply cannot
    livecode in class you may ask me about doing some individualized
    programming instruction with the TAs / instructor instead.
  - "Introduce yourself" to class (1 minute answer to question) gives 1 point.
  - "Meet your professor" to discuss career goals gives 1 point.
  - Groups that present answers to in-class questions will receive 1 point.
- 6 programming projects
  - Projects are assigned throughout the term. All projects are due at
    11:59PM the last day of classes at SU (Friday, May 14, 2021 at
    11:59PM US Eastern Time).
  - 1 participation point will be awarded to all students who have &gt;50% test completion within 10 days of project handout.
  - Projects will be graded via the autograder.
- 12 exam questions
  - There are three 60-minute quizzes and one 120-minute exam.
  - *All* quizzes / exams will be cumulative.
  - Exam questions will all be derived from the [written learning
    objectives]({{ "/learning-objectives" | absolute_url }}) for
    CIS352.

### Informal Grading Rules for CIS352

<div class="container">
  <div class="row">
    <div class="leftside">
      <table class="table table-sm table-striped grade-table table-hover">
        <thead>
          <tr class="gradestop">
            <th class="projdesc" colspan="3" scope="col"><strong>Projects</strong></th>
            <th class="examdesc" colspan="2" scope="col"><strong>Exam Questions</strong></th>
            <th scope="col">Grade</th>
          </tr>
          <tr class="gradestop">
            <th class="smhgradecol" scope="col">Minimal</th>
            <th class="smhgradecol" scope="col">Satisfactory</th>
            <th class="lghgradecol" scope="col">Excellent</th>
            <th class="smhgradecol" scope="col">Satisfactory</th>
            <th class="lghgradecol" scope="col">Excellent</th>
            <th scope="col"></th>
          </tr>
        </thead>
        <tbody>
          <tr id="gradea">
            <td class="smgradecol">6/6</td>
            <td class="smgradecol">5/6</td>
            <td class="lggradecol">3/6</td>
            <td class="smgradecol">12/12</td>
            <td class="lggradecol">6/12</td>
            <th scope="row">A</th>
          </tr>
          <tr id="gradeam">
            <td class="smgradecol">5/6</td>
            <td class="smgradecol">5/6</td>
            <td class="lggradecol">2/6</td>
            <td class="smgradecol">11/12</td>
            <td class="lggradecol">5/12</td>
            <th scope="row">A-</th>
          </tr>
          <tr>
            <td class="smgradecol">4/6</td>
            <td class="smgradecol">4/6</td>
            <td class="lggradecol">2/6</td>
            <td class="smgradecol">10/12</td>
            <td class="lggradecol">5/12</td>
            <th scope="row">B+</th>
          </tr>
          <tr>
            <td class="smgradecol">4/6</td>
            <td class="smgradecol">3/6</td>
            <td class="lggradecol">1/6</td>
            <td class="smgradecol">9/12</td>
            <td class="lggradecol">4/12</td>
            <th scope="row">B</th>
          </tr>
          <tr>
            <td class="smgradecol">4/6</td>
            <td class="smgradecol">3/6</td>
            <td class="lggradecol">1/6</td>
            <td class="smgradecol">9/12</td>
            <td class="lggradecol">3/12</td>
            <th scope="row">B-</th>
          </tr>
          <tr>
            <td class="smgradecol">3/6</td>
            <td class="smgradecol">2/6</td>
            <td class="lggradecol">1/6</td>
            <td class="smgradecol">8/12</td>
            <td class="lggradecol">2/12</td>
            <th scope="row">C+</th>
          </tr>
          <tr>
            <td class="smgradecol">3/6</td>
            <td class="smgradecol">3/6</td>
            <td class="lggradecol">1/6</td>
            <td class="smgradecol">8/12</td>
            <td class="lggradecol">1/12</td>
            <th scope="row">C</th>
          </tr>
          <tr>
            <td class="smgradecol">3/6</td>
            <td class="smgradecol">3/6</td>
            <td class="lggradecol">0/6</td>
            <td class="smgradecol">8/12</td>
            <td class="lggradecol">0/12</td>
            <th scope="row">C-</th>
          </tr>
          <tr>
            <td class="smgradecol">3/6</td>
            <td class="smgradecol">2/6</td>
            <td class="lggradecol">0/6</td>
            <td class="smgradecol">6/12</td>
            <td class="lggradecol">0/12</td>
            <th scope="row">D</th>
          </tr>
          <tr>
            <td class="smgradecol">&lt; 3/6</td>
            <td class="smgradecol">&lt; 3/6</td>
            <td class="lggradecol">0/6</td>
            <td class="smgradecol">&lt; 7/12</td>
            <td class="lggradecol">0/12</td>
            <th scope="row">&lt;D</th>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="rightside">
      <!-- <div id="projectquestions"> -->
      <!--   <h5 class="pcardtitle">Projects</h5> -->
      <!--   <div id="projects" class="egrade" grade="A"> -->
      <!--     <svg width="100" height="100" viewPort="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg"> -->
      <!--       <circle class="pfail" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       <circle class="pminimal" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       <circle class="psat" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       <circle class="pex" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--     </svg> -->
      <!--   </div> -->
      <!--   <p class="points"> -->
      <!--     3 <strong class="ex">Excellent</strong> -->
      <!--     &nbsp;5 <strong class="sat">Satisfactory</strong> -->
      <!--   </p> -->
      <!--   <p class="points" id="min">6 <strong class="min">Minimal</strong></p> -->
      <!-- </div> -->
      <!-- <div> -->
      <!--   <div id="examquestions"> -->
      <!--     <h5 class="pcardtitle">Exam Questions</h5> -->
      <!--     <div id="exams" class="egrade" grade="A"> -->
      <!--       <svg grade="A" class="gpa" width="100" height="100" viewPort="0 0 100 100" version="1.1" xmlns="http://www.w3.org/2000/svg"> -->
      <!--         <circle class="efail" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--         <circle class="esat" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--         <circle class="eex" r="40" cx="50" cy="50" fill="transparent" stroke-dashoffset="0"></circle> -->
      <!--       </svg> -->
      <!--     </div> -->
      <!--     <p class="points"> -->
      <!--       6 <strong class="ex">Excellent</strong> -->
      <!--       &nbsp;12 <strong class="sat">Satisfactory</strong> -->
      <!--     </p> -->
      <!--   </div> -->
      <!-- </div> -->

      <table class="table table-sm table-striped grade-table participation">
        <thead>
          <tr class="gradestop">
            <th scope="col"><strong>Participation</strong></th>
            <th scope="col"><strong>GPA Δ</strong></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="smgradecol">&lt; 20</td>
            <th scope="row">-</th>
          </tr>
          <tr>
            <td class="smgradecol">&geq; 20 &ndash; &lt; 30</td>
            <th scope="row">=</th>
          </tr>
          <tr>
            <td class="smgradecol">&geq; 30</td>
            <th scope="row">+</th>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>

<!-- <script> -->
<!-- $(document).ready(function() { -->
<!--   window.update_gpa = function(p0,p1,p2,e0,e1) { -->
<!--     var update = function(id,num,tot) { -->
<!--       var r = id.attr('r'); -->
<!--       var c = Math.PI*(r*2); -->
<!--       var doffset = (1-(num/tot))*c; -->
<!--       id.css({'stroke-dasharray': `${c} ${c}`}); -->
<!--       id.css({'stroke-dashoffset': `${circumference}`}); -->


<!-- id.css({ 'stroke-dasharray': doffset}) -->
<!--     } -->
<!--     update($('.pminimal'),p0,6); -->
<!--     update($('.psat'),p1,6); -->
<!--     update($('.pex'),p2,6); -->
<!--     update($('.esat'),e0,12); -->
<!--     update($('.eex'),e1,12); -->
<!--   } -->
<!--   $('#gradea').hover(function() { window.update_gpa(6,5,3,12,6); }); -->
<!--   $('#gradeam').hover(function() { window.update_gpa(5,5,2,11,5); }); -->
<!--   $('#gradebp').hover(function() { window.update_gpa(4,4,2,10,5); }); -->
<!-- }); -->
<!-- </script> -->

- Your grade consists of participation, projects, and quiz / exam
  questions.
- The bulk of this is projects and exams, and most of your time will
  be spent on projects.
- Projects are graded as either non-satisfactory,
  minimally-satisfactory, satisfactory, or excellent.
- Projects are graded via the autograder. You may submit as many times
  as you like up until 11:59PM on the last day of class (Friday, May
  14 at 11:59PM). However, the autograder will rate-limit you by
  providing you with a set number of tokens per day. Specs for
  minimal, satisfactory, and excellent are given on a per-project
  basis.
- There are 12 quiz / exam questions, and every exam is cumulative. If
  you miss a question on Q0, you can reattempt the same learning
  outcome (e.g., basic recursion) on Q1 and so on.
- However, students may only submit up to six answers for each quiz / exam.
- Quizzes are 60 minutes, and include questions for each learning
  objective covered in the course so far. The final is cumulative and
  is scheduled for 120 minutes. While you may still submit only six
  new answers, the expanded time may give you time to refine excellent
  solutions.
- Based on the above, you may represent your project grade as a
  three-tuple (p₀,p₁,p₂) where p₀ specifies the number of minimal
  projects, p₁ the number of satisfactory, and p₂ the number of
  excellent projects you have submitted. Remember that each
  satisfactory project is also minimally-satisfactory and so on.
- Similarly, exam questions may be represented as a pair (e₀,e₁) where
  e₀ represents the number of satisfactory solutions and e₁ represents
  the number of excellent solutions.
- Using the project grade (p₀,p₁,p₂) and exam grades (e₀,e₁) you may
  calculate a raw gradepoint using the table below. The final
  gradepoint is given by taking a minus of the raw gradepoint (e.g.,
  decreasing 4.0 to 3.7) if participation points are < 20, make no
  change if participation points are > 20 but < 30, and add a plus
  (e.g., bumping 3.7 to 4.0) if participation grade is ≥ 30. Note that
  assigned grades cannot go above 4.0, but the instructor will track
  this for recommendation letters and references.




<!-- ## Course Overview -->

<!-- This course will introduce many of the principles of programming -->
<!-- language design and implementation. We will discuss numerous features -->
<!-- of several programming languages and the algorithms and data -->
<!-- structures that are needed to provide these features. Projects will -->
<!-- cover both the use of various features and high-level understanding -->
<!-- the algorithms and data structures involved in their -->
<!-- implementation. -->

<!-- Lectures and labs will include examples (and exercises) in Racket. No -->
<!-- prior knowledge of Racket is needed for this course, but students -->
<!-- should be familiar with the programming techniques from their -->
<!-- lower-level courses and possess fluency in basic functional -->
<!-- programming. -->

<!-- ## Grading -->

<!-- - Projects: 56% -->
<!-- - Exams: 44% -->
<!--   - Midterm: 14% -->
<!--   - Final: 20% -->
<!--   - Coding Exam 0: 5% -->
<!--   - Coding Exam 1: 5% -->

<!-- ## Grade cutoffs -->

<!-- These are rough grade cutoffs. I never fit grade distributions to a -->
<!-- normal curve (e.g., specifying that only 10% of students may earn an -->
<!-- A), however I may choose to lower the bar for some letter grades. I -->
<!-- will not curve assignments or projects. -->

<!-- - 93% -- A -->
<!-- - 89% -- A- -->
<!-- - 84% -- B+ -->
<!-- - 80% -- B -->
<!-- - 77% -- B- -->
<!-- - 74% -- C+ -->
<!-- - 70% -- C -->
<!-- - 65% -- C- -->
<!-- - 55% -- D -->
<!-- - 0%  -- F -->


<!-- ## Autograder -->

<!-- Projects in this course will be graded by an automatic grader. We may -->
<!-- adjust projects so that portions of the projects include style-based -->
<!-- grading, though we will *not* employ subjective grading. More -->
<!-- pointedly: we will *not* award partial credit for solutions that have -->
<!-- the right ideas but do not pass our tests. -->

<!-- ## Late Projects and Extensions -->

<!-- I used to extend project deadlines, but I have found that this is -->
<!-- often unfair to the students who start on time (and more students than -->
<!-- I would have thought have raised this point to me -->
<!-- privately). Therefore, project extensions will be rare--and only in -->
<!-- the event of things such as university closures. Project extensions -->
<!-- for students will not be granted except for religious observances and -->
<!-- extenuating circumstances (family illness, etc..). The late policy is -->
<!-- as follows: -->

<!-- - Projects turned in on time will earn a maximum of 100% -->

<!-- - Projects turned in up to 72 hours late will have a 15% penalty -->
<!--   applied. -->

<!-- - Projects turned in after 72 hours late (until the end of the term) -->
<!--   will have a 30% penalty applied. -->

<!-- - Your project grade always be the maximum possible. For example, -->
<!--   let's say you make an on-time project submission for 60%, but the -->
<!--   next day you turn in a project which earns an 75%. This submission -->
<!--   would earn a 63.75%. Five days after the deadline you turn in a -->
<!--   project earning 100%. Your final score is 70%, as the 70% (100% with -->
<!--   a 30% penalty) still got the maximum grade of any submission. -->

<!-- You *should* be able to earn **at least** a 70% on all of the projects -->
<!-- with enough work. -->

<!-- ## Topics -->

<!-- We will plan to cover all of the following, though some may be dropped -->
<!-- for time: -->

<!-- - Programming in Racket -->
<!-- - Higher-order functions -->
<!-- - Execution models and their impact on the stack -->
<!-- - Pattern matching -->
<!-- - Immutable data structures -->
<!-- - Okasaki-style immutable queues -->
<!-- - Immutable binary trees -->
<!-- - Quad-trees -->
<!-- - Static scope -->
<!-- - Dynamic scope -->
<!-- - Lambda calculus -->
<!-- - Textual-reduction semantics -->
<!-- - Big-step semantics (CE-style evaluators) -->
<!-- - Metacircular interpreters -->
<!-- - Church encoding -->
<!-- - Control and continuations -->
<!-- - Abstract machines -->
<!-- - The CEK machine -->
<!-- - A-Normal Form -->
<!-- - Continuation-passing style -->
<!-- - Top-down parsing -->
<!-- - State-passing style -->
<!-- - Simply-typed lambda calculus -->
<!-- - Type inference -->
<!-- - Hygienic macros -->
<!-- - Logic programming -->
<!-- - MiniKanren -->

## Projects and Labs

This course will have six individual projects. Each of these will be
completed using the course's autograder. Projects will be handed out
every few weeks, starting after the second or third week of class. All
projects are due at 11:59PM the last day of class.

Labs will be led by the TA or instructor to facilitate studying and
reviewing material presented in lecture.

## Collaboration and the Honor Code

- Assignments and exams must be completed alone, without exception.

- Specifically, you must never send your code to anyone or allow
  anyone to watch you code, obtain your code, study your code, copy
  your code, etc... We expect you will take reasonable precautious to
  ensure the secrecy of your solutions.

- The autograder employs elaborate cheat-detection techniques. These
  techniques will compare your code to other students' submissions,
  along with students from previous years. The TAs will be using these
  features to periodically scan for students who are cheating. Past
  experience shows us that this system is very robust, and has allowed
  us to detect several large clusters of collaborating students. We
  hope that specification-based grading will assuage this.

- All apparent cases (with credible evidence, as determined by lead
  instructor) of academic dishonesty will be reported, even if the
  student believes they made an honest mistake, or no mistake at
  all. We understand honor violations are stressful processes, and
  thus we strive to only submit honor code cases when we believe there
  is clear evidence that the honor board should review our findings
  independently.

- You may collaborate, to any degree you want, with anyone (even
  outside of your group) on participation coding exercises. These will
  be clearly labeled, and are specifically not the course projects
  (which explicitly disallow any form of collaboration).

- While we recommend you discuss the project specification with your
  peers, you should basically never be getting help from peers about
  your code. In particular, you should never be showing another
  student your project code. If you do discuss coding about the
  project with another student, it should only be in the abstract
  (e.g., "can you use operator overloading to implement that?" or "do
  you think it would be sensible to implement this with `map`?") and
  not particularized to your codebase. We understand that this can be
  a challenging line to walk, and thus, we recommend the following
  heuristic: when talking to other students about code, discuss mostly
  the in-class exercises and participation coding exercises.

- Cite all help other than the professor, T.A., and
  required/recommended text (you are allowed to cite those if you
  wish, but it is not required unless you are specifically told
  otherwise); note that proper citation is sufficient to avoid any
  charge of academic dishonesty, and we will not be particularly
  focused on copyright law during lab work.

**Again**: You should **never** share code with another student. This
  includes both sending a file to another student and "over the
  shoulder" copying (even when, e.g., variable names are changed,
  etc..). In the eyes of the instructor, these are both equally
  bad. You should never be sitting and helping another along by
  writing their code. By doing so you are both violating the honor
  policy and disadvanting the student you are helping (as they may not
  then properly learn the material).

## Student Support

Syracuse University values diversity and inclusion; we are committed
to a climate of mutual respect and full participation. There may be
aspects of the instruction or design of this course that result in
barriers to your inclusion and full participation in this course. I
invite any student to meet with me to discuss strategies and/or
accommodations (academic adjustments) that may be essential to your
success and to collaborate with the Office of Disability Services
(ODS) in this process.

If you would like to discuss disability-accommodations or register
with ODS, please visit their website at
http://disabilityservices.syr.edu. Please call (315) 443-4498 or email
disabilityservices@syr.edu for more detailed information.

ODS is responsible for coordinating disability-related academic
accommodations and will work with the student to develop an access
plan. Since academic accommodations may require early planning and
generally are not provided retroactively, please contact ODS as soon
as possible to begin this process.

## Accreditation

As part of the regular ABET accreditation process for the
undergraduate program in computer science, we may be collecting
samples of students' work in each of our undergraduate classes.  As a
result, some of your labs/homeworks/exams may be photocopied/scanned
(or electronically copied) to be presented for accreditation at some
later point.

## Student Mental Health

Mental health and overall well-being are significant predictors of
academic success. As such it is essential that during your college
experience you develop the skills and resources effectively to
navigate stress, anxiety, depression and other mental health
concerns. Please familiarize yourself with the range of resources the
Barnes Center provides (https://ese.syr.edu/bewell) and seek out
support for mental health concerns as needed. Counseling services are
available 24/7, 365 days a year, at 315.443.8000.

## Discrimination and Harassment

The University does not discriminate and prohibits harassment or
discrimination related to any protected category including creed,
ethnicity, citizenship, sexual orientation, national origin, sex,
gender, pregnancy, disability, marital status, age, race, color,
veteran status, military status, religion, sexual orientation,
domestic violence status, genetic information, gender identity, gender
expression or perceived gender.

Any complaint of discrimination or harassment related to any of these
protected bases should be reported to Sheila Johnson-Willis, the
Universitys Chief Equal Opportunity & Title IX Officer. She is
responsible for coordinating compliance efforts under various laws
including Titles VI, VII, IX and Section 504 of the Rehabilitation
Act. She can be contacted at Equal Opportunity, Inclusion, and
Resolution Services, 005 Steele Hall, Syracuse University, Syracuse,
NY 13244-1120; by email: titleix@syr.edu; or by telephone:
315-443-0211.

If you notice any incidents of harassment or discrimination, however
minor, please email me. You may wish to use an anonymous email service
such as https://anonymousemail.me/. Please feel free to tell me as
much as you feel comfortable.  I am a mandatory Title IX reporter and
must report incidents such as sexual harassment, relationship
violence, stalking, etc...

## Slack

Slack is an instant messaging app for teams. We'll be using it for
most course management. This is the best place to get in touch with me
for one-off questions, ask for an appointment for office hours,
etc.. Email me if you have not been invited to the course Slack.

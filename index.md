---
layout: mainpage
---

<!-- ## Upcoming deadlines -->

<!-- <ul class="due-list"> -->
<!-- {% for post in site.posts %} -->
<!--     {% capture nowunix %}{{'now' | date: '%s'}}{% endcapture %} -->
<!--     {% capture duetime %}{{post.due | date: '%s'}}{% endcapture %} -->
<!--     {% if post.categories contains 'assignment' and duetime > nowunix %} -->
<!--     <li> -->
<!--        <span><span class="post-meta"><b>(Due <span itemprop="date">{{ post.due | date: "%b %-d, %Y" }}</span>)</b></span><a class="mainpage-asn-link" href="{{ post.url | absolute_url }}">{{ post.title }}</a></span></li> -->
<!--    {% endif %} -->
<!-- {% endfor %} -->
<!-- </ul> -->

<!-- <div class="container"> -->
<!--     <div class="row"> -->
<!--     <div class="col"> -->
<!--     lkjasdf  -->
<!--     </div> -->
<!--     <div class="col"> -->
<!--     lkjsdf -->
<!--     </div> -->
<!--     </div> -->
<!-- </div> -->

<!-- <div class="infomatter"> -->
<!-- <table class="infotablestyle"> -->
<!-- <tr><td>Course Number</td> -->
<!--     <td>CIS 352 (Spring 2020) at Syracuse</td> -->
<!-- </tr> -->
<!-- <tr><td>Instructor</td> -->
<!--     <td><a href="http://kmicinski.com">Kristopher Micinski</a> </td> -->
<!-- </tr> -->
<!-- <tr><td></td> -->
<!--     <td>(<tt>kkmicins@syr.edu</tt>)</td> -->
<!-- </tr> -->
<!-- <tr><td>Teaching Assistants</td> -->
<!--     <td>Jack Vining (<tt>jcvining@syr.edu</tt>)</td> -->
<!-- </tr> -->
<!-- <tr> -->
<!--     <td></td> -->
<!--     <td>Yihao Sun (<tt>ysun67@syr.edu</tt>)</td> -->
<!-- </tr> -->
<!-- <tr> -->
<!--     <td>Times</td> -->
<!--     <td>Tu/Th 11:00-12:20 <i>Lecture</i>  Monday <i>Labs</i></td> -->
<!-- </tr> -->
<!-- <tr> -->
<!--     <td>Professor Office Hours</td> -->
<!--     <td>Th 9-11AM or by appt.</td> -->
<!-- </tr> -->
<!-- <tr> -->
<!--     <td>TA Office Hours</td> -->
<!--     <td>Tu 9-11AM, 1-3PM. Th 2-4PM</td> -->
<!-- </tr> -->
<!-- </table> -->
<!-- <\!-- <img class="krispic" src="/assets/img/krisbw.jpg"> -\-> -->
<!-- </div> -->
    

<!-- ## Introduction  -->

<!-- The purpose of this course is to help you understand how to leverage -->
<!-- the semantics programming languages to write the clearest and most -->
<!-- obviously-correct programs you can. We will begin by introducing you -->
<!-- to a new language, [Racket](https://racket-lang.org/). Racket is an -->
<!-- untyped functional language that harmoniously mixes code and data to -->
<!-- allow succinct and expressive programs. We will use Racket as a means -->
<!-- to teach good functional programming style and reflect upon how our -->
<!-- decisions impact the quality of our code. While doing this we will -->
<!-- highlight several foundational concepts whose implications go far -->
<!-- beyond Racket, such as operational semantics and the Lambda calculus. -->

<!-- After bringing students to fluency in functional programming, we will -->
<!-- use Racket to build several different languages. The languages we -->
<!-- build will be relatively small (compared to, say, C), but will be -->
<!-- nonetheless expressive, allowing us to write quite impressive programs -->
<!-- in languages we built ourselves. We will explore different ways of -->
<!-- defining programming language semantics while remarking upon the -->
<!-- implications of these choices in our day-to-day programming (even in -->
<!-- languages beyond Racket, such as JavaScript, C++, Rust, etc...). -->

<!-- ## Course Structure -->

<!-- Please read the [Syllabus]({{ "/syllabus" | absolute_url }}) for course information. -->

<table class="table table-sm table-striped">
  <thead>
    <tr>
      <th scope="col">Date</th>
      <th scope="col">Type</th>
      <th scope="col">Unit</th>
      <th scope="col">Video</th>
    </tr>
  </thead>
  <tbody>
    <tr class="table-success">
      <th scope="row">2/9</th>
      <td>Logistics</td>
      <td></td>
      <td><a href="https://www.youtube.com/watch?v=CrCRTFvJWoQ">Course Introduction and Logistics</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/9</th>
      <td>Lecture</td>
      <td>L0</td>
      <td><a href="https://www.youtube.com/watch?v=j63O7A-ZKHk">Introduction to Racket and Dr. Racket</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/11</th>
      <td>Lecture</td>
      <td>L1</td>
      <td><a href="https://www.youtube.com/watch?v=kMOgrVjEuk8">Racket Forms and Callsites</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/11</th>
      <td>Lecture</td>
      <td>L2</td>
      <td><a href="https://www.youtube.com/watch?v=bnzjganKVgU">Definitions and the Environment</a></td>
    </tr>
    <tr class="table-secondary">
      <th scope="row">2/9 &ndash;</th>
      <td>Reading</td>
      <td>R0</td>
      <td><a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-10.html#%_sec_1.1">SICP sections 1 through 1.1.5 (stop before 1.1.6)</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/16</th>
      <td>Lecture</td>
      <td>L3</td>
      <td><a href="https://www.youtube.com/watch?v=mwIF8cAn30I&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=5">Textual Reduction</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/16</th>
      <td>Lecture</td>
      <td>L4</td>
      <td><a href="https://www.youtube.com/watch?v=WVmomIoxBZM&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=6">Case Splitting and Lists Intro</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/18</th>
      <td>Lecture</td>
      <td>L5</td>
      <td><a href="https://www.youtube.com/watch?v=0y325A82vMc&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=7">Recursion over Lists</a></td>
    </tr>
    <tr class="table-success">
      <th scope="row">2/18</th>
      <td>Logistics</td>
      <td></td>
      <td>Using the Autograder</td>
    </tr>
    <tr class="table-warning">
      <th scope="row">2/18</th>
      <td>Project</td>
      <td>P0</td>
      <td>Tic-Tac-Toe</td>
    </tr>
    <tr class="table-secondary">
      <th scope="row">2/16 &ndash;</th>
      <td>Reading</td>
      <td>R1</td>
      <td>SICP sections <a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-10.html#%_sec_1.1.6">1.1.6</a>  and <a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-11.html#%_sec_1.2">1.2 up to 1.2.3</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/23</th>
      <td>Lecture</td>
      <td>L6</td>
      <td><a href="https://www.youtube.com/watch?v=OqZleNZto0A&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=8">Lambdas</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/25</th>
      <td>Lecture</td>
      <td>L7</td>
      <td><a href="https://www.youtube.com/watch?v=7NA9HZdlR0g&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=9">Cons Diagrams and Boxes</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">2/25</th>
      <td>Lecture</td>
      <td>L8</td>
      <td><a href="https://www.youtube.com/watch?v=AGDnCUfFp84&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=10">Mapping Over Lists</a></td>
    </tr>
    <tr class="table-secondary">
      <th scope="row">2/23 &ndash;</th>
      <td>Reading</td>
      <td>R2</td>
      <td><a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-12.html#%_sec_1.3">SICP section  1.3</a> and <a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-14.html#%_sec_2.1">2.1</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/2</th>
      <td>Lecture</td>
      <td>L9</td>
      <td><a href="https://www.youtube.com/watch?v=RJFkmh9Wo8o">Pattern Matching</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/4</th>
      <td>Lecture</td>
      <td>L10</td>
      <td><a href="https://www.youtube.com/watch?v=kAskgLplQgw">Tail Calls and Tail Recursion</a></td>
    </tr>
    <tr class="table-secondary">
      <th scope="row">3/2 &ndash;</th>
      <td>Reading</td>
      <td>R3</td>
      <td>SICP sections <a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-15.html">2.2</a> and <a href="https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book-Z-H-16.html#%_sec_2.3">2.3</a></td>
    </tr>
    <tr class="table-danger">
      <th scope="row">3/8</th>
      <td>Quiz</td>
      <td>Q0</td>
      <td>Online Synchronous Quiz 0 (80min)</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/9</th>
      <td>Lecture</td>
      <td>L11</td>
      <td><a href="https://www.youtube.com/watch?v=cFkHFoKW4e4&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=14">Practicing Tail Recursion</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/9</th>
      <td>Lecture</td>
      <td>L12</td>
      <td><a href="https://www.youtube.com/watch?v=WUAI_v110NQ&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=15">Folding over Lists</a></td>
    </tr>
    <tr class="table-warning">
      <th scope="row">3/11</th>
      <td>Project</td>
      <td>P1</td>
      <td><a href="https://www.youtube.com/watch?v=wWpu6UDYhc4&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=19">PageRank</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/16</th>
      <td>Lecture</td>
      <td>L13</td>
      <td><a href="https://www.youtube.com/watch?v=vhOH2GmuYrQ&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=16">Interpreting IfArith</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/18</th>
      <td>Lecture</td>
      <td>L14</td>
      <td><a href="https://www.youtube.com/watch?v=neCrsTf8h7Y&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=17">Natural Deduction for IfArith</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/23</th>
      <td></td>
      <td></td>
      <td><b>SU Wellness Day (No Class)</b></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/25</th>
      <td>Lecture</td>
      <td>L15</td>
      <td><a href="https://www.youtube.com/watch?v=Qq5Bzpsoi7k&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=18">Small-Step Semantics of IfArith</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/30</th>
      <td>Lecture</td>
      <td>L16</td>
      <td><a href="https://www.youtube.com/watch?v=RqA-m_QMJYc&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=20">Lambda Calculus Introduction</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">3/30</th>
      <td>Lecture</td>
      <td>L17</td>
      <td><a href="https://www.youtube.com/watch?v=Paxvaq0Q-S0&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=21">Lambda Calculus: Reductions and Substitution</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/1</th>
      <td>Lecture</td>
      <td>L18</td>
      <td><a href="https://www.youtube.com/watch?v=GNkQrqAGB-o&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=22">Reduction Strategies</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/6</th>
      <td>Lecture</td>
      <td>L19</td>
      <td><a href="https://www.youtube.com/watch?v=DC-9wWgXQTc&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=23">Church Numerals</a></td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/8</th>
      <td>Lecture</td>
      <td>P2</td>
      <td><a href="https://www.youtube.com/watch?v=izfoxmSAQ28&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=24">Church Encoding</a></td>
    </tr>
    <tr class="table-danger">
      <th scope="row">4/12</th>
      <td>Quiz</td>
      <td>Q1</td>
      <td>Online Synchronous Quiz 1 (100min)</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/13</th>
      <td>Lecture</td>
      <td></td>
      <td>Review / catch up day on lambda calculus</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/15</th>
      <td>Lecture</td>
      <td>L20</td>
      <td>Fixed-Point Combinators</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/20</th>
      <td>Lecture</td>
      <td>L21</td>
      <td>Continuations Introduction</td>
    </tr>
    <tr class="table-warning">
      <th scope="row">4/20</th>
      <td>Project</td>
      <td>P3</td>
      <td>Definitional Interpreter</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/22</th>
      <td>Lecture</td>
      <td>L22</td>
      <td>Continuation Passing Style</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/27</th>
      <td>Lecture</td>
      <td>L23</td>
      <td>Continuations Example</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">4/27</th>
      <td>Lecture</td>
      <td>L24</td>
      <td>Control-Flow Constructs via Continuations</td>
    </tr>
    <tr class="table-warning">
      <th scope="row">4/29</th>
      <td>Project</td>
      <td>P4</td>
      <td>Stack-Passing Interpreter (CEK Machine)</td>
    </tr>
    <tr class="table-warning">
      <th scope="row">4/29</th>
      <td>Project</td>
      <td>P5</td>
      <td>Symbolic Execution for LoopArray</td>
    </tr>
    <tr class="table-danger">
      <th scope="row">5/3</th>
      <td>Quiz</td>
      <td>Q2</td>
      <td>Online Synchronous Quiz 2 (100min)</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/4</th>
      <td>Lecture</td>
      <td>L43</td>
      <td>Types Introduction</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/4</th>
      <td>Lecture</td>
      <td>L44</td>
      <td>Simply-Typed Lambda Calculus</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/6</th>
      <td>Lecture</td>
      <td>L45</td>
      <td>Defining Type Soundness for STLC</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/6</th>
      <td>Lecture</td>
      <td>L46</td>
      <td>Proving Type Soundness via Progress and Preservation</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/11</th>
      <td>Lecture</td>
      <td>L47</td>
      <td>Curry-Howard Correspondence, Programs-as-Proofs</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/11</th>
      <td>Lecture</td>
      <td>L48</td>
      <td>Example: Certified Programming in Idris2</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/13</th>
      <td>Lecture</td>
      <td>L49</td>
      <td>Macros and Hygiene</td>
    </tr>
    <tr class="table-primary">
      <th scope="row">5/13</th>
      <td>Lecture</td>
      <td>L50</td>
      <td>Massively-Parallel Deductive Databases</td>
    </tr>
    <tr class="table-danger">
      <th scope="row">TBA</th>
      <td>Exam</td>
      <td>F</td>
      <td>Final (120min, comprehensive, submit up to 6 answers)</td>
    </tr>


  </tbody>
</table>


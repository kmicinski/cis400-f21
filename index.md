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
      <th scope="row">8/31</th>
      <td>Lecture</td>
      <td>L1</td>
      <td>Course Introduction (<a href="{{ '/assets/slides/lec0.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/lec0.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>)</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/1</th>
      <td>Lecture</td>
      <td>L2</td>
      <td>Case splitting and lists intro (<a href="https://www.youtube.com/watch?v=WVmomIoxBZM&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=6">L4 of 352</a>) and recursion over lists (<a href="https://www.youtube.com/watch?v=0y325A82vMc&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG&index=7">L5 of 352</a>)</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/7</th>
      <td>Lecture</td>
      <td>L3</td>
      <td>Racket boot-up</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/9</th>
      <td>Lecture</td>
      <td>L4</td>
      <td>IfArith Intro, Racket-based interpreter (<a href="{{ '/assets/slides/ifarith-intro.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/ifarith-intro.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>)</td>
    </tr>
    <tr class="table-info">
      <th scope="row">9/9</th>
      <td>Lecture</td>
      <td>L4</td>
      <td><a href="https://gist.github.com/kmicinski/83dc13db32f1aecf6207c4cb10de8d73">Livecoding from L4</a></td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/14</th>
      <td>Lecture</td>
      <td>L5</td>
      <td>Lambda Calculus Intro (<a href="{{ '/assets/slides/lambda-calculus.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/lambda-calculus.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>)</td>
    </tr>
    <tr class="table-info">
      <th scope="row">9/14</th>
      <td>Livecoding</td>
      <td>L5</td>
      <td>Lambda Calculus Livecoding (<a href="https://gist.github.com/kmicinski/48d3dc59285667119962e0546cfeb452">starter code</a>)</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/16</th>
      <td>Lecture</td>
      <td>L6</td>
	  <td>Alpha/eta subst., Capture-Avoiding Substitition, reduction strategies</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/21</th>
      <td>Lecture</td>
      <td>L7</td>
	  <td>Desugaring LetRec (Project 2) (<a href="{{ '/assets/slides/letrec.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/letrec.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>)</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/23</th>
      <td>Lecture</td>
      <td>L8</td>
	  <td>Closures and Closure-Creating Interpreters (<a href="{{ '/assets/slides/closures.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/closures.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>)</td>
    </tr>
    <tr class="table-success">
      <th scope="row">9/28</th>
      <td>Lecture</td>
      <td>L9</td>
	  <td><a href="https://www.youtube.com/watch?v=K-AhJgjb-8s&list=PLXaqTeMx01E-l20YhTNwN4xncM-1jweqG">Continuations and call/cc (video)</a>Additional (in-class) slides (<a href="{{ '/assets/slides/continuations.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/continuations.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>) </td>
    </tr>
    <tr class="table-success">
      <th scope="row">..</th>
      <td>Lecture</td>
      <td>L10</td>
	  <td>Implementing call/cc and the CEK machine (<a href="{{ '/assets/slides/cek.pdf' | prepend: site.baseurl | prepend: site.url }}">PDF</a> and <a href="{{ '/assets/slides/cek.key' | prepend: site.baseurl | prepend: site.url }}">.key</a>)</td>
    </tr>
    <tr class="table-success">
      <th scope="row">..</th>
      <td>Lecture</td>
      <td>L11</td>
	  <td>The CEK machine</td>
    </tr>
    <tr class="table-success">
      <th scope="row">..</th>
      <td>Lecture</td>
      <td>L12</td>
	  <td>SSA and ANF, ANF conversion</td>
    </tr>

    <!-- <tr class="table-danger"> -->
    <!--   <th scope="row">TBA</th> -->
    <!--   <td>Exam</td> -->
    <!--   <td>F</td> -->
    <!--   <td>Final (120min, comprehensive, submit up to 6 answers)</td> -->
    <!-- </tr> -->


  </tbody>
</table>


# Chapter 17
 I learn in the past they were using <div id=""> to  Specify  the header and main  (content) and the footer  like:
<div id="page">
<div id="header"> 

 Now we use new layout element that allow you to divide up the
parts of a page  like <header> <footer>  like :
** <header>
<h1>Yoko's Kitchen</h1>
<nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav>
</header> **

 ** <footer>
&copy; 2011 Yoko's Kitchen
</footer> **


 They usually use header for the main contact and information and we use footer to copyright  .

 I learn The <nav> element is used to
contain the major navigational
blocks on the site such as the
primary site navigation like : 
** <nav>
<ul>
<li><a href="" class="current">home</a></li>
<li><a href="">classes</a></li>
<li><a href="">catering</a></li>
<li><a href="">about</a></li>
<li><a href="">contact</a></li>
</ul>
</nav> **
 
 The <article> element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.

This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.

If a page contains several articles
(or even summaries of several
articles), then each individual
article would live inside its own
 ** <article> element ; like :
<article>
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />

<p>A five week introduction to traditional
Japanese vegetarian meals, teaching you a
selection of rice and noodle dishes.</p>
</article>

<article>
<p>An intensive one-day course looking at how to
create the most delicious sauces for use in a
range of Japanese cookery.</p> 
</article> **

The <aside> element has two
purposes, depending on whether
it is inside an <article>
element or not. ------- we use it to side contact   
example :
<aside>
<h4>Epcot Center</h4>
<p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside> 

 The <section> element groups
related content together, and
typically each section would
have its own heading. example:

<section>
<h2>WWF's Symbol</h2>
<p>The Panda has become the symbol of WWF. The well-known panda logo of WWF originated from a panda named Chi Chi that was transferred from the Beijing Zoo to the London Zoo in the same year of the establishment of WWF.</p>
</section> 

we used  <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading. example: 

<hgroup>
<h2>Japanese Vegetarian</h2>
<h3>Five week course in London</h3>
</hgroup>

<figure> <figcaption>
You already met the <figure>
element in Chapter 5 when we
looked at images. It can be used
to contain any content that is
referenced from the main flow of
an article (not just images). 
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>


 

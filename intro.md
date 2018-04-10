<!-- $theme: default -->

# An Introduction to Bootstrap

Isaac Gluck, Robert Livaudais, Braden Pellowski, Raul Rodriguez, Kevin Xue

---

<!-- slide 1 -->

# What is Bootstrap?

##### Taken verbatim from their [website](https://getbootstrap.com/):

>"Bootstrap is an open source toolkit for developing with HTML, CSS, and JS."

##### In other words, it's a well-established CSS framework of pre-written stylesheets*

###### *Bootstrap also supports Javascript, however this presentation is primarily concerned with CSS and HTML

---

<!-- slide 2 -->

# Let's take a step back
##### How and why was Bootstrap created?

Prior to Bootstrap's inception building from scratch was a tedious manual process.

In the early 2010's Twitter began the construction of an internal tool used to "document and share common design patterns and assets within the company."


Twitter proceeded to release an open source version of the tool titled Bootstrap, which was received  with great acclaim.

---

<!-- slide 3 -->

# Bootstrap's ubiquity and longevity
##### Why has Bootstrap been so popular for so long?

These features have endowed Bootstrap with an incredible degree of popularity, which in turn has thusly provided a much needed level of consistency across the web development community.

As such, no similar tool has yet outpaced Bootstrap.

---

<!-- slide 4 -->

# Where does Boostrap fit into all of this?
- [ ] dev tool
- [x] front-end framework
- [ ] pre-processor
- [ ] language

---

<!-- slide 5 -->
![alt text](https://cdn.dribbble.com/users/135993/screenshots/2066450/webdevtrackillustration.gif)

---


<!-- slide 6 -->

# Why should you use Bootstrap?

##### Numerous core competencies position Bootstrap as an outstanding candidate for simple to intermediate web design

---

<!-- slide 7 -->

# Mobile-first

![alt text](http://blog.froont.com/content/images/2014/11/08_Desktop-first-vs-Mobile-first-3.gif)

---

<!-- slide 8 -->

# Responsive

![alt text](http://blog.froont.com/content/images/2014/11/04_Flow-vs-Static-2.gif)

---

<!-- slide 9 -->

# Example

#### Say we want a navbar

---

<!-- slide 10 -->
# Without Bootstrap

#### We'd set-up a structure in HTML:
~~~~
<nav id="menu">
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>
~~~~

---

<!-- slide 11 -->

# Without Bootstrap

#### Then we'd add our styling in CSS:

~~~~
#menu{
  z-index: 111;
  -webkit-transition: all 0.5s;
  text-align: center;
  position: fixed;
  left: 0;
  right: 0;
  margin: 0 auto;
  top: 65px;
  font-size: 18px;
  font-family: sans-serif;
  font-weight: 100;
  text-transform: uppercase;
  width: 100%;
  height: 0;
  border-bottom: 1px solid transparent;
  overflow: hidden;
  & // on & on ...
~~~~

---

<!-- slide 12 -->
# With BootstrapCDN

#### BootstrapCDN

~~~~
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
<nav class="navbar navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
</nav>
~~~~
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
<!-- As a link -->
<nav class="navbar navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
</nav>

---

<!-- slide 13 -->
# That's it

![alt text](https://m.popkey.co/574b46/WxVke.gif)

---

<!-- slide 14 -->
# Why Bootstrap and not other libraries?
1. cross-browser compatibility
2. lightweight (CSS, at least) and easy to customize
3. responsive compoents
4. good documentation and large community 🤗
5. now supports [Sass](http://sass-lang.com/)
6. templates
7. grid system

---

<!-- slide 15 -->
# In general, *structure* and *components*

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
<div class="row">
  <div class="col-md-4" style="background-color:rgba(86,61,124,.15);">1</div>
  <div class="col-md-4 ml-auto" style="background-color:rgba(86,61,124,.15);">2</div>
</div>
<div class="row">
  <div class="col-md-3 ml-md-auto" style="background-color:rgba(86,61,124,.15);">3</div>
  <div class="col-md-3 ml-md-auto" style="background-color:rgba(86,61,124,.15);">4</div>
</div>
<div class="row">
  <div class="col-auto mr-auto" style="background-color:rgba(86,61,124,.15);">5</div>
  <div class="col-auto" style="background-color:rgba(86,61,124,.15);">6</div>
</div>

#### Bootstrap *4* uses a mobile-first flexbox grid

---
<!-- slide 16 -->

# Why would one *not* use Bootstrap?

##### Despite its wonderful qualities, Bootstrap is not without shortcomings

---
<!-- slide 17 -->

# Here's one reason:

##### Bootstrap is heavy - coming loaded with an above average amount of CSS and JS code base. Paired with a weak internet connection, pages built using Bootstrap load very slowly. <sup>3</sup>*

###### * That is, assuming you're using a Bootstrap 4 component that requires JavaScript to function (i.e. *tooltips* and *alerts*)

---
<!-- slide 18 -->

# Here's another:

##### Bootstrap does not support SASS natively. SASS speeds up CSS styling cia preprocessing (we'll learn more about this later in the term), so SASS's incompatibility can rule out Bootstrap as a viable candidate for certain projects. <sup>3</sup>
---
<!-- slide 19 -->

# And another:

##### We talked earlier about how Bootstrap provides consistency among the web development community. This is a plus in one sense, but it also entails a lack of *originality*; developers wishing to truly distinguish their designs might not want to rely on the same framework as everyone else. <sup>4</sup>

---

<!-- slide 20 -->
# Bootstrap is *GREAT*, but it isn't perfect
1. style overrides
2. verbose classes (e.g. `list-group-item list-group-item-success`)
3. some components aren't compliant with accessibility standards (i.e. jumbotron before Bootstrap 4 update)
4. [generic design](http://adventurega.me/bootstrap/)
---

<!-- slide 21 -->

# Sources

1. http://markdotto.com/2012/01/17/bootstrap-in-a-list-apart-342/

2. https://www.devsaran.com/blog/10-best-reasons-use-bootstrap-amazing-web-designs

3. http://www.zingdesign.com/5-reasons-not-to-use-twitter-bootstrap/
4. http://blog.creative-tim.com/web-design/use-not-use-bootstrap-framework/



<!--- things that still need to be addressed in this presentation:
at one point the bootstrap look defined a generation of sites and maybe still does to some extent. Explain.
Due to consistency?
People migrating to CSS preprocessors like SASS ? --->

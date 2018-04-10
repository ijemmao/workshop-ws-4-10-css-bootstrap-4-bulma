<!-- $theme: default -->

# An Introduction to Bootstrap

Isaac Gluck, Robert Livaudais, Braden Pellowski, Raul Rodriguez, Kevin Xue

---

# What is Bootstrap?

##### Taken verbatim from their [website](https://getbootstrap.com/): 

>"Bootstrap is an open source toolkit for developing with HTML, CSS, and JS."



##### In other words, it's a well-established CSS framework of pre-written stylesheets*

###### *Bootstrap also supports Javascript, however this presentation is primarily concerned with CSS and HTML

---
# Let's take a step back
##### How and why was Bootstrap created?

Prior to Bootstrap's inception building from scratch was a tedious manual process.

In the early 2010's Twitter began the construction of an internal tool used to "document and share common design patterns and assets within the company."


Twitter proceeded to release an open source version of the tool titled Bootstrap, which was received  with great acclaim.

---


# Why should you use Bootstrap?

##### Numerous core competencies position Bootstrap as an outstanding candidate for simple to intermediate web design
---
# Here's one
##### Bootstrap is mobile-first and incredibly responsive:
> Hey, Dave — is the site mobile responsive yet?

<!-- insert frustrated GIF here --> GIF | <!-- insert confident GIF here --> GIF
--- | ---
Forgot media queries| Used Bootstrap instead

---

# Example

#### CSS
~~~~
body {margin: 0;}

ul.topnav {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

ul.topnav li {float: left;}
...
// 11 lines in and I'm still not moble reponsive :'(
~~~~

---

# Where does Boostrap fit into all of this?
- [ ] dev tool
- [x] front-end framework
- [ ] pre-processor
- [ ] language
---

# Bootstrap is *GREAT*; it isn't perfect
1. style overrides
2. verbose styles
3. some components aren't compliant with accessibility standards
4. generic design

---

# Why Bootstrap and not other libraries?
1. cross-browser compatibility
2. lightweight (CSS, at least 🤷) and easy to customize
3. responsive compoents
4. good documentation and large community
5. templates
6. grid system

---

# Where's our styling?

~~~~
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">

<div class="alert alert-primary" role="alert">
  A simple primary alert—check it out!
</div>
~~~~

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">
<div class="alert alert-primary" role="alert">
  A simple primary alert—check it out!
</div>

# Here's another
##### Predefined classes enable efficient and reliable coding:

<!--- insert example --->

---

# And another...
##### Flex boxes might be great, but Bootstrap's 12-column grid is automatically responsive allows the user a greater degree of control:

<!--- insert example --->


---


# Bootstrap's ubiquity and longevity
##### Why has Bootstrap been so popular for so long?

These features have endowed Bootstrap with an incredible degree of popularity, which in turn has thusly provided a much needed level of consistency across the web development community.

As such, no similar tool has yet outpaced Bootstrap.

---

# Why would one *not* use Bootstrap?

##### Despite its wonderful qualities, Bootstrap is not without shortcomings

---

# Here's one reason:

##### Bootstrap is heavy - coming loaded with an above average amount of CSS and JS code base. Paired with a weak internet connection, pages built using Bootstrap load very slowly. <sup>3</sup>

---

# Here's another:

##### Bootstrap does not support SASS natively. SASS speeds up CSS styling cia preprocessing (we'll learn more about this later in the term), so SASS's incompatibility can rule out Bootstrap as a viable candidate for certain projects. <sup>3</sup>
---

# And another:

##### We talked earlier about how Bootstrap provides consistency among the web development community. This is a plus in one sense, but it also entails a lack of *originality*; developers wishing to truly distinguish their designs might not want to rely on the same framework as everyone else. <sup>4</sup>

---

# Sources

1. http://markdotto.com/2012/01/17/bootstrap-in-a-list-apart-342/

2. https://www.devsaran.com/blog/10-best-reasons-use-bootstrap-amazing-web-designs

3. http://www.zingdesign.com/5-reasons-not-to-use-twitter-bootstrap/
4. http://blog.creative-tim.com/web-design/use-not-use-bootstrap-framework/



<!--- things that still need to be addressed in this presentation:
at one point the bootstrap look defined a generation of sites and maybe still does to some extent. Explain. 
Due to consistency?
People migrating to CSS preprocessors like SASS ? --->

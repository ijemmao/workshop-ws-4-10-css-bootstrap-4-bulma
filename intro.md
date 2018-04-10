<!-- $theme: default -->

# Bootstrap

ws-4-10-css

---

# What is Bootstrap?

Taken verbatim from their [website](https://getbootstrap.com/):
>Bootstrap is an open source toolkit for developing with HTML, CSS, and JS.

---

# In other words, it's a CSS framework of pre-written stylesheets*

#### *There is a JavaScript component to Bootstrap, too, but this presentation will only cover the CSS component

---

# Why use Bootstrap?

---
> Dave, is the site mobile responsive yet?

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

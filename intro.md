<!-- $theme: default -->

# Bootstrap

ws-4-10-css

---

# What is Bootstrap?

Taken verbatim from their [website](https://getbootstrap.com/): 
>Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. 

---

# In other words, it's a CSS framework of pre-written stylesheets*

#### *There is a JavaScript component to Bootstrap, too, but this presentation is primarily concerned with CSS

---

# Why use Bootstrap?

---
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
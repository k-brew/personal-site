---
layout: default
title: Kyle M. Brewster
---

<div id="navbar">
  <a href="#home">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
</div>
/* Style the navbar */
#navbar {
  overflow: hidden;
  background-color: #333;
}

/* Navbar links */
#navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px;
  text-decoration: none;
}

/* Page content */
.content {
  padding: 16px;
}

/* The sticky class is added to the navbar with JS when it reaches its scroll position */
.sticky {
  position: fixed;
  top: 0;
  width: 100%;
}

/* Add some top padding to the page content to prevent sudden quick movement (as the navigation bar gets a new position at the top of the page (position:fixed and top:0) */
.sticky + .content {
  padding-top: 60px;
}

// When the user scrolls the page, execute myFunction
window.onscroll = function() {myFunction()};

// Get the navbar
var navbar = document.getElementById("navbar");

// Get the offset position of the navbar
var sticky = navbar.offsetTop;

// Add the sticky class to the navbar when you reach its scroll position. Remove "sticky" when you leave the scroll position
function myFunction() {
  if (window.pageYOffset >= sticky) {
    navbar.classList.add("sticky")
  } else {
    navbar.classList.remove("sticky");
  }
}


## Hello!

Welcome to the website of Kyle Brewster.

This site is currently a work-in-progress, so please check these links for some more information/content in the meantime until I have this page properly developed:

- [Old Personal Site](https://kyle-brewster.blogspot.com/)
- [Github](https://github.com/k-brew)
- [Linkedin](https://www.linkedin.com/in/kyle-brewster)



In the future, this page will be the "landing page" for a collection of my websites (or maybe branches within the same site). In the near future, there will be the following topics:

1. **Professional/portfolio** - a collection of work samples and experience that potential employers would find relevent
2. **Personal** - a platform for voicing my ideas, sharing things that I find interesting, and other things
3. **Learning** - a collection of my notes and resources I find helpful/informative
4. *to be announced soon*

Best wishes in the meantime,  
Kyle 

*Last Update:* 7/7/22

<script src="http://code.jquery.com/jquery-1.4.2.min.js"></script> <script> var x = document.getElementsByClassName("site-footer-credits"); setTimeout(() => { x[0].remove(); }, 10); </script>




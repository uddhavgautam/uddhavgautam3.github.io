---
title: "Blogs"
layout: gridlay
sitemap: false
permalink: /blogs/
---

# Blogs

<button class="collapsible">Using Jekyll to build your Static Github Website</button>
<div class="content">

[Clone this GitHub repo](https://github.com/uddhavgautam3/uddhavgautam3.github.io) in your favorite IDE (e.g., Ruby Mine). 
You can re-write all git histories.in your favorite IDE (e.g., Ruby Mine). You can re-write all git histories. 
Create a github repo something like \<websitename\>.github.io. Then add your publish ssh-key, give read/write permissions, 
and configure page publish in your github settings.

In your local IDE (e.g., Ruby Mine),
Edit as you like and push. This should take less than 2 minutes to publish with new changes.

You must install Ruby and other build dependencies to be able to start your local Jekyll server.

Before pushing, you can test locally using below commands

      % bundle exec jekyll serve
      % http://localhost:4000/

</div>

<script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
<script>
  $(document).ready(function(){
    $(".collapsible").click(function(){
      $(".content").slideToggle();
    });
  });
</script>

<style>
  .collapsible {
    background-color: #302f2f;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }

  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    color: black;
    background-color: #c4c4c4;
  }
</style>



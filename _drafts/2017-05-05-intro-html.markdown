---
layout: "default"
title: "Introduction to HTML"
image: "assets/images/material/intro_html/my_first_page.png"
date: "2017-05-05 23:25"
---

<!--more-->


<link href="/assets/css/intro_html.css" rel="stylesheet" />
<link href="https://fonts.googleapis.com/css?family=Oxygen" rel="stylesheet">

<div id="impress" style="margin-top: 100px">
  <div class="step slide" data-x="-1000" data-y="-1500" data-scale="3">
      <q>HTML</q>
  </div>
  <div id="title" class="step" data-x="-3000" data-y="200" data-scale="1">
      <span class="try">it.pinterest.com</span>
      </br>
      <img src="/assets/images/material/intro_html/pinterest.png" style="width: 800px">
  </div>
  <div id="its" class="step" data-x="-1000" data-y="200" data-scale="1">
      <p><strong>HyperText Maurkup Language</strong> <br/><br/>
      - documenti nel <strong>W</strong>orld <strong>W</strong>ide <strong>W</strong>eb
      <br/>
      - usa <strong>< tag >< /tag ></strong>
      </p>
  </div>
  <div class="step slide " data-x="1000" data-y="200" data-scale="1">
      <p>Testo con link</p>
      <img src="/assets/images/material/intro_html/destigo.png" style="width: 800px">
  </div>
  <div id="its-in-3d" class="step slide" data-x="1000" data-y="2000" data-z="-100" data-scale="3" data-rotate-x="-50" data-rotate-y="0">
      <img src="/assets/images/material/intro_html/my_first_page.png" style="width: 800px">
  </div>
  <div  class="step slide" data-x="-1500" data-y="2000" data-z="-100" data-scale="3" data-rotate-x="-50" data-rotate-y="0">
      HTML per i componenti <br/>
      CSS per stilarlo <br/>
  </div>

  <!-- CSS -->
  <div class="step slide" data-x="5000" data-y="-1500" data-scale="3">
      <q>CSS</q>
      <p>Cascading Style Sheets</p>
  </div>
  <div class="step" data-x="4000" data-y="200" data-scale="1">
      <br>
      <img src="/assets/images/material/intro_html/css_no_css.svg" style="width: 800px">
  </div>
  <div class="step" data-x="6000" data-y="200" data-scale="1">
      <br>
      <img src="/assets/images/material/intro_html/css_blue_back.png" style="width: 500px">
      <br>
      <img src="/assets/images/material/intro_html/blue_back.png" style="width: 500px">
  </div>
  <div style="text-align: center" class="step" data-x="7000" data-y="200" data-scale="1">
      <p>Usando codice Esadecimale</p>
      <br>
      <img src="/assets/images/material/intro_html/css_blue_hex_back.png" style="width: 500px">
      <br>
      <img src="/assets/images/material/intro_html/blue_hex_back.png" style="width: 500px">
  </div>
  <div style="text-align: center" class="step" data-x="7000" data-y="1200" data-scale="1">
      <p>Usando il tag < style > </p>
      <br>
      <img src="/assets/images/material/intro_html/css_blue_hex_back_style.png" style="width: 700px">
  </div>
  <div class="step" data-x="5000" data-y="1200" data-scale="1">
      <p>blue_background => tag</p>
      <p>.blue_background => class</p>
      <p>#blue_background => id</p>
  </div>

  <!-- RGB -->
  <div class="step slide" data-x="5000" data-y="5000" data-scale="3">
      <q>RGB</q>
      <p>Red Green Blue</p>
  </div>
  <div class="step" data-x="6000" data-y="5000" data-scale="1">
      <br>
      <img src="/assets/images/material/intro_html/slack_zoom_1.jpg" style="width: 800px">
  </div>
  <div class="step" data-x="6000" data-y="5000" data-z="-3000" data-scale="1">
      <br>
      <img src="/assets/images/material/intro_html/slack_zoom_2.jpg" style="width: 800px">
  </div>
  <div class="step" data-x="6000" data-y="5000" data-z="-6000" data-scale="1">
      <br>
      <img src="/assets/images/material/intro_html/slack_zoom_3.jpg" style="width: 800px">
  </div>
  <div class="step" data-x="6000" data-y="5000" data-z="-9000" data-scale="1">
      <br>
      <img src="/assets/images/material/intro_html/slack_zoom_4.jpg" style="width: 800px">
  </div>


  <div  class="step slide" data-x="-1000" data-y="5000" data-scale="1">
      <a class="link" href="https://www.w3schools.com/">w3schools</a>
  </div>

  <div id="overview" class="step" data-x="2000" data-y="1000" data-scale="9">
  </div>
</div>

<div style="
    width: 100%;
    display: flex;
    position: absolute;
    bottom: 0px;
    justify-content: center;">
  <a href="" style="font-size: 5em; font-weight: bold; padding-right: 50px; margin: 0px" onClick="return prev()"> < </a>
  <a href="" style="font-size: 5em; font-weight: bold; padding-left: 50px; margin: 0px" onClick="return next()"> > </a>
</div>

<script src="/js/impress.js"></script>
<script>impress().init();</script>

<script>
  function prev(){
    impress().prev();
    return false;
  }

  function next(){
    impress().next();
    return false;
  }
</script>

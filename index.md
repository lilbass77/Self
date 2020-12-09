---
title: Hello
date: <font face="fantasy " size="2" > 2020-10-18 23:21:39
tags:
---
<script>
   document.addEventListener('DOMContentLoaded', function(){
    document.getElementById('getMessage').onclick = function(){
    document.getElementsByClassName('message')[0].textContent="Welcome To My Blog!!!";
    }
  });
</script>

<style>
  body {
    text-align: center;
    font-family: "Helvetica", sans-serif;
  }
  h1 {
    font-size: 2em;
    font-weight: bold;
  }
  .box {
    border-radius: 5px;
    background-color: #eee;
    padding: 20px 5px;
  }
  button {
    color: white;
    background-color: #4791d0;
    border-radius: 5px;
    border: 1px solid #4791d0;
    padding: 5px 10px 8px 10px;
  }
  button:hover {
    background-color: #0F5897;
    border: 1px solid #0F5897;
  }
</style>

<h1>ALLEN'S PHOTOS</h1>
<p class="message box">
</p>
<p>
  <button id="getMessage">
    CLICK ON 
  </button>
</p>
<style>
  .red-text {
    width:   100px;
    background-color :orange;
    height:   30px ;
    color: red;
    border-radius:10% 10%;
  }
  .blue-text {
    color: blue;
    background-color: orange;
    width: 100px;
    height: 30px;
    border-radius: 10% 10%;
 
  }

</style>
<script>
    $(document).ready(function() {
    $("#photo1").addClass("animated bounce");
    $("#photo1").addClass("animated shake");
  });
</script>

<font face="fantasy " size="6"   >
In Liyutan Reservoir
<font face="fantasy " size="3" >
<div class="container-fluid">
1.
<img src="/images/1.jpg"id="photo1">
<div class="row">
    <div class="col-xs-2">
      <button class="blue-text btn btn-block btn-primary" ><i class="fa fa-thumbs-up"></i> Like</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
      <button class="btn btn-default target red-text"><i class="fa fa-thumbs-down"></i> DisLike</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
    </div>
  </div>
2.
<img src="/images/2.jpg" id="photo2">
  <div class="row">
    <div class="col-xs-2">
      <button class="blue-text btn btn-block btn-primary" ><i class="fa fa-thumbs-up"></i> Like</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
      <button class="btn btn-default target red-text"><i class="fa fa-thumbs-down"></i> DisLike</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
    </div>
  </div>
3.
<img src="/images/3.jpg">
<div class="row">
    <div class="col-xs-2">
      <button class="blue-text btn btn-block btn-primary" ><i class="fa fa-thumbs-up"></i> Like</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
      <button class="btn btn-default target red-text"><i class="fa fa-thumbs-down"></i> DisLike</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
    </div>
  </div>
4.
<img src="/images/4.jpg">
<div class="row">
    <div class="col-xs-2">
      <button class="blue-text btn btn-block btn-primary" ><i class="fa fa-thumbs-up"></i> Like</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
      <button class="btn btn-default target red-text"><i class="fa fa-thumbs-down"></i> DisLike</button>  <label><input type="radio" name="indoor-outdoor"> </label><br>
    </div>
  </div>

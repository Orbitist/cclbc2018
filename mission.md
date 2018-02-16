---
layout: page
title: "Our Mission"
lead: "We're the Chautauqua County Land Bank Corporation.<br/>It's nice to meet you!"
image: "img/man_demo.jpg"
---
<iframe class="center-block video" width="560" height="315" src="https://www.youtube.com/embed/hKwv6ZR_d2s?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

Control and manage strategically selected dilapidated and abandoned residential and commercial properties acquired through the County tax foreclosure process, bank foreclosures and/or donations, and facilitate solutions aimed at stabilizing neighborhoods, encouraging private investment, and improving the quality of life throughout Chautauqua County.

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-home number-icon"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer rehabs-sold">0.00</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.rehabs-sold').offset().top,
             hH = $('.rehabs-sold').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.rehabs-sold').html(20);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Rehabs Sold in 2017</div>
</div>

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon" style="height:111px;"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer assessed-value">0</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.assessed-value').offset().top,
             hH = $('.assessed-value').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.assessed-value').html(1182623);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Those properties’ Assessed Value back on the tax Rolls</div>
</div>

# Overview

The Chautauqua County Land Bank Corporation (CCLBC) was designated as one of the first five land banks in NYS, by authority of the New York State Land Bank Act, in 2012. By year-end 2017, the Land Bank secured over $4,410,000 million dollars in public grant funding, and leveraged over $3,188,686 in private investment in the interventions of more than 173 vacant or abandoned properties in the county.

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon" style="height:111px;"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer private-investment">0</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.private-investment').offset().top,
             hH = $('.private-investment').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.private-investment').html(1118372);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Private Re-Investment into Neighborhoods</div>
</div>

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon" style="height:111px;"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer cclbc-taxes">0</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.cclbc-taxes').offset().top,
             hH = $('.cclbc-taxes').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.cclbc-taxes').html(40521);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Property taxes paid by the Land Bank last year</div>
</div>

<hr>

<a href="problem" class="btn btn-default btn-lg center-block">The Problem <i class="fa fa-arrow-right"></i></a>

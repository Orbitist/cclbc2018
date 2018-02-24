---
layout: page
title: Outcomes
lead: "Results from 2017"
image: "img/drone_beach.jpg"
---
<iframe class="center-block video" width="560" height="315" src="https://www.youtube.com/embed/iq9xEV2Vu8c?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

# Completion of Round 2 Community Revitalization Initiative Grant Funding from the NYS Attorney General’s office

This grant support has provided vital operating funds for the Land Bank in its early years and critical funding of our demolition program, resulting in the removal of 90 blighted and unsafe structures throughout the county. It also facilitated in the return of 14 bank owned, or zombie properties, and 30 vacant lots to productive use.

<a href="https://cclbc.carto.com/builder/c5b985f5-b7f9-4988-9d49-fb0c5583d67c/embed" target="blank" class="btn btn-default btn-lg center-block"><i class="fa fa-map-marker"></i> GIS Database of Properties effected by CCLBC</a>

Through the generous support of the county Legislature, the Chautauqua County Land Bank has also demonstrated its ability to address blight and stabilize neighborhoods across the county through its Sales 4 Rehab program and creative problem-solving. The Land Bank’s programs impact vacancy rates and property values, most dramatically in the cities of Jamestown and Dunkirk, where 98 properties have entered the Sales 4 Rehab program and each year, additional substandard properties are turned over to the Land Bank and scheduled for demolition. Rural townships receive additional resources from the land bank in the form of demolition funding and project management to help these smaller municipalities build capacity to effectively tackle blight in their communities. The Land Bank is shifting the paradigm on how the county deals with tax foreclosed properties by leveraging resources to tackle the glut of vacant, abandoned and condemned properties.

<a href="https://chqlandbank.org/properties" target="blank" class="btn btn-default btn-lg center-block"><i class="fa fa-home"></i> View Current Inventory</a>

# 2017 Results of Acquisitions from the Legislature (Properties pulled from the Tax Auction)

{% include charts/property-types.html %}

# To date:

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-home number-icon" style="height:111px;"></span>
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
               $('.assessed-value').html(62);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Rehabs sold from 2013 - 2017</div>
</div>

# 2017 Activity in Dunkirk and Jamestown

<div class="row">
  <div class="col-md-3">
    <p class="lead">Dunkirk Demos 2015 - 2018:</p>
    <img src="img/maps/Dunkirk_demos_2015-2018.png" class="img-responsive">
  </div>
  <div class="col-md-3">
    <p class="lead">Jamestown Demos 2015 - 2018:</p>
    <img src="img/maps/Jamestown_demos_2015-2018.png" class="img-responsive">
  </div>
  <div class="col-md-3">
    <p class="lead">Dunkirk Rehabs 2015 - 2018:</p>
    <img src="img/maps/Dunkirk_rehabs_2015-2018.png" class="img-responsive">
  </div>
  <div class="col-md-3">
    <p class="lead">Jamestown Rehabs 2015 - 2018:</p>
    <img src="img/maps/Jamestown_rehabs_2015-2018.png" class="img-responsive">
  </div>
</div><!-- /.row -->
<hr>

# 2017 Financial Overview

Statements of Financial Position:

{% include charts/financials.html %}

<hr>

<a href="team" class="btn btn-default btn-lg center-block">Our Team <i class="fa fa-arrow-right"></i></a>

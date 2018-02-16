---
layout: page
title: Outcomes
lead: "Highlights of 2017 Activities"
image: "img/drone_beach.jpg"
---
Between 2013-2017, the Chautauqua County Land Bank Corporation secured two separate grants from the NYS Office of Attorney General’s Community Revitalization Initiative Program totaling $2.86 million.  This funding has been allocated primarily towards activities related to demolition, vacant lot disposition, acquisition of bank foreclosed properties, administration and marketing (Refer to attached 2017 Financial Audit Report).

This grant support has provided vital operating funds for the Land Bank in its early years and critical funding of our demolition program, resulting in the removal of 90 blighted and unsafe structures throughout the county. It also facilitated in the return of 14 bank owned, or zombie properties, and 30 vacant lots to productive use. 

Through the generous support of the county Legislature, the Chautauqua County Land Bank has also demonstrated its ability to address blight and stabilize neighborhoods across the county through its Sales 4 Rehab program and creative problem-solving. The Land Bank’s programs impact vacancy rates and property values, most dramatically in the cities of Jamestown and Dunkirk, where 98 properties have entered the Sales 4 Rehab program and each year, additional substandard properties are turned over to the Land Bank and scheduled for demolition. Rural townships receive additional resources from the land bank in the form of demolition funding and project management to help these smaller municipalities build capacity to effectively tackle blight in their communities. The Land Bank is shifting the paradigm on how the county deals with tax foreclosed properties by leveraging resources to tackle the glut of vacant, abandoned and condemned properties.

{% include maps/inventory.html %}

# 2017 Results of Acquisitions from the Legislature

{% include charts/property-types.html %}

_* Note: Demolitions were acquired from were acquired 2013-2016_

<div class="number">
  <div class="col-xs-2">
    <span class="fa fa-dollar number-icon"></span>
  </div>  
  <div class="col-xs-10">
    <div id="odometer" class="odometer reinvestment">000,000</div>
    <script>
      $(window).scroll(function() {
         var hT = $('.reinvestment').offset().top,
             hH = $('.reinvestment').outerHeight(),
             wH = $(window).height(),
             wS = $(this).scrollTop();
          console.log((hT-wH) , wS);
         if (wS > (hT+hH-wH)){
           setTimeout(function(){
               $('.reinvestment').html(431145);
           }, 100);
         }
      });
    </script>
  </div>
  <div class="number-caption">Private reinvestment commitments for Rehab renovations</div>
</div>


# 2016 Financial Overview

Statements of Financial Position:

{% include charts/financials.html %}

<hr>

<a href="team" class="btn btn-default btn-lg center-block">Our Team <i class="fa fa-arrow-right"></i></a>

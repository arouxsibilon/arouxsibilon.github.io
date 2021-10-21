---
layout: page
title: 
---
<html lang="en">


 <head>
  <meta charset="utf-8">
  
  <title>Image Gallery</title>
  <meta name="description" content="Responsive Image Gallery">
  <meta name="author" content="Tim Wells">
  
  <style type="text/css">
#gallery {
   line-height:0;
   -webkit-column-count:2; /* split it into 5 columns */
   -webkit-column-gap:5px; /* give it a 5px gap between columns */
   -moz-column-count:2;
   -moz-column-gap:5px;
   column-count:2;
   column-gap:5px;
}
#gallery img {
   width: 100% !important;
   height: auto !important;
   margin-bottom:5px; /* to match column gap */
}
@media (max-width: 1200px) {
   #gallery {
    -moz-column-count:    2;
    -webkit-column-count: 2;
    column-count:         2;
   }
}
@media (max-width: 1000px) {
   #gallery {
    -moz-column-count:    2;
    -webkit-column-count: 2;
    column-count:         2;
   }
}
@media (max-width: 800px) {
   #gallery {
    -moz-column-count:    1;
    -webkit-column-count: 1;
    column-count:         1;
   }
}

  </style>
</head>
<body>
<div id="gallery">
 
   <img src="images/1.jpg">
   <img src="images/15.jpg">
   <img src="images/19.jpg">
   <img src="images/14.jpg">
   <img src="images/10.jpg">
   <img src="images/11.jpg">
   <img src="images/12.jpg">
   <img src="images/13.jpg">
   <img src="images/16.jpg">  
   <img src="images/3.jpg">
   <img src="images/17.jpg">
   <img src="images/24.jpg">
   <img src="images/4.jpg">
   <img src="images/5.jpg">
   <img src="images/6.jpg">
   <img src="images/22.jpg">
   <img src="images/9.jpg">
   <img src="images/21.jpg">
   <img src="images/2.jpg">
   <img src="images/8.jpg">
   <img src="images/20.jpg">
   <img src="images/7.jpg">
   <img src="images/25.jpg">
   <img src="images/18.jpg">
   <img src="images/23.jpg">  
   
  </div>
 
 </body>
</html>

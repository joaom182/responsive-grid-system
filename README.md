Responsive Grid System - RGS
===

This grid system was based on the grid system of the Twitter Bootstrap 3, HOWEVER, it is not "mobile first" to ensure support for older browsers that do not support CSS Media Queries AND is flexibly is based on 10 and 12 columns, depending on the measures you choose your layout.

There are scenarios where you have to design a solution compatible with IE8 and operating on mobile devices, such as an Intranet of a company, where the desktop computers have update restrictions to maintain compatibility with internal software, but want to be able to access and view information on the intranet via a mobile device.

##Example using 10 colums based
```
<div class="row-10">
  <div class="col-md-3-3"></div>
  <div class="col-md-3-3"></div>
  <div class="col-md-3-3"></div>
</div>
```
Note that three columns with `col-md-3-3` (33.3% each) were used, the reason for this is to give greater flexibility in the construction of the grid system and also be based on 10 columns, where you need to have levels greater precision in the columns.



[Tooltip for Google Maps API V3](http://medelbou.wordpress.com/2012/02/03/creating-a-tooltip-for-google-maps-javascript-api-v3/)
==================================================
Simple class to create a tooltip in Google Maps JavaScript API V3. This is based on the example given in the Google Maps API documentation, [see it here][lk].
[lk]: http://code.google.com/apis/maps/documentation/javascript/overlays.html#CustomOverlays

For comments/suggestions, email me at me[at]medelbou[dot]com.

## How to use


```html
<script src="http://maps.googleapis.com/maps/api/js?sensor=true"></script>
<script src="js/tooltip.js"></script>
//after the map is ready..
// Tooltip Options   
var tooltipOptions={
  marker:marker,// required
  content:content,// required
  cssClass:'tooltip' // name of a css class to apply to tooltip
};
var tooltip = new Tooltip(tooltipOptions);
```


[Download](https://github.com/medelbou/Tooltip-for-Google-Maps/zipball/master)
====================================================
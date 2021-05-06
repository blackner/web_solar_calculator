For the nominal power calculation, I am assuming that the nominal power depends only on the surface area and the energy conversion efficiency of the installation. I assume that the sun shines perpendicular to the earth's surface, and the angle between the earth's surface and the installation's surface is exactly defined by the "tilt" input. I also assume that the light intensity from the sun is 1kW/square meter (from https://www.pveducation.org/pvcdrom/solar-cell-operation/effect-of-light-intensity).

Test cases:
User enters an invalid location in the seach box
User enters an address not in the US
User draws a polygon that intersects with itself
User changes the map style
User types in a negative efficiency value
User types in an efficiency value greater than 100
User draws a polygon and changes the efficiency value
User draws a polygon and deletes it
User types in a negative tilt value
User types in a tilt value greater than 89
User enters 45 as a tilt value (calculated surface area should increase by about 1.43 times)
User enters 89 as a tilt value (calculated surface area should increase significantly)

Nice-to-haves/possible enhancements:
Allow polygons that contain "holes"
Look up more accurate angle of sunlight depending on lat/long of installation

References used:
https://docs.mapbox.com/mapbox-gl-js/example/simple-map/
https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-geocoder-accept-coordinates/
https://docs.mapbox.com/mapbox-gl-js/example/mapbox-gl-draw/
https://www.pveducation.org/pvcdrom/solar-cell-operation/effect-of-light-intensity
https://stackoverflow.com/questions/2901102/how-to-print-a-number-with-commas-as-thousands-separators-in-javascript

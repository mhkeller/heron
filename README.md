Heron
===

A simple interface for making locator maps with styled tiles and GeoJson.

See it [here](http://mhkeller.github.io/heron).

## How to use

Heron uses Google map base layer, which you can style with the [Google Maps API Styled Map Wizard](http://gmaps-samples-v3.googlecode.com/svn/trunk/styledmaps/wizard/index.html). That wizard will give you JSON, which you can paste Heron's `Tile style` field.

You can also upload a GeoJSON file and style it with the properties Google supports: <https://developers.google.com/maps/documentation/javascript/3.exp/reference#Data.StyleOptions>

From their documentation:

| Property | Type | Description |
|:--------:|:-----:|-----------|
| clickable  | boolean | If true, the marker receives mouse and touch events. Default value is true.
| cursor |string | Mouse cursor to show on hover. Only applies to point geometries.
| fillColor |string | The fill color. All CSS3 colors are supported except for extended named colors. Only applies to polygon geometries.
| fillOpacity |number | The fill opacity between 0.0 and 1.0. Only applies to polygon geometries.
| icon |string,Icon,Symbol | Icon for the foreground. If a string is provided, it is treated as though it were an Icon with the string as url. Only applies to point geometries.
| shape |MarkerShape | Defines the image map used for hit detection. Only applies to point geometries.
| strokeColor |string | The stroke color. All CSS3 colors are supported except for extended named colors. Only applies to line and polygon geometries.
| strokeOpacity |number | The stroke opacity between 0.0 and 1.0. Only applies to line and polygon geometries.
| strokeWeight |number | The stroke width in pixels. Only applies to line and polygon geometries.
| title |string | Rollover text. Only applies to point geometries.
| visible |boolean | Whether the feature is visible. Defaults to true.
| zIndex |number | All features are displayed on the map in order of their zIndex, with higher values displaying in front of features with lower values. Markers are always | displayed in front of line-strings and polygons.

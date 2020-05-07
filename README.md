# Pelias Design

Branding &amp; graphic design guidelines and assets

## Brand Guidelines

[PDF](./Pelias_Brand_Guideliness_RGB.pdf)

## Logos

### PNG

![Horizontal primary](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_horizontal_primary.png)


![Vertical primary](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_vertical_primary.png)

![Horizontal secondary](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_horizontal_secondary.png)


![Vertical secondary](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_vertical_secondary.png)

![Horizontal black](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_horizontal_black.png)


![Vertical black](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_vertical_black.png)

![Horizontal white](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_horizontal_white.png)


![Vertical white](./logo/pelias/Pelias%20Logo%20PNG/Pelias%20-%20Logo_vertical_white.png)

### PNG, transparent

![Horizontal primary](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_horizontal_primary.png)


![Vertical primary](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_vertical_primary.png)

![Horizontal secondary](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_horizontal_secondary.png)


![Vertical secondary](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_vertical_secondary.png)

![Horizontal black](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_horizontal_black.png)


![Vertical black](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_vertical_black.png)

![Horizontal white](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_horizontal_white.png)


![Vertical white](./logo/pelias/Pelias%20Logo%20PNG%20Transparent/Pelias%20-%20Logo%20-%20Transparent_vertical_white.png)

### SVG

![Horizontal primary](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_horizontal_primary.svg)


![Vertical primary](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_vertical_primary.svg)

![Horizontal secondary](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_horizontal_secondary.svg)


![Vertical secondary](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_vertical_secondary.svg)

![Horizontal black](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_horizontal_black.svg)


![Vertical black](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_vertical_black.svg)

![Horizontal white](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_horizontal_white.svg)


![Vertical white](./logo/pelias/Pelias%20Logo%20SVG/Pelias%20-%20Logo_vertical_white.svg)

## Favicons

### PNG

![](./logo/pelias/Favicon/Favicon-PNG/Favicon_16x16.png) ![](./logo/pelias/Favicon/Favicon-PNG/Favicon_32x32.png) ![](./logo/pelias/Favicon/Favicon-PNG/Favicon_64x64.png)

### SVG

![](./logo/pelias/Favicon/Favicon-SVG/Favicon_16x16.svg)

## Maps

Maps are provided by [**Jawg**Maps](https://jawg.io), the style used in our repositories is `jawg-terrain`.
When you are using maps, JawgMaps and OSM attributions are mandatory, don't forget that.

```html
<head>
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css"/>
  <script src="https://unpkg.com/leaflet@1.6.0/dist/leaflet.js"></script>
</head>
<body>
<div id="map" style="width: 100%; height: 100%;"></div>
<script>
  var map = L.map('map').setView([0.0, 0.0], 1);
  L.tileLayer('https://tile.jawg.io/jawg-terrain/{z}/{x}/{y}.png?access-token=t6fAKnvaPdPCucraY88YwlKjBfUHqBMvvZBIWlcp1Z9Z5FVtA02uWo6Dc9DGB2JO', {
    attribution: 'Map &copy; <a href="http://jawg.io" target="_blank" class="jawg-attrib"><b>Jawg</b>Maps</a> | Map data &copy; <a href="https://www.openstreetmap.org/copyright" target="_blank" class="osm-attrib">OpenStreetMap contributors</a>',
    maxZoom: 22
  }).addTo(map);
</script>
</body>
```

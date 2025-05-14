---
layout: page
title: Georgia Loyalists
permalink: Gloyalists
show-title: true
---

<!-- Load the ArcGIS Web Components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>

<style>
  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
  }

  .map-container {
    width: 100%;
    height: 100vh; /* full height of viewport */
    display: flex;
    flex-direction: column;
    gap: 20px;
    align-items: center;
    justify-content: center;
  }

  arcgis-embedded-map {
    width: 90vw;  /* 90% of viewport width */
    height: 45vh; /* 45% of viewport height per map */
    max-width: 1200px;
  }
</style>

<div class="map-container">
  <arcgis-embedded-map 
    item-id="3a94c18237ef410b9f139bc08310136b" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>

  <!-- Add script to the <head> of your page to load the embeddable map component -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>
<style>
  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
  }

  .map-container {
    width: 100%;
    height: 100vh; /* full height of viewport */
    display: flex;
    flex-direction: column;
    gap: 20px;
    align-items: center;
    justify-content: center;
  }

  arcgis-embedded-map {
    width: 90vw;  /* 90% of viewport width */
    height: 45vh; /* 45% of viewport height per map */
    max-width: 1200px;
  }
</style>

<div class="map-container">
  <arcgis-embedded-map 
    item-id="3a94c18237ef410b9f139bc08310136b" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>

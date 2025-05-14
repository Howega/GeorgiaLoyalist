---
layout: page
title: Georgia Loyalists
permalink: Gloyalists
show-title: true
---

<!-- Load ArcGIS Web Components (only once) -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>

<style>
  html, body {
    margin: 0;
    padding: 0;
    height: 100%;
  }

  .map-section {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 40px;
    padding: 40px 0;
  }

  arcgis-embedded-map {
    width: 90vw;
    height: 45vh;
    max-width: 1200px;
    border: none;
  }
</style>

<div class="map-section">
  <!-- First ArcGIS Map -->
  <arcgis-embedded-map 
    item-id="3a94c18237ef410b9f139bc08310136b" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>

  <!-- Second ArcGIS Map -->
  <arcgis-embedded-map 
    item-id="79f3c93b50e34accb9f5fa62bf724aa6" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>
</div>

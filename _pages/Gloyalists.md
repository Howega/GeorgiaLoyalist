---
layout: page
title: Georgia Loyalists
permalink: Gloyalists
show-title: true
---

<!-- Load ArcGIS Web Components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>

<style>
  .map-wrapper {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
    margin-top: 2rem;
  }

  arcgis-embedded-map {
    width: 100%;
    max-width: 1100px;
    height: 45vh;
    border: none;
  }
</style>

<div class="map-wrapper">
  <!-- Loyalist Map -->
  <arcgis-embedded-map 
    item-id="3a94c18237ef410b9f139bc08310136b" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>

  <!-- Trade Connections Map -->
  <arcgis-embedded-map 
    item-id="79f3c93b50e34accb9f5fa62bf724aa6" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arc

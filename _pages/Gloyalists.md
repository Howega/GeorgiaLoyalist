---
layout: page
title: Georgia Loyalists
permalink: Gloyalists
show-title: false
---

<!-- Add script to the <head> of your page to load the embeddable map component -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>
<!-- Add custom element to <body> of your page -->
 <arcgis-embedded-map style="height:600px;width:700px;" item-id="3a94c18237ef410b9f139bc08310136b" theme="light" portal-url="https://bostoncollege.maps.arcgis.com" ></arcgis-embedded-map>

<style>
  .map-wrapper {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 2rem;
    margin-top: 2rem;
    padding: 1rem;
  }

  arcgis-embedded-map {
    width: 95vw;
    max-width: 1200px;
    height: 60vh;
    border: none;
  }
</style>

<div class="map-wrapper">
  <!-- Loyalist Distribution Map -->
  <arcgis-embedded-map 
    item-id="3a94c18237ef410b9f139bc08310136b" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>

  <!-- Trade Connections Map -->
  <arcgis-embedded-map 
    item-id="79f3c93b50e34accb9f5fa62bf724aa6" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>
</div>


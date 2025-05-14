---
layout: page
title: Georgia Loyalists
permalink: Gloyalists
show-title: true
---

<!-- Load ArcGIS Web Components -->
<script type="module" src="https://js.arcgis.com/embeddable-components/4.32/arcgis-embeddable-components.esm.js"></script>

<style>
  .map-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 40px;
    padding: 40px 0;
  }

  arcgis-embedded-map {
    width: 700px;
    height: 600px;
    border: none;
  }

  @media (max-width: 768px) {
    arcgis-embedded-map {
      width: 90vw;
      height: 400px;
    }
  }
</style>

<div class="map-row">
  <!-- Map 1 -->
  <arcgis-embedded-map 
    item-id="3a94c18237ef410b9f139bc08310136b" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>

  <!-- Map 2 -->
  <arcgis-embedded-map 
    item-id="79f3c93b50e34accb9f5fa62bf724aa6" 
    theme="light" 
    portal-url="https://bostoncollege.maps.arcgis.com">
  </arcgis-embedded-map>
</div>

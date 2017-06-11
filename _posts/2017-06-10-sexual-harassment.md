---
title: Sexual Harrassment

scripts:
    - /the-stack/js/lib/d3.v4.min.js
    - /the-stack/js/posts/sexual-harassment/app.js
    - /the-stack/js/posts/sexual-harassment/bubble-chart.js
    - /the-stack/js/posts/sexual-harassment/table.js

stylesheets:
    - /the-stack/css/tooltip.css
    - /the-stack/css/posts/sexual-harassment/tooltip.css
    - /the-stack/css/posts/sexual-harassment/table.css
---

<select style='margin:0 auto; display: flex; width: 200px; height: 3em;' id='bubbleChartDropdown'>
  <option value='0'>POSITIONS</option>
  <option value='1'>GENDERS</option>
  <option value='2'>PUNISHMENTS</option>
</select>
<div class='bubble-chart-wrapper' style='text-align: center;'>
  <svg width="640" height="640" id="bubble-chart"></svg>
</div>

<select style='margin:0 auto; display: flex; width: 200px; height: 3em;' id='tableDropdown'>
  <option value='0'>POSITIONS</option>
  <option value='1'>GENDERS</option>
  <option value='2'>PUNISHMENTS</option>
</select>
<div class='table-container fullwidth'>
    <div class='table-wrapper' style='display: block;'></div>
</div>

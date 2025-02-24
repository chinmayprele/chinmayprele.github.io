---
title: Professional Societies
layout: default
nav_order: 7
---

<ol class="reverse">
	<li><b>Society for Molecular Biology and Evolution</b> <i>2022 &rarr; Present</i></li> 
	<li><b>Genetics Society of America</b> <i>2019 &rarr; Present</i></li>
</ol>

<style>
ol.reversed {
  counter-reset: reversed-counter; /* JavaScript will set the correct number */
}

ol.reversed li {
  list-style: none;
  counter-increment: reversed-counter -1;
  position: relative;
}

ol.reversed li::before {
  content: counter(reversed-counter, decimal) ". ";
  position: absolute;
  left: -2em;
}
</style>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    document.querySelectorAll("ol.reversed").forEach(ol => {
      ol.style.counterReset = `reversed-counter ${ol.children.length + 1}`;
    });
  });
</script>

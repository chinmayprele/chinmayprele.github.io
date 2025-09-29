---
title: Presentations
layout: default
parent: Research Products
---

# Presentations

<ol class="reversed">
  <li><i>Understanding The Evolutionary Dynamics Of Transposable Elements in Drosophila Via de novo Identification and Classification</i>, Rutgers Honors Day (2019)</li>
	<li><i>mucroPublication Futures for Multi-Orhtolog Publications</i>, GEP Faculty Workship (2023)</li>

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

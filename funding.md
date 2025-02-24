---
title: Funding
layout: default
author: cprele
has_toc: true
nav_order: 11
---

# The University of Alabama, Tuscaloosa, AL

<ol class="reversed">
	<li><i>Conference & Research Support Funding</i>, The University of Alabama (<b>2024</b>) <code>$1,000 USD</code>
		<ol>
			<li>To attend The Allied Genetics Conference 2024 in National Harbor, MD</li>
		</ol>
	</li>
	<li><i>Summer Institute in Statistical Genetics</i>, University of Washington, School of Public Health (<b>2022</b>) <code>$900 USD</code>
		<ol>
			<li>Learning Statistical Genetics with a concentration in the following</li>
			<li>Introduction to R</li>
			<li>Statistical Genetics</li>
			<li>Computational Pipeline for WGS Data</li>
		</ol>
	</li>
	<li><i>Conference & Research Support Funding</i>, The University of Alabama (<b>2022</b>) <code>$1,000 USD</code>
		<ol>
			<li>To attend the 63rd Drosophila Conference 2022 held in San Diego, CA</li>
		</ol>
	</li>
	<li><i>Summer Institute in Statistical Genetics</i>, University of Washington, School of Public Health (<b>2021</b>) <code>$900 USD</code>
		<ol>
			<li>Learning Statistical Genetics with a concentration in the following</li>
			<li>Bayesian Statistics for Genetics</li>
			<li>Pathway & Network Analysis for Omics Data</li>
			<li>MCMC for Genetics</li>
		</ol>
	</li>
</ol>

# Rutgers University, New Brunswick, NJ

0. _Aresty Research Fellowship_, Rutgers University (**2017**) `$950 USD`
	- To study the Genetic Variation in the Repetitive Sequence Content of _D. melanogaster_ using Oxford Nanopore

<style>
/* Reset the counter for the outer <ol> */
ol.reversed {
  counter-reset: list-counter; /* Initialize counter */
}

/* Style for the outer <ol> and its <li> elements */
ol.reversed > li {
  list-style: none;
  counter-increment: list-counter; /* Increment for each item in the outer <ol> */
  position: relative;
}

/* Add numbering to the outer <ol> items */
ol.reversed > li::before {
  content: counter(list-counter, decimal) ". "; /* Display the current number */
  position: absolute;
  left: -2em;
}

/* Reset the counter for the nested <ol> */
ol.reversed li ol {
  counter-reset: nested-counter; /* Initialize separate counter for nested <ol> */
}

/* Style for nested <ol> items */
ol.reversed li ol li {
  list-style: decimal; /* Default numbering for nested <ol> */
}

/* Optional: If you want the nested lists to have their own independent numbers */
ol.reversed li ol li::before {
  content: counter(nested-counter, decimal) ". "; /* Numbering for nested list */
  position: relative;
  left: 0;
}
</style>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    // Reset the outer <ol> to start from the correct number
    document.querySelectorAll("ol.reversed").forEach(ol => {
      ol.style.counterReset = `list-counter ${ol.children.length + 1}`; /* Start from length + 1 to count down */
    });
  });
</script>

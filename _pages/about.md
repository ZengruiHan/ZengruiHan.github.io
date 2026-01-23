---
permalink: /
title: "Welcome to Zengrui Han's homepage"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html

---


**About Me**

- I'm a Brin Postdoctoral Fellow in the Mathematics Department at the University of Maryland, College Park, working with [Amin Gholampour](https://math.umd.edu/~amingh/). I obtained my Ph.D. at Rutgers University in 2025 under [Lev Borisov](https://sites.math.rutgers.edu/~borisov/). Prior to that, I obtained my bachelor's degree from University of Science and Technology of China in 2020.

- My main research interest is Algebraic Geometry, especially mirror symmetry and related areas. See [here](https://zengruihan.github.io/research/) for more details.

- I'm co-organizing the [Algebraic Geometry Seminar](https://www-math.umd.edu/research/seminars/algebraic-geometry.html) at University of Maryland College Park with Dori Bejleri, Amin Gholampour and Junyan Zhao.

- Fall 2025: learning seminar on log geometry -- [seminar website](https://sites.google.com/umd.edu/log-gemetry).

<div id="random-quote">
  <div id="rq-text" class="rq-text"></div>
  <div id="rq-source" class="rq-src"></div>
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const quotes = {{ site.data.quotes | jsonify }};
  if (!Array.isArray(quotes) || quotes.length === 0) return;

  const q = quotes[Math.floor(Math.random() * quotes.length)];

  const textEl = document.getElementById('rq-text');
  const srcEl  = document.getElementById('rq-source');
  if (!textEl || !srcEl) return;

  textEl.textContent = q.text || '';
  srcEl.textContent  = q.source ? ('— ' + q.source) : '';
});
</script>

<style>
.random-quote .rq-source { text-align: right; }
</style>


<a href="https://info.flagcounter.com/u8zB"><img src="https://s11.flagcounter.com/count/u8zB/bg_FFFFFF/txt_000000/border_FFFFFF/columns_2/maxflags_6/viewers_0/labels_0/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>

<font size=1>(Last Update: 01/23/2026)</font>

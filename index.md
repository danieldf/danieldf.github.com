---
layout: page
title: Ars Physica
tagline: Free Science 2.0
---
{% include JB/setup %}

## Hello World…

I work with mathematical and nonperturbative aspects of [Gauge Theory](http://www.scholarpedia.org/article/Gauge_theories),
and their relations to [symmetry breaking](http://plato.stanford.edu/entries/symmetry-breaking/)
([local](http://www.scholarpedia.org/article/Englert-Brout-Higgs-Guralnik-Hagen-Kibble_mechanism) or
[global](http://www.scholarpedia.org/article/Spontaneous_symmetry_breaking_in_quantum_systems)) and how the
[moduli space](http://en.wikipedia.org/wiki/Moduli_space) and its topology determine the quantization of the physical
system at hand. I am also interested in quantum phases and the space of quantum field theories, non-linear Fredholm theory,
branes and [topological quantization](http://projecteuclid.org/euclid.cmp/1103943448) (which is related to the previous
topic via [Index Theorems](http://en.wikipedia.org/wiki/Atiyah%E2%80%93Singer_index_theorem)); noncommutative and
spectral geometry, and their relation to deformation and geometric quantization;
[Higgs Bundles](http://www.numdam.org/item?id=PMIHES_1992__75__5_0); [Geometric Langlands Duality](http://arxiv.org/abs/0906.2747)
(dualities in general: AdS/CFT, modular and mirror symmetry, etc); quantum fields in curved spaces; higher gauge theory
and category theory; and so on — and their relations to Quantum Gravity.

Lately, I have also been peaking at some problems in Theoreical and Computational Neuroscience,
e.g., [Ersätz-Brain](http://www.cog.brown.edu/Research/ErsatzBrainGroup/).

Using the [arXivs](http://arxiv.org/)' notation: [hep-th](http://arxiv.org/archive/hep-th), [math-ph](http://arxiv.org/archive/math-ph),
[hep-lat](http://arxiv.org/archive/hep-lat), [gr-qc](http://arxiv.org/archive/gr-qc).

My scientific articles can be found in the [arXivs](http://arxiv.org/a/ferrante_d_1), or in [inSPIRE](http://bit.ly/ddfinspire);
and my [Lattes CV](http://lattes.cnpq.br/0783279382148211) (pt_BR).


MathJax: $$ \mathscr{Z}_{\mathcal{C}}(J) = \int_{\mathcal{C}} e^{i\, S(\varphi)}\, e^{i\, J\, \varphi}\, \mathcal{D}\varphi = \mathrm{Tr}_{\mathcal{C}} (e^{i\, S}\, e^{i\, J\, \varphi})\;. $$


## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.

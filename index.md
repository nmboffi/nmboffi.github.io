---
layout: default
---

<div class="header-section" style="display: flex; align-items: center; gap: 2rem; margin-bottom: 2rem;">
  <img src="../images/me_hammock.png" alt="Nicholas Boffi" style="width: 480px; border: 2px solid #000;">
  <div style="flex: 1; display: flex; flex-direction: column; justify-content: center; align-items: center;">
    <h1 style="margin: 0 0 0.5rem 0; font-size: 3.2rem; color: #222;">Nicholas M. Boffi</h1>
    <p style="margin: 0.5rem 0 0 0; font-size: 1.44rem;">nboffi at andrew dot cmu dot edu</p>
    <p style="margin: 0 0; font-size: 1.44rem;">
      <a href="https://scholar.google.com/citations?user=_jkX2q0AAAAJ&hl=en&oi=ao">Scholar</a> /
      <a href="https://github.com/nmboffi">GitHub</a> /
      <a href="https://x.com/nmboffi">Twitter</a> /
      <a href="https://nmboffi.github.io/pdfs/boffi_cv_8_25.pdf">CV</a>
    </p>
  </div>
</div>

<style>
@media (max-width: 720px) {
  .header-section {
    flex-direction: column !important;
    text-align: center !important;
    gap: 0.5rem !important;
    margin-bottom: 1rem !important;
  }

  .header-section img {
    width: 100% !important;
    border: 1px solid #000 !important;
  }

  .header-section h1 {
    font-size: 1.5rem !important;
    margin: 0.25rem 0 !important;
  }

  .header-section p {
    font-size: 0.85rem !important;
    margin: 0.15rem 0 !important;
  }
}
</style>

<p>I am an assistant professor in the <a href="https://www.ml.cmu.edu">Machine Learning Department</a> and the <a href="https://www.cmu.edu/math/index.html">Department of Mathematical Sciences</a> at CMU. I lead a focused team that studies the algorithmic foundations of generative models and their application to problems across science and engineering. Previously, I was a Courant Instructor at the Courant Institute of Mathematical Sciences working with <a href="https://wp.nyu.edu/courantinstituteofmathematicalsciences-eve2/">Eric Vanden-Eijnden</a>. I completed my PhD in applied mathematics at Harvard co-advised by <a href="https://scholar.google.com/citations?user=TcREpMQAAAAJ&hl=en&oi=ao">Jean-Jacques Slotine</a> and <a href="https://scholar.google.com/citations?user=IS_xUuIAAAAJ&hl=en&oi=ao">Chris Rycroft</a>. A longer bio is <a href="{{ site.baseurl }}/about">here</a>.</p>

<p style="margin-top: 1rem; text-align: center;">
  <a href="#research">Research</a> /
  <a href="#publications">Publications</a> /
  <a href="#code">Code</a> /
  <a href="#teaching">Teaching</a> /
  <a href="{{ site.baseurl }}/applications">Application Materials</a>
</p>

<!-- <h2 style="margin-top: 2.5rem;">⭐ News ⭐</h2>

{% include news-list.html news=site.data.news limit=6 %} -->

{% include research-section.html %}

<h2 id="publications" style="margin-top: 2.5rem;">Publications</h2>

{% include papers-list.html papers=site.data.publications self_name="Nicholas M. Boffi" %}

{% include code-section.html %}

{% include teaching-section.html %}

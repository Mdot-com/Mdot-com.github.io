---
layout: archive
title: ""
author_profile: false
sidebar: false
---

<style>
  .page__content,
  .archive {
    max-width: 1500px;
    margin: 0 auto;
    padding: 1em;
    text-align: justify;
  }
  .page, #main {
    display: flex;
    justify-content: center;
    width: 100%;
  }
  .archive { width: 100%; }
  img { max-width: 100%; border: 1px solid #ccc; margin-top: 0.5em; }
</style>

<div class="page__content">

<h2>About Us</h2>
<p>
  We are the <strong>Massive Star Group</strong> at Armagh Observatory, focusing on the extremes of stellar physics—from metal‑free Population III stars to modern supermassive stars. Using self‑consistent hydrodynamic atmosphere models, we tackle stellar winds, mass loss, and the cosmic feedback of the most massive stars.
</p>

<h2>Group Lead</h2>
<p>
  <strong>Professor Jorick S. Vink</strong> is a leading theoretical astrophysicist at Armagh Observatory whose models of radiation‑driven winds in very massive stars have reshaped our understanding of stellar feedback, black hole seed formation, and chemical enrichment.
</p>

<h2>Team Members</h2>
<ul>
  <li>Ciaran Furey – PhD Student</li>
  <li>Ethan Winch – PhD Student</li>
  <li>Gautham Sabhahit – Postdoctoral Assistant</li>
  <li>Erin Higgins – Former Postdoctoral Researcher</li>
  <li>Andreas Sander – Former Postdoctoral Researcher</li>
</ul>

<h2>Research Highlights</h2>

<div>
  <h3>Hydrodynamic Mass Estimates for R136a1</h3>
  <img src="/assets/images/R136a1_model.png" alt="R136a1 hydrodynamic model">
  <p>
    <a href="/publications/#sabhahit2025">Sabhahit, Vink &amp; Sander (2025)</a> computed the first hydrodynamically consistent non-LTE atmosphere models for WNh stars in R136 and R144, empirically and theoretically deriving mass-loss rates and wind speeds. They constrained R136a1’s present-day mass at ~233 M⊙—a key benchmark for VMS physics.
  </p>
</div>

<div>
  <h3>Nitrogen Enrichment from Very Massive Stars</h3>
  <img src="/assets/images/nitrogen_galaxies.png" alt="Nitrogen in high‑z galaxies">
  <p>
    <a href="/publications/#vink2023">Vink (2023)</a> argued that early‑universe galaxies, including GN‑z11 and the Sunburst Arc, show high nitrogen content likely originating from VMS winds (100–1000 M⊙). These stars dominate chemical feedback and stellar ionization in young systems.
  </p>
</div>

<div>
  <h3>Universal Wind Behavior across the HR Diagram</h3>
  <img src="/assets/images/red_supergiant_kink.png" alt="RSG wind kink">
  <p>
    <a href="/publications/#vink2023rsg">Vink and Sabhahit (2023)</a> identified a universal “wind kink” at the transition from optically thin to thick winds. Applied to red supergiants, this new RSG mass-loss prescription naturally reproduces the Humphreys‑Davidson limit and resolves long-standing supernova evolution issues.
  </p>
</div>

<div>
  <h3>Metallicity‑dependent Wind Scaling for OB Stars</h3>
  <img src="/assets/images/metallicity_scaling.png" alt="Metallicity scaling of winds">
  <p>
    <a href="/publications/#vink2021">Vink &amp; Sander (2021)</a> updated the Monte Carlo mass-loss recipe for massive OB stars, revealing a weaker terminal velocity dependence on metallicity and a strong relation between mass-loss rates and metallicity: \(\dot{M} \propto Z^{0.42–0.85}\) depending on temperature regime. This has direct implications for low-metallicity LIGO/Virgo black hole progenitors.
  </p>
</div>

<h2>Recent Publications</h2>
<ul>
  {% assign first_author_pubs = site.publications | where: "category", "manuscripts" | sort: "date" | reverse | slice: 0, 3 %}
  {% for pub in first_author_pubs %}
    <li style="margin-bottom: 1.5em;">
      <strong><a href="{{ pub.url }}">{{ pub.title }}</a></strong><br>
      <em>{{ pub.authors | join: ", " }}</em><br>
      <span>{{ pub.content | strip_html | truncatewords: 30 }}</span>
    </li>
  {% endfor %}
</ul>
<p><a href="/publications/">More publications →</a></p>

<h2>News & Updates</h2>
<ul>
  <li><strong>July 2025:</strong> Sabhahit et al. 2025 accepted in *A&A* on R136a1 hydrodynamic modeling.</li>
</ul>

<h2>Contact</h2>
<p>
  Interested in collaborating or joining the team? Contact <a href="mailto:jorick.vink@armagh.ac.uk">Prof. Jorick Vink</a> for PhD or postdoc opportunities.
</p>

</div>

---
permalink: /
title: "Profile"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Short bio
Hengyuan Chang is a researcher at the Japan Advanced Institute of Science and Technology [JAIST](https://www.jaist.ac.jp/). He received Ph.D. in information science in [Human-Centered AI Laboratory](https://www.jaist.ac.jp/~xie/lab.html), JAIST, Ishikawa, Japan, supervised by Prof. Haoran Xie.
He received his bachelor's degree in computer science at Donghua University, Shanghai, China, and his master degree in information science at JAIST, Ishikawa, JAPAN. His research lies at the intersection of image&video generation and fluid dynamics.

---
<section class="research-areas" id="research">

  <h2 class="section-title">Research</h2>

  <div class="research-vision">
    <p>
      My research explores generative AI for modeling, controlling,
      and understanding complex physical systems.
    </p>
  </div>

  <div class="research-grid">

    <div class="research-card">
      <div class="research-number">01</div>

      <h3>Controllable Generation</h3>

      <p>
        Developing controllable image and video generative models
        that respond precisely to sparse, intuitive, and structured conditions.
      </p>

      <div class="research-tools">
        <span>Image &amp; Video Generation</span>
      </div>
    </div>


    <div class="research-card">
      <div class="research-number">02</div>

      <h3>Physics-Informed Generation</h3>

      <p>
        Incorporating physical priors and dynamics into generative models
        to improve temporal consistency, interpretability,
        and physical plausibility.
      </p>

      <div class="research-tools">
        <span>Physics-Informed Learning</span>
        <span>Physical Constraints</span>
      </div>
    </div>


    <div class="research-card">
      <div class="research-number">03</div>

      <h3>Learning Physical Dynamics</h3>

      <p>
        Learning spatiotemporal representations and dynamics
        from simulation data for complex fluid
        and coupled physical systems.
      </p>

      <div class="research-tools">
        <span>Fluid Dynamics</span>
        <span>Scientific Machine Learning</span>
      </div>
    </div>

  </div>

</section>

---
## Selected Publications

{% assign selected_pubs = site.publications | sort: "index" %}

{% for post in selected_pubs limit: 20 %}
  {% include publication-single.html %}
{% endfor %}

---
## Experiences
2025.05 - 2026.02, Research Collaboration, [ANIMINS](https://www.meti.go.jp/policy/mono_info_service/geniac/selection_data_2/index.html), [OLM, Digital, Inc](https://www.olm.co.jp/rd), Japan (Remote).

2018.11 - 2020.02, research student, Tokyo Metropolitan University, Japan.

---
## Educations
Ph.D. in Information Science, JAIST, Japan (2022.04 – 2026.03)

M.S. in Information Science, JAIST, Japan (2020.04 – 2022.03)

B.E. in Computer Science, Donghua University, China (2014.09 – 2018.06)


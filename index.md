---
layout: default
title: Eric Newland
---
Senior Research Associate at the University of Bristol

I am a volcanologist researching volcanic plumes and unrest using mathematical models, fluid-dynamical experiments and geophysical observations.

My current research focuses on the dynamics of volcanic plumes as part of the **Ex-X: Expecting the Unexpected** NERC project at the University of Bristol.
## About

I am a Senior Research Associate at the University of Bristol. Previously, I worked on the FEVER project at University College London, investigating unrest at volcanoes reawakening after long repose. I completed my PhD in Geophysical Fluid Dynamics at the University of Cambridge and my MSci in Geophysics at Imperial College London.

## Research

My research interests include:

- Volcanic plume dynamics
- Unsteady and starting plumes
- Volcanic deformation and unrest
- Mathematical and numerical modelling
- Eruption forecasting

<h2>Research gallery</h2>

<div class="gallery-scroll">

  <figure class="gallery-item">
    <button
      class="gallery-button"
      type="button"
      data-full="{{ '/assets/img/research/particle-plumes.jpg' | relative_url }}"
      data-alt="Laboratory experiments investigating volcanic plume dynamics">
  
      <img
        src="{{ '/assets/img/research/particle-plumes.jpg' | relative_url }}"
        alt="Laboratory experiments investigating volcanic plume dynamics">
  
    </button>
  
    <figcaption>
      Laboratory experiments investigating volcanic plume dynamics.
    </figcaption>
  </figure>

  <figure class="gallery-item">
    <button
      class="gallery-button"
      type="button"
      data-full="{{ '/assets/img/research/crustal-weakening.jpg' | relative_url }}"
      data-alt="Geophysical observations of volcanic unrest">
  
      <img
        src="{{ '/assets/img/research/crustal-weakening.jpg' | relative_url }}"
        alt="Geophysical observations of volcanic unrest">
  
    </button>
  
    <figcaption>
      Tracking crustal weakening as volcanic systems approach rupture.
    </figcaption>
  </figure>

</div>

<p class="gallery-hint">→</p>

<dialog class="gallery-lightbox" id="gallery-lightbox">

  <button
    class="lightbox-close"
    type="button"
    aria-label="Close enlarged image">
    &times;
  </button>

  <img id="lightbox-image" src="" alt="">

</dialog>


## Publications

<ol>
  <li>
    <strong>Newland, E. L.</strong> &amp; Kilburn, C. R. J. (2026).
    Crustal weakening before rupture at volcanoes after long repose.
    <em>Nature Communications</em>.
    <a href="https://doi.org/10.1038/s41467-026-77001-5"
       target="_blank" rel="noopener noreferrer">doi:10.1038/s41467-026-77001-5</a>
  </li>

  <li>
    <strong>Newland, E. L.</strong> &amp; Woods, A. W. (2024).
    The dynamics of impinging plumes from a moving source.
    <em>Journal of Fluid Mechanics</em>, <strong>982</strong>, A6.
    <a href="https://doi.org/10.1017/jfm.2024.104"
       target="_blank" rel="noopener noreferrer">doi:10.1017/jfm.2024.104</a>
  </li>

  <li>
    <strong>Newland, E. L.</strong> &amp; Woods, A. W. (2023).
    On particle fountains in a crossflow.
    <em>Journal of Fluid Mechanics</em>, <strong>964</strong>, A10.
    <a href="https://doi.org/10.1017/jfm.2023.342"
       target="_blank" rel="noopener noreferrer">doi:10.1017/jfm.2023.342</a>
  </li>

  <li>
    Collins, G. S., <strong>Newland, E. L.</strong>, et al. (2022).
    The meteoroid fragmentation in the Martian atmosphere and the formation of crater clusters.
    <em>Journal of Geophysical Research: Planets</em>, <strong>127</strong>(3), e2021JE007149.
    <a href="https://doi.org/10.1029/2021JE007149"
       target="_blank" rel="noopener noreferrer">doi:10.1029/2021JE007149</a>
  </li>

  <li>
    <strong>Newland, E. L.</strong>, Mingotti, N. &amp; Woods, A. W. (2022).
    Dynamics of deep-submarine volcanic eruptions.
    <em>Scientific Reports</em>, <strong>12</strong>, 3276.
    <a href="https://doi.org/10.1038/s41598-022-07351-9"
       target="_blank" rel="noopener noreferrer">doi:10.1038/s41598-022-07351-9</a>
  </li>

  <li>
    <strong>Newland, E. L.</strong> &amp; Woods, A. W. (2021).
    On particle fountains in a stratified environment.
    <em>Journal of Fluid Mechanics</em>, <strong>917</strong>, A22.
    <a href="https://doi.org/10.1017/jfm.2021.295"
       target="_blank" rel="noopener noreferrer">doi:10.1017/jfm.2021.295</a>
  </li>
</ol>

## Contact

<ul>
  <li>University of Bristol</li>
  <li><a href="https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=hkzlhUgAAAAJ&scilu=&scisig=AOcXxEUAAAAAao7V_-sCvE5HQmvwBZULbERWqSo&gmla=AKCpqFz4bK12Dt9fFqPaDm5fk8Ar6DdkZoB2on8eTty-hHEz-f0FnJxmuJkpJ8zbPQGoQuh6QAh9yCc0HJDDmux7FB5SlN57eEFyxPY&sciund=9487580993215789303" target="_blank" rel="noopener noreferrer">Google Scholar</a></li>
  <li><a href="https://www.linkedin.com/in/eric-newland-42aa13128/" target="_blank" rel="noopener noreferrer">LinkedIn</a></li>
  <li>Email: <a href="mailto:px26843@bristol.ac.uk">px26843@bristol.ac.uk</a></li>
</ul>


<script>
  const lightbox = document.getElementById("gallery-lightbox");
  const lightboxImage = document.getElementById("lightbox-image");
  const closeButton = lightbox.querySelector(".lightbox-close");
  const galleryButtons = document.querySelectorAll(".gallery-button");

  galleryButtons.forEach((button) => {
    button.addEventListener("click", () => {
      lightboxImage.src = button.dataset.full;
      lightboxImage.alt = button.dataset.alt;
      lightbox.showModal();
    });
  });

  closeButton.addEventListener("click", () => {
    lightbox.close();
  });

  lightbox.addEventListener("click", (event) => {
    if (event.target === lightbox) {
      lightbox.close();
    }
  });
</script>

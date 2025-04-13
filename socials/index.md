---
title: Social
nav:
  order: 6
  tooltip: Social Images
---

# {% include icon.html icon="fa-solid fa-images" %}Lab Socials

Explore photos from the RAIL lab – see our work and our people.

{% include section.html %}

<div class="gallery">

  <figure>
    {% assign img_src = '/images/rsna2024.jpg' | relative_url %}
    {% assign caption = "RAIL Team at RSNA 2024" %}
    <a href="{{ img_src }}" data-lightbox="social-gallery" data-title="{{ caption }}">
      <img src="{{ img_src }}" alt="{{ caption }}">
    </a>
    <figcaption>{{ caption }}</figcaption>
  </figure>

  <!-- <figure>
    {% assign img_src = '/images/rsna2024.jpg' | relative_url %}
    {% assign caption = "RAIL Team at RSNA 2024" %}
    <a href="{{ img_src }}" data-lightbox="social-gallery" data-title="{{ caption }}">
      <img src="{{ img_src }}" alt="{{ caption }}">
    </a>
    <figcaption>{{ caption }}</figcaption>
  </figure>

  <figure>
    {% assign img_src = '/images/rsna2024.jpg' | relative_url %}
    {% assign caption = "RAIL Team at RSNA 2024" %}
    <a href="{{ img_src }}" data-lightbox="social-gallery" data-title="{{ caption }}">
      <img src="{{ img_src }}" alt="{{ caption }}">
    </a>
    <figcaption>{{ caption }}</figcaption>
  </figure>

  <figure>
    {% assign img_src = '/images/rsna2024.jpg' | relative_url %}
    {% assign caption = "RAIL Team at RSNA 2024" %}
    <a href="{{ img_src }}" data-lightbox="social-gallery" data-title="{{ caption }}">
      <img src="{{ img_src }}" alt="{{ caption }}">
    </a>
    <figcaption>{{ caption }}</figcaption>
  </figure>

  <figure>
    {% assign img_src = '/images/rsna2024.jpg' | relative_url %}
    {% assign caption = "RAIL Team at RSNA 2024" %}
    <a href="{{ img_src }}" data-lightbox="social-gallery" data-title="{{ caption }}">
      <img src="{{ img_src }}" alt="{{ caption }}">
    </a>
    <figcaption>{{ caption }}</figcaption>
  </figure> -->

</div>

<style>
/* Updated gallery styling */
.gallery {
  display: grid;
  /* Default: 1 column for small screens */
  grid-template-columns: 1fr;
  gap: 1.5rem; /* Spacing between images */
  margin-top: 2rem;
  width: 100vw;
  position: relative;
  left: 50%;
  transform: translateX(-50%);
  padding-left: 1rem;
  padding-right: 1rem;
}

/* Medium screens: 2 columns */
@media (min-width: 600px) {
  .gallery {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Large screens: 3 columns */
@media (min-width: 992px) {
  .gallery {
    grid-template-columns: repeat(3, 1fr);
  }
}

.gallery figure {
  margin: 0; /* Remove default figure margin */
  text-align: center;
}

.gallery img {
  width: 100%; /* Make image fill the grid column */
  height: auto; /* Maintain aspect ratio */
  display: block; /* Remove extra space below image */
  border: 1px solid var(--light-gray); /* Optional border */
  border-radius: var(--rounded); /* Use theme rounding */
}

.gallery figcaption {
  font-size: 1.3rem;
  margin-top: 0.5rem;
  color: var(--black);
}
</style>
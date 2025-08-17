---
layout: page
permalink: /gallery/
title: Gallery
nav: true
nav_order: 8
---

<div class="gallery-list">

  <!-- 2024.03 HPCA -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2024-03-HPCA/' | relative_url }}">
      <img src="/assets/gallery/2024_03_HPCA/001.jpg" alt="2024.03 HPCA in Edinburgh, Scotland">
      <h3>2024.03 HPCA in Edinburgh, Scotland</h3>
      <p>2024.03</p>
    </a>
  </div>

  <!-- 2024.02 MS Graduation -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2024-02-MS-Graduation/' | relative_url }}">
      <img src="/assets/gallery/2024_02_MS_Graduation/001.jpg" alt="2024.02 M.S. Graduation in SKKU">
      <h3>2024.02 M.S. Graduation in SKKU</h3>
      <p>2024.02</p>
    </a>
  </div>

  <!-- 2023.11 SC -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2023-11-SC/' | relative_url }}">
      <img src="/assets/gallery/2023_11_SC/001.jpg" alt="2023.11 SC in Denver, United States">
      <h3>2023.11 SC in Denver, United States</h3>
      <p>2023.11</p>
    </a>
  </div>

  <!-- 2023.11 SAIF -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2023-11-SAIF/' | relative_url }}">
      <img src="/assets/gallery/2023_11_SAIF/001.jpg" alt="2023.11 SAIF in Suwon, South Korea">
      <h3>2023.11 SAIF in Suwon, South Korea</h3>
      <p>2023.11</p>
    </a>
  </div>

  <!-- 2023.02 ISSCC -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2023-02-ISSCC/' | relative_url }}">
      <img src="/assets/gallery/2023_02_ISSCC/001.jpg" alt="2023.02 ISSCC in San Francisco, United States">
      <h3>2023.02 ISSCC in San Francisco, United States</h3>
      <p>2023.02</p>
    </a>
  </div>

  <!-- 2022.11 SC -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2022-11-SC/' | relative_url }}">
      <img src="/assets/gallery/2022_11_SC/001.jpg" alt="2022.11 SC in Dallas, United States">
      <h3>2022.11 SC in Dallas, United States</h3>
      <p>2022.11</p>
    </a>
  </div>

  <!-- 2022.10 ISOCC -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2022-10-ISOCC/' | relative_url }}">
      <img src="/assets/gallery/2022_10_ISOCC/001.jpg" alt="2022.10 ISOCC in Gangneung, South Korea">
      <h3>2022.10 ISOCC in Gangneung, South Korea</h3>
      <p>2022.10</p>
    </a>
  </div>

  <!-- 2022.07 DAC -->
  <div class="gallery-item">
    <a href="{{ '/gallery/2022-07-DAC/' | relative_url }}">
      <img src="/assets/gallery/2022_07_DAC/001.jpg" alt="2022.07 DAC in San Francisco, United States">
      <h3>2022.07 DAC in San Francisco, United States</h3>
      <p>2022.07</p>
    </a>
  </div>

</div>

<style>
.gallery-list {
  display: grid;
  gap: 20px;
  /* Default 1column */
  grid-template-columns: 1fr;
}

.gallery-list img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  display: block;
}

.gallery-list a {
  text-decoration: none;
  color: inherit;
}

.gallery-list h3 {
  margin-top: 8px;
  font-size: 1rem;
  text-align: center;
}

.gallery-list p {
  margin-top: 4px;
  font-weight: 600;
  text-align: center;
  font-size: 0.9rem;
}

/* When screen is more than 600px, 2column */
@media (min-width: 600px) {
  .gallery-list {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* When screen is more than 900px, 3column */
@media (min-width: 900px) {
  .gallery-list {
    grid-template-columns: repeat(3, 1fr);
  }
}
</style>

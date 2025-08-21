---
# Leave the homepage title empty to use the site title
title:
date: 2025-08-04
type: landing

sections:
  - block: markdown
    content:
      title: Research Overview
      text: |
        The Shi Photonics Group explores new frontiers in light manipulation using nanophotonics. Our research spans the entire stack — from new physics of nanoscale light–matter interaction, to innovative photonic components, to fully integrated photonic systems. A key focus is bridging nanophotonics with active platforms such as MEMS, liquid crystals, and nonlinear materials to enable next-generation programmable light processing. These technologies open new possibilities for applications in both the classical and quantum domains, including advanced imaging, sensing, displays, and emerging quantum computing systems.
    design:
      columns: '1'
      align: center

  - block: markdown
    content:
      title: ""
      text: |
        <link rel="stylesheet" href="https://unpkg.com/swiper@10/swiper-bundle.min.css">

        <div class="swiper" id="welcome-slider">
          <div class="swiper-wrapper">
            <div class="swiper-slide"><img src="/uploads/pic.png" alt="Image 1"></div>
            <div class="swiper-slide"><img src="/uploads/metalens.png" alt="Image 2"></div>
            <div class="swiper-slide"><img src="/uploads/picschematic.png" alt="Image 3"></div>
            <div class="swiper-slide"><img src="/uploads/poincare.png" alt="Image 4"></div>
          </div>

          <!-- controls -->
          <div class="swiper-button-prev"></div>
          <div class="swiper-button-next"></div>
          <div class="swiper-pagination"></div>
        </div>

        <script src="https://unpkg.com/swiper@10/swiper-bundle.min.js"></script>
        <script>
          new Swiper('#welcome-slider', {
            loop: true,
            slidesPerView: 1,
            spaceBetween: 12,
            keyboard: { enabled: true },
            navigation: { nextEl: '.swiper-button-next', prevEl: '.swiper-button-prev' },
            pagination: { el: '.swiper-pagination', clickable: true },
            // autoplay: { delay: 4000, pauseOnMouseEnter: true, disableOnInteraction: false },
            // grabCursor: true,
          });
        </script>

        <style>
          #welcome-slider { max-width: 980px; margin: 0 auto; }
          #welcome-slider .swiper-slide {
            display: flex;
            justify-content: center;
            align-items: center;
            background: #fff;
          }
          #welcome-slider img {
            height: 400px;        /* set consistent height */
            width: auto;          /* width adjusts automatically */
            object-fit: contain;  /* keep aspect ratio, no cropping */
            display: block;
          }
        </style>
    design:
      columns: '1'
      align: center

    
    
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
---

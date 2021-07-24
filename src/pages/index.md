---
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/DSC_3267_1.jpg
    background_image_opacity: 75
    content: |
      # The Botanicart Society

      Aggiungere frase accattivante...
    actions:
      - title: Vai allo store
        url: /store
        arrow: false
        style: primary
      - title: Scoprici
        url: lorem-ipsum
        style: link
        arrow: true
        type: action
  - type: featured_products_section
    section_id: best_sellers_section
    title: PIANTE
    icon: false
    light_title: true
    featured_products:
      - src/pages/products/plant1.md
      - src/pages/products/plant3.md
      - src/pages/products/plant5.md
      - src/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - src/pages/category/bigplants.md
      - src/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
  - type: promotion_section
    section_id: promotion_section
    title: SCOPRI IL NOSTRO STORE
    subtitle: Visualizza i nostri prodotti ed esclusive collab.
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: Vai allo Store
      url: /store
      style: primary
      arrow: true
template: home
---

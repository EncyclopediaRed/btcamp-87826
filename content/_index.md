---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: >
      # Temporary Emergency Shelters


      Don't forget to add your Snipcart API key to the site's configuration to
      enable Cart actions.
    actions:
      - title: See all items
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Best sellers
    icon: true
    light_title: true
    featured_products:
      - content/products/plant1.md
      - content/products/plant3.md
      - content/products/plant5.md
      - content/products/plant7.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Testimonials
    testimonials:
      - author:
          name: Bob Loblaw
          location: 'Colorado, USA'
        text: >-
          The Büt Camp system saved my bacon when I followed a bear off the main
          trail and got lost. It took days to find me, and I only packed for day
          hike. I "bearly" made it out. But Büt Camp kept me sheltered until the
          rescue squad found me.
      - author:
          name: Ella Vader
          location: 'MO, USA'
        text: "I'm not ready to be raptured yet. So when the apocalypse comes, I've got several Büt Camp emergency shelters. I love that they're environmentally friendly. Can't start a new world without helping out mother nature.\_ Armageddon too old not to have a shelter."
  - type: promotion_section
    section_id: promotion_section
    title: There when you need it.
    subtitle: from $11.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
seo:
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---

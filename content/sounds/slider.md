---
widget: slider
weight: 20
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3000

content:
  slides:
    - title: What is Sounds of Nature?
      content: Learn how we are discovering biodiversity through sound...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: soundscape.jpg
      link:
        icon: book
        icon_pack: fas
        text: Learn More
        url: https://playful-fox-997b3e.netlify.app/sounds-about/
    - title: Check out our results!
      content: Explore last year's results using our interactive explorer
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: soundscape.jpg
      link:
        icon: map
        icon_pack: fas
        text: Learn More
        url: https://playful-fox-997b3e.netlify.app/sounds-results/
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
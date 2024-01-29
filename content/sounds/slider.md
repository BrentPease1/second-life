---
widget: slider
weight: 30
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
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
        url: https://peaselab.com/sounds-about/
    - title: Check out our results!
      content: Explore last year's results using our interactive explorer
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: recording_map_results.jpg
      link:
        icon: map
        icon_pack: fas
        text: Results
        url: https://peaselab.com/sounds-results/
    - title: Ready to Join?
      content: Sign up now!
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: audio_bag.jpg
      link:
        icon: user-plus
        icon_pack: fas
        text: Join Us
        url: https://peaselab.com/sounds-volunteer/
---

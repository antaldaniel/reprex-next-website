---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2200

content:
  slides:
    - title: 🚀  We Are Finalists!
      content: 'Vote for us in The Hague Innovators Award 2022'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.5
        media: contact.jpg
      link:
        icon: fa-solid fa-right-to-bracket
        icon_pack: fas
        text: Read More
        url: ../post/2022-09-13-the-hague-innovators-award/
    - title: 👋 Welcome to Reprex
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: Digital Music Observatory  ☕️
      content: 'Our openmuse'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
      link:
        icon: fa-solid fa-right-to-bracket
        icon_pack: fas
        text: Check Out Our Observatories!
        url: ../#observatories
    - title: Learn R With Our Team
      content: 'Participating in open source is often a highly collaborative experience. We’re encouraged to create in public view, and we’re incentivized to welcome contributions of all kinds from people around the world. This makes the practice of open source as much social as it is technical. [&#9755; slides](http://localhost:4321/slides/learnr-with-reprex)'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: fa-solid fa-right-to-bracket
        icon_pack: fas
        text: Slides
        url: /slides/learnr-with-reprex)
---

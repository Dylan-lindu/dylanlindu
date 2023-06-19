---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

# widget: hero # See https://wowchemy.com/docs/page-builder/
# headless: true # This file represents a page section.
# weight: 10 # Order that this section will appear.
# title: |
#   Liu Bing  
#   Research Group
# hero_media: welcome.jpg
# design:
#   # Choose how many columns the section has. Valid values: 1 or 2.
#   columns: '1'
#   # Add custom styles
#   css_style:
#   css_class:
<!-- --- -->

<!-- <br>

The **Liu Bing Research Group**  focus on clinical translation of multi-modal neuroimaging and neuroscience translation of multi-modal data. -->

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: World-Class Semiconductor Lab
        content: 'Just opened last month!'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000


---
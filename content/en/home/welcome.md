---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

# Page title
title: My page
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      title: Section 1
      subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - post
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true



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

---

<!-- <br>

The **Liu Bing Research Group**  focus on clinical translation of multi-modal neuroimaging and neuroscience translation of multi-modal data.


---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

# Page title
# title: My page
# # Page type - we want a landing page (such as a homepage)
# type: landing

# # Your landing page sections - add as many different content blocks as you like
# sections:
#   # A section to display blog posts
#   - block: collection
#     id: section-1
#     content:
#       title: Section 1
#       subtitle: A subtitle
#       text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
#       # Display content from the `content/post/` folder
#       filters:
#         folders:
#           - post
#     design:
#       # Choose how many columns the section has. Valid values: '1' or '2'.
#       columns: '1'
#       # Choose your content listing view - here we use the `showcase` view
#       view: showcase
#       # For the Showcase view, do you want to flip alternate rows?
#       flip_alt_rows: true



widget: hero
headless: true
weight: 10
title: |
  Lin Du  
hero_media: 22.png
design:
  columns: '2'
  css_style: |
    /* 左 3 份宽度，右侧列只撑到它内容的宽度 */
    --grid-template-columns: 7fr min-content;  
    /* 让整体容器更宽一些 (或去掉下面两行撑满父级) */
    max-width: none;
    width: 90vw;
  css_class: wide-hero

---

<br>
<span style="font-size:25px;">
My name is Lin Du, a second-year master's student in the <span style="color:red">State Key Laboratory of Cognitive Neuroscience and Learning | IDG/McGovern Institute for Brain Research</span>, Beijing Normal University (Ranked No.1 in China for Psychology/Psychiatry/Neuroscience).<br><br><br><br>

I am presently a research scholar at the <span style="color:red">Department of Psychology | Center for Brain Science, Harvard University</span>, supervised by <span style="color:red">Prof. Randy Buckner</span>. Additionally, I am an <span style="color:red">online intern at the Vision and Computational Cognition Group at the Max Planck Institute</span> for Human Cognitive and Brain Sciences under <span style="color:red">Dr. Martin Hebart</span>.

</span>

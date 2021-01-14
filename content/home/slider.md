---
widget: slider
headless: true  # This file represents a page section.

active: true
weight: 120

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 300px


item:
  - title: My Favourites
    content: 'I am center aligned 😄
    align: center
    # Overlay a color or image (optional).
    #overlay_color: '#666'  # An HTML color value.
    #overlay_img: bubbles.jpg  # Image path relative to your `static/media/` folder
    #overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Download my app
    cta_url: 'https://example.org'
    cta_icon_pack: fas
    cta_icon: graduation-cap
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Right
    content: 'Languages I have learned'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
    
---

+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = '5000'

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "450px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "BMSMC"
  content = "R Package"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  # overlay_color = "#666"  # An HTML color value.
  overlay_img = "research/baymsmc.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Link"
  cta_url = "https://github.com/javenrflo/BMSMC"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "Longitudinal Clustering"
  content = "R Shiny Application"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "software/longclust.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
    
  cta_label = "Link"
  cta_url = "https://ph-shiny.iowa.uiowa.edu/javflores/RA_apps/BP%20Project/Policy%20Cluster%20Analyses/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "Principal Components Regression"
  content = "R Shiny Application"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "software/pcreg.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Link"
  cta_url = "https://ph-shiny.iowa.uiowa.edu/javflores/RA_apps/Bullying_Policy_Implementation/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap" 
+++

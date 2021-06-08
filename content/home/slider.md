+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.

[[item]]
  title = "Check out our new paper in Science"
  content = "about interaction networks and diversification!"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/science_2021.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "You can access the paper here"
  cta_url = "https://doi.org/10.1126/science.abf0556"
  cta_icon_pack = "ai"
  cta_icon = "google-scholar"


[[item]]
  title = "ggplot2"
  content = "Tutorial com informações básicas de ggplot2 :smile:"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "tutorial_ggplot2.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Tutorial de ggplot2"
  cta_url = "/post/tutorial_ggplot2/tutorial_ggplot2/"
  cta_icon_pack = "fas"
  cta_icon = "chart-bar"

[[item]]
  title = "Check out our new preprint"
  content = "about mycorrhizae and diversification!"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/header_mujica_biorxiv.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Get it on bioRxiv"
  cta_url = "https://www.biorxiv.org/content/10.1101/824441v1"
  cta_icon_pack = "ai"
  cta_icon = "biorxiv"

[[item]]
  title = "Or go look at my other publications"
  content = "about the birds and the b... I mean, the snakes"
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/paper1.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.
  
  cta_label = "Other Publications"
  cta_url = "https://www.gburin.com/#featured"
  cta_icon_pack = "ai"
  cta_icon = "lattes"
+++

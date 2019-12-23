+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 100  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = "5000"

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "350px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
 # title = "Darwinian Networks Lab"
 # content = "I am center aligned :smile:"
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "dns.gif"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.1  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Play"
  #<!-- cta_url = "https://andreeds.github.io/dns_lab/index.html" -->
  cta_url = "DNS/index.html"
  cta_icon_pack = "fas"
  cta_icon = "play"

[[item]]
  #title = "UofR Jiu-Jitsu"
  #content = "I am left aligned :smile:"
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "jj.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.
  

  cta_label = "UofR Jiu-Jitsu Club"
  cta_url = "http://uofrjiujitsu.com/"
  #cta_icon_pack = "fas"
  #cta_icon = "play"

  [[item]]
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "eva.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.
  

  cta_label = "E.V.A. HQs"
  cta_url = "https://evahqs.tumblr.com/"
  #cta_icon_pack = "fas"
  #cta_icon = "heart"

+++

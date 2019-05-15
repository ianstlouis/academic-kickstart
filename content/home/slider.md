+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Welcome!"
  content = """Allow me to introduce myself."""
  align = "center"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "/slider/ssc_wallpaper.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.15  # Darken the image. Value in range 0-1.

  cta_label = "Bio"
  cta_url = "#about"
  cta_icon_pack = "fas"
  cta_icon = "male"

[[item]]
  title = "Project Highlight"
  content = "Senior Capstone Project."
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#111"  # An HTML color value.
  overlay_img = "/slider/senior_render.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.



  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Let's Play!"
  cta_url = "#projects"
  cta_icon_pack = "fa"
  cta_icon = "gamepad"
  cta_color = "#999"

[[item]]
  title = "Projects"
  content = "Click to learn about some of my projects."
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "/slider/projects_headline.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.4  # Darken the image. Value in range 0-1.



  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Take me there!"
  cta_url = "#projects"
  cta_icon_pack = "fas"
  cta_icon = "project-diagram"

[[item]]
  title = "Resume"
  content = "An amalgamation of academic and professional pursuits."
  align = "left"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "/slider/resume_slider.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "CV"
  cta_url = "files/cv.pdf"
  cta_icon_pack = "fas"
  cta_icon = "file"
+++

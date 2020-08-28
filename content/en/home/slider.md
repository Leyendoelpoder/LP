+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.


# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = "5000"

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "400px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Nuevo episodio"
  content = "La competencia geopolítica detrás de la vacuna COVID-19"
  align = "left"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "headers/izquierda.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Ver"
  cta_url = "https://www.youtube.com/watch?v=WzQOBDBrbac"
  cta_icon_pack = "fab"
  cta_icon = "youtube"

[[item]]
  title = "Próximos episodios"
  content = "Los prejuicios de las Relaciones Internacionales, Cuestionando la enseñanza de las RRII en Sudamérica, Poder y biopolítica durante la pandemia"
  align = "right"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "headers/derecha.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

+++

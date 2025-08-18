# quarto_tips
quarto tips

# Themes

``` markdown
---
title: "Mapping Earth's Pulse: Temporal Ridgeline Visualization in R"
author: Duccio Rocchini
format: 
  revealjs:
    theme: black
editor: visual
---
```

## Available themes

``` md
- beige
- blood
- dark
- default
- league
- moon
- night
- serif
- simple
- sky
- solarized
```
The best is the default for sure. So:

``` md
---
title: "Mapping Earth's Pulse: Temporal Ridgeline Visualization in R"
author: Duccio Rocchini
format: 
  revealjs:
    theme: default
editor: visual
---
```

You can leave without anything otherwise.

Personalized theme [here](https://quarto.org/docs/presentations/revealjs/themes.html).

# Embedding resources

``` md
---
title: "Mapping Earth's Pulse: Temporal Ridgeline Visualization in R"
author: Duccio Rocchini
format: 
  revealjs:
    theme: default
    embed-resources: true
editor: visual
---
```

# Exporting to pdf
in RStudio:
 quarto::quarto_render("~/Documents/lectures_and_seminars/comec_2025_budapest/DUCCIOROCCHINI_Comec2025.qmd", output_format = "revealjs", output_file = "nome_file.pdf")

# Oceanic Eighties

A cool dark mode theme for RStudio. 

Based on the [Oceanic - Eighties tmTheme](https://tmtheme-editor.herokuapp.com/#!/editor/theme/Oceanic%20-%20Eighties) and modified to fit in well with RStudio's blueish Dark Mode UI.

![](oceanic-eighties.png)

## Installation

You'll need RStudio version 1.2. Grab the [preview version here](https://www.rstudio.com/products/rstudio/download/preview/).

Run the following code in RStudio to download and apply the theme.

```r
oceanic_theme <- fs::path_temp("Oceanic-Eighties", ext = "rstheme")
download.file("https://git.io/rstudio-theme-oceanic-eighties", oceanic_theme)
rstudioapi::addTheme(oceanic_theme, apply = TRUE)
```

#### Manual Installation

If the steps above don't work, you can manually download the [oceanic-eighties.rstheme](oceanic-eighties.rstheme) file and place it in `.R/rstudio/themes` in your R home directory (see `path.expand("~")`). Then, in the RStudio appearance settings, select the _Oceanic - Eighties_ editor theme. 

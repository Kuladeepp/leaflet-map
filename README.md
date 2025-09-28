# leaflet-map

This repository hosts a simple **interactive Leaflet map** webpage created using R Markdown.

## 🗺️ What the page shows

- The webpage displays the current date when it was rendered.
- A full interactive map with markers and popups for several landmarks.
- The map is built using the `leaflet` package in R.

## 🚀 How to view it

You can view the webpage here:  
[https://Kuladeepp.github.io/leaflet-map/](https://Kuladeepp.github.io/leaflet-map/)

If the link doesn’t immediately work, make sure GitHub Pages is enabled (see below).

## 🛠️ How it’s built

1. The source file is `index.Rmd` (R Markdown).  
2. It is knitted to produce `index.html`.  
3. The `index.html` is hosted on GitHub Pages so the interactive map is viewable by everyone.

## 📦 Dependencies

This project requires the following R packages:

```r
install.packages("rmarkdown")
install.packages("leaflet")

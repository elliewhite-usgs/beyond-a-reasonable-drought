# Chart Challenge 2023 Contribution

Ellie White

Prompt: anthropocene, Date TBD

## Image(s) 

![20230419_anthropocene_ewhite](https://github.com/whiteellie/chartchallenge-drought/blob/main/out/20230419_anthropocene_ewhite.png)

## Key Takeaways

1. Historic megadroughts lasted nearly a century. Could future droughts last just as long? Such a scenario would eclipse anything the west has seen recently.  

## Data Sources

* LBDA V2: Gille, E.P.; Wahl, E.R.; Vose, R.S.; Cook, E.R. (2017-08-03): NOAA/WDS Paleoclimatology - Living Blended Drought Atlas (LBDA) Version 2 - recalibrated reconstruction of United States Summer PMDI over the last 2000 years. Regional subset used. NOAA National Centers for Environmental Information. https://doi.org/10.25921/7xm8-jn36. Accessed 03/20/2022.

## Key Programs and/or Packages Used
* sessionInfo() = R version 4.2.3 (2023-03-15 ucrt), Platform: x86_64-w64-mingw32/x64 (64-bit), Running under: Windows 10 x64 (build 19044) 
* packages = c("raster", "ncdf4", "sf", "sfheaders", "rgdal", "stringr", "scales", "ggplot2", "ggimage", "lubridate", "tidyverse", "RColorBrewer")

## Overall Process to Create the Viz
1) `targets` pipeline in R to get data ready 
2) `ggplot` to make base plot 
2) PowerPoint to add chart elements

## Design considerations
* Flower colors were picked by considering contrast needed for those with visual impairements and/or colorblindness (508 compliance).
* Flower stem lines serve as a visual guide for the eye from the start of a drought to its end (the flowers) and double encodes the duration variable. 
* Fonts and visual hierarchy was deliberately designed to guide the eye and progressively deliver information.
* Explanatory axis provides more context for general audiences that may not have a frame of reference for the years and different epochs in the common era. 
* Captions, legend, and "How to read the diagram" provide extra information about the underlying data meant to be consumed last if users are interested. 
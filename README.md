# R-learning-resources
These are a collection of resources that I have found helpful in learning R.

## getting started
* [download R](https://www.r-project.org/)
* [download RStudio](https://rstudio.com/products/rstudio/download/) - interface for a more user-friendly R
* [here](https://malco.io/2018/11/05/why-should-i-use-the-here-package-when-i-m-already-using-projects/) - best practices in referencing files in projects

## importing data
* [readr](https://readr.tidyverse.org/) - supports different file formats including csv files

## combining data sets
* [dplyr's join functions](https://dplyr.tidyverse.org/reference/join.html) - includes for example inner_join()

## data manipulation
* [dplyr](https://dplyr.tidyverse.org/)
* [tidyr](https://tidyr.tidyverse.org/) - tidy messy data (e.g., pivoting data from wide to long or long to wide)

## data cleaning
* [gsub](http://www.endmemo.com/r/gsub.php) - replace multiple occurrences of strings
* [janitor](https://garthtarr.github.io/meatR/janitor.html) - cleaning data

## descriptives and data exploration
* [descriptive statistics](https://rpsystats.com/datasets.html#descriptive-statistics) - example of examining data numerically and visually
* [DataExplorer](https://boxuancui.github.io/DataExplorer/) - has a great create_report() function
* [glimpse](https://tibble.tidyverse.org/reference/glimpse.html) - take a glimpse at dataframe
* [skimr](https://github.com/ropensci/skimr) - quickly skim descriptive statistics of data
* [summary](https://www.statmethods.net/stats/descriptives.html) - provides descriptives of data with summary() function
* [hmisc](https://thomaselove.github.io/431notes-2017/summarizing-categorical-variables.html#describe-in-the-hmisc-package-1) - hmisc package has the describe() function to get statistical descriptions
* [psych](https://www.rdocumentation.org/packages/psych/versions/1.0-17/topics/describe) - psych package has the describe() function

## longitudinal data
* [brolgar](https://github.com/njtierney/brolgar)
* [overviewR](https://cosimameyer.github.io/overviewR/articles/overviewR_vignette.html) - examines data and sample coverage across time and conditions

## tables
* [stargazer](https://www.jakeruss.com/cheatsheets/stargazer/)
* [gt](https://gt.rstudio.com/) - create customized tables
* [pander](https://www.statsandr.com/blog/tips-and-tricks-in-rstudio-and-r-markdown/#pander-for-aesthetics) - improve aesthetics of R outputs
* [broom](https://github.com/tidymodels/broom)
* [kable](https://bookdown.org/yihui/rmarkdown-cookbook/kable.html)
* [apaTables](https://www.rdocumentation.org/packages/apaTables/versions/1.5.0) - export APA formatted tables from R to word

## plots
* [ggplot2](https://ggplot2.tidyverse.org/) - data visualization package
* [ggplot2 extensions](https://exts.ggplot2.tidyverse.org/)
* [cowplot](https://cran.r-project.org/web/packages/cowplot/vignettes/introduction.html) - add on to ggplot
* [ggdist](https://mjskay.github.io/ggdist/reference/index.html#section-package-overview) - visualizing distributions and uncertainty
* [ggstatsplot](https://indrajeetpatil.github.io/ggstatsplot/) - graphics that include details of statistical test
* [lattice](https://cran.r-project.org/web/packages/lattice/index.html) - multivariate plotting
* [ggstatsplot](https://indrajeetpatil.github.io/ggstatsplot/) - plots with statistical details
* [ggpubr](http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/) - publication ready plots

### themes
* [hrbrthemes](https://github.com/hrbrmstr/hrbrthemes) - more themes for ggplot2

### color
* [colors in R](http://www.stat.columbia.edu/~tzheng/files/Rcolor.pdf) - pdf of colors in R

### color palettes
* [RColorBrewer](https://www.datanovia.com/en/blog/the-a-z-of-rcolorbrewer-palette/) - package offers palettes for qualitative and quantitative data
* [palette_OkabeIto](https://rdrr.io/github/clauswilke/colorblindr/man/scale_OkabeIto.html) - color-blind friendly, categorical
* [viz palette](https://projects.susielu.com/viz-palette) - helps pick colors for data visualizations
* [color blindness simulator](https://www.color-blindness.com/coblis-color-blindness-simulator/) - test your data visualization with this color blindness simulator
* [scico](https://github.com/thomasp85/scico) - color palettes
* [viridis](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html) - color palettes
* [pals](https://kwstat.github.io/pals/) - collection of color palettes
* [paletteer](https://github.com/EmilHvitfeldt/paletteer) - collection of color palettes
* [color hex codes](https://www.color-hex.com/) - help with color hex codes
* [colorspace](https://cran.r-project.org/web/packages/colorspace/vignettes/colorspace.html) - helps to manipulate colors

### highlighting select data
* [gghighlight](https://cran.r-project.org/web/packages/gghighlight/vignettes/gghighlight.html)
* [highlight](https://cmdlinetips.com/2019/05/how-to-highlight-select-data-points-with-ggplot2-in-r/) - post on how to highlight select data in ggplot

### fonts
* [extrafont](https://cran.r-project.org/web/packages/extrafont/README.html) - using fonts other than PostScript
* [showtext](https://cran.rstudio.com/web/packages/showtext/vignettes/introduction.html) - alternative to extrafont; can use google fonts

### combining multiple plots
* [patchwork](https://patchwork.data-imaginist.com/) - combime multiple plots in same visualization
* [cowplot](https://cran.r-project.org/web/packages/cowplot/vignettes/introduction.html) - arrange plots in grid
* [gridExtra](https://cran.r-project.org/web/packages/egg/vignettes/Ecosystem.html) - lay out multiple plots

### animating plots
* [gganimate](https://gganimate.com/articles/gganimate.html)

### interactive plots
* [shiny](https://github.com/rstudio/shiny)
* [flexdashboard](https://rmarkdown.rstudio.com/flexdashboard/)
* [plotly](https://plotly.com/r/getting-started/)
* [ggiraph](https://davidgohel.github.io/ggiraph/articles/offcran/using_ggiraph.html)

### saving plots
* [ggsave](http://www.sthda.com/english/wiki/ggsave-save-a-ggplot-r-software-and-data-visualization) - saving a ggplot
* [cairo](https://aebou.rbind.io/posts/2020/11/how-to-export-high-quality-images-in-r/) - using cairo package to save high quality images

### data visualization catalogues
* [the data visualization catalogue](https://datavizcatalogue.com/)
* [from data to viz](https://www.data-to-viz.com/)
* [data viz project](https://datavizproject.com/)
* [visualization universe](http://visualizationuniverse.com/charts/)
* [chart doctor](https://github.com/ft-interactive/chart-doctor/tree/master/visual-vocabulary)

## R markdown
* [R Markdown](https://rmarkdown.rstudio.com/index.html)
* [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)

****

## R tutorials
* [swirl](https://swirlstats.com/students.html) - learn R in R
* [Sara and Debbie's R tutorials](https://debyeeneuro.com/r-tutorials/)

***

## collection of online books
* [Cookbook for R](http://www.cookbook-r.com/Graphs/)
* [Data Visualization with R](https://rkabacoff.github.io/datavis/)
* [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/)
* [Getting Used to R, RStudio, and R Markdown](https://rbasics.netlify.app/index.html)
* [ggplot2: elegant graphics for data analysis](https://ggplot2-book.org/index.html)
* [Happy Git and GitHub for the useR](https://happygitwithr.com/)
* [Just Enough R](https://benwhalley.github.io/just-enough-r/)
* [Learning Statistics with R](https://learningstatisticswithr.com/)
* [ModernDive](https://moderndive.com/)
* [R for Data Science](https://r4ds.had.co.nz/)
* [R for Psychological Science](https://psyr.djnavarro.net/)
* [Text Mining with R: A Tidy Approach](https://www.tidytextmining.com/tidytext.html)
* [YaRrr! The Pirate’s Guide to R](https://ndphillips.github.io/piratesguide.html)
* [Handbook of Regression Modeling in People Analytics](http://peopleanalytics-regression-book.org/index.html)

***

## #TidyTuesday screencasts
* [David Robinson](https://www.youtube.com/user/safe4democracy/videos)
* [TidyX](https://www.youtube.com/c/TidyX_screencast/videos)

***

## R for psychological research
* [psych](http://personality-project.org/r/psych/) - descriptive and statistical analysis
* [lavaan](https://lavaan.ugent.be/start.html) - latent variable analysis (e.g., SEM)
* [lme4](https://github.com/lme4/lme4/) - mixed-effects models
* [GLM in R](https://rpsystats.com/)

***

## Datasets for practice
* [datasets package](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/00Index.html)
* [Rdatasets](https://vincentarelbundock.github.io/Rdatasets/articles/data.html)

***

## list of lists of useful R resources
* [RStudio's list](https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages)
* [Association for Psychological Science (APS) list](https://www.psychologicalscience.org/observer/learning-to-work-with-r)
* [CRAN Task Views list of packages](https://cran.r-project.org/web/views/) - lists packages on CRAN that are relevant for certain types of tasks
* [9 useful R data visualization packages list](https://mode.com/blog/r-data-visualization-packages/)
* [Top 50 ggplot2 visualizations list](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html)


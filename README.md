# R Basics for datasciencecoursera
# README.md

Working notes for the intro to Data Science through Coursera

> [The Data Scientist’s Toolbox](https://www.coursera.org/learn/data-scientists-tools)


# R Basics Guide

We will make working notes on using R throughout this project.

You can find helpful resources all over the web:

* [RStudio cheat sheets](https://www.rstudio.com/resources/cheatsheets/)
* [How to share data with a statistician](https://github.com/jtleek/datasharing)


# Console commands

**Install**
When installing packages make sure to check your exact spelling within commands. For example, the install option requires the plural 'install.packages()' but will not accept singluar 'install.package()'
```
install.packages('ggplot2')
install.packages(c('ggplot2','devtools','lme4'))
```

**Load**
```
library()
library(ggplot2)
```

**What packages are installed?**
```
installed.packages()
library
```

**Updating packages**
```
old.packages()
update.packages()
install.packages('packagename')
```

**Unload packages**
```
detach()
detach("package:ggplot2", unload=TRUE)
```

**Uninstall packages**
```
remove.packages()
remove.packages('ggplot2')
```

**Check current versions and copyrights**
```
version
sessionInfo()
library(packageName)
```

For example, running ```library(KernSmooth)``` gives us:
> KernSmooth 2.23 loaded
> Copyright M. P. Wand 1997-2009

**Help**
```
help()
help(package='ggplot2')
```

**Vignettes**
```
browseVignettes()
browseVignettes('ggplot2')
```
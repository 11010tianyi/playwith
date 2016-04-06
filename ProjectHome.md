This project has moved to github: https://github.com/floybix/playwith

**playwith** is an **[R](http://www.R-project.org/)** package, providing a GTK+ graphical user interface for editing and interacting with R plots.

The playwith package is maintained by Felix Andrews `<felix@nfrac.org>`

### Examples ###
  * [List of features](http://code.google.com/p/playwith/wiki/Features)
  * [Screenshots of playwith examples](http://code.google.com/p/playwith/wiki/Screenshots)
  * Demos of creating custom tools for playwith:
    * HelloTool A simple "Hello world" tool for playwith().
    * LineEqTool Draw a line and place its equation on the plot.
    * VarLinkTool Create a linked plot of covariates.
    * PointsTool A tool to add and remove points from a plot.
    * ClusterApp A mini application (a playwith toolbar) for clustering.

### Installation ###
  1. Make sure you have the GTK+ libraries, version 2.10.11 or later:
    * Windows: `RGtk2` will automatically install GTK+ on Windows if necessary. To get the latest version, download and install the _Gtk+/Win32 Runtime Environment_ from [here](http://gladewin32.sourceforge.net/) (~6MB).
    * GNU/Linux: GTK+ is usually included on desktop systems but may need to be updated.
    * MacOS: a GTK+ installer is available from [here](http://r.research.att.com/#other) (~25MB).
  1. Install the playwith package from CRAN:
> > `install.packages("playwith")`
  1. `library("playwith")` to load the package.

Type `help("playwith")` for details and examples.

### Troubleshooting ###

If you are using R on Windows you may find the playwith window disappears behind the "RGui" window. To avoid that, set RGui to run in "SDI" mode via _Edit_ > _GUI preferences_; or just minimise the RGui window.

### Other ###

[NEWS (from the development version)](http://code.google.com/p/playwith/source/browse/trunk/inst/NEWS)
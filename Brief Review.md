# Review of Various Plot Packages  


## Gadfly  
**Website**: http://gadflyjl.org/  
**Github**: https://github.com/dcjones/Gadfly.jl  
**Main Contributors**: Daniel C. Jones  
**Active Period**: Sep 2, 2012 – Current  
**Introduction**: Implemented in Julia. Inspired by the book *the Grammar of Graphics* and R package ggplot2.  
**Code Example**: `plot(x=rand(10), y=rand(10), Geom.point, Geom.line)`  
  
  
## PyPlot  
**Github**: https://github.com/stevengj/PyPlot.jl  
**Main Contributors**: Steven G. Johnson  
**Active Period**: Nov 18, 2012 – Current  
**Introduction**: Interface to the Python package Matplotlib.  
**Uses Julia** package PyCall to call it.  
  
  
## Winston  
Website: http://winston.readthedocs.org/en/latest/  
**Github**: https://github.com/nolta/Winston.jl  
**Main Contributors**: Mike Nolta  
**Active Period**: Feb 26, 2012 – Current  
**Introduction**: 2D Plotting for Julia and written in Julia.  
**Code Example**: `plot(x, y, "b:", x2, y2, "g^")`  
  
  
## Gaston  
**Github**: https://github.com/mbaz/Gaston.jl  
**Main Contributors**: mbaz  
**Active Period**: Mar 25, 2012 – Jul 1, 2015  
**Introduction**: Interface to Gnuplot.  
**Code Example**: `plot({h,} {x,} y {, property, value...} {...})`  
  
  
## julia-plot  
**Github**: https://github.com/Mononofu/julia-plot  
**Main Contributors**: Julian Schrittwieser  
**Active Period**: Feb 19, 2012 – Feb 28, 2012  
**Introduction**: Interface to MathGL.  
**Code Example**: `plot(x -> sin(x), -4, 4, "sample.png")`  
  
  
  
## GLPlot & GLVisualize  
**Website**: https://github.com/SimonDanisch/GLPlot.jl/wiki  
**Github**: https://github.com/SimonDanisch/GLPlot.jl  
**Main Contributors**: Simon Danisch  
**Active Period**: May 11, 2014 – Current  
**Introduction**: Interface to OpenGL  
**Code Example**: `glplot(b)`  
  
  
  
## Qwt  
**Github**: https://github.com/tbreloff/Qwt.jl  
**Main Contributors**: Tom Breloff  
**Active Period**: May 24, 2015 – Current  
**Introduction**: Interface to Python’s interface to Qwt. Qwt is a plotting widget of Qt.  
**Code Example**: `plot(Y[:,1:2], axiss=[:left, :right], colors=[blue, :green])`  
  
  
  
## Bokeh  
**Website**: http://bokeh.github.io/Bokeh.jl/  
**Github**: https://github.com/bokeh/Bokeh.jl  
**Main Contributors**: Samuel Colvin  
**Active Period**: Jun 8, 2014 – Mai 28, 2015  
**Introduction**: Interface to Python Package Bokeh.  
**Code Example**: `plot(x, [y1 y2 y3], "rs|bo|g*")`  
  
  
  
## Plotly  
**Website**: https://plot.ly/julia/  
**Github**: https://github.com/plotly/Plotly.jl  
**Main Contributors**: Plotly team ?  
**Active Period**: Aug 11, 2013 – Apr 1, 2015  
**Introduction**: A commercial web based plotting service  
**Code Example**: `Plotly.plot(data, ["filename" => "date-xes", "fileopt" => "overwrite"])`  
  
  
  
## GoogleCharts  
**Website**: http://code.google.com/apis/chart/  
**Github**: https://github.com/jverzani/GoogleCharts.jl  
**Main Contributors**: john verzani  
**Active Period**: Mar 24, 2013 – Jan 18, 2015  
**Introduction**: Interface to Google Chart Tools  
**Code Example**: `chart = scatter_chart(scatter_data, options);render(chart)`  
  
  
  
## Vega  
**Website**: https://trifacta.github.io/vega/  
**Github**: https://github.com/johnmyleswhite/Vega.jl  
**Main Contributors**: Randy Zwitch  
**Active Period**: Jun 23, 2013 – Current  
**Introduction**: Interface to Vega.  
  
  
  
##PLplot  
**Website**: http://plplot.sourceforge.net/  
**Github**: https://github.com/wildart/PLplot.jl  
**Main Contributors**: Art  
**Active Period**: Aug 16, 2015 – Current  
**Introduction**: Interface to PLplot  
**Code Example**: `plot(:xwin, rand(10), pch='⋄', typ=:overlay)`  


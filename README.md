# GAUSS Plot Library

![Wage Data Plots](images/wage_data_plot.jpeg)

## What is GAUSS?
GAUSS is an easy-to-use data analysis, mathematical and statistical environment based on the powerful, fast and efficient GAUSS Matrix Programming Language. GAUSS is a complete analysis environment with the built-in tools you need for estimation, forecasting, simulation, visualization and more.

## What is the GAUSS plot library?
The [**GAUSS**](www.aptech.com) plot library focuses on the graphic functionality of [**GAUSS**](www.aptech.com). It provides example images of plots created in [**GAUSS**](www.aptech.com) along with the [**GAUSS**](www.aptech.com) code used to create the plots. Together these tools demonstrate how to create and format a variety of types of graphs in [**GAUSS**](www.aptech.com). This library illustrates both fundamental graphing features as well as advanced plotting features in [**GAUSS**](www.aptech.com), such as color schemes, graph annotation, and canvas sizing.
![GAUSS](images/polar_rose.jpg?raw=true)

## Structure of repository
Images and descriptions of graph examples are stored in the "doc" directory as .md files. These files contain links to the GAUSS program files that are used to create the graphs. The program files are stored as .gss files in the "src" directory. The naming structure is consistent between the .md files and the .gss files. For example, the code for creating the graph illustrated in the file ["doc/bar_add_error_bars.md"](docs/bar_add_error_bars.md) is found in file  ["src/bar_add_error_bars.gss"](src/bar_add_error_bars.gss).

## Getting Started
### Prerequisites
The program files require a working copy of [**GAUSS 24+**](www.aptech.com). Many can be run on earlier versions with some small revisions.

### Installing
1. Images and descriptions of graph examples are stored in the "doc" directory as .md files. These files contain links to the [**GAUSS**](www.aptech.com) program files that are used to create the graphs.
2. The program files are stored as .gss files in the "src" directory. The naming structure is consistent between the .md files and the .gss files. For example, the code for creating the graph illustrated in the file "doc/bar_add_error_bars.md" is found in file "src/bar_add_error_bars.gss".
3. If the program file contains data it is stored in the "data" directory.
4. These program files and their associated data files can be downloaded directly into the examples directory in the **GAUSS** home directory.

## Coverage
|Graph|Image|
|:----|:----|
|[Stock portfolio area plot](docs/area_plot_stocks.md)|![GAUSS area plot](images/area_stock_portfolio.jpeg)|
|[Bar graph with error bars](docs/bar_add_error_bars.md)|![GAUSS bar graph with error bars](images/bar_add_error_bars_default.jpg)|
|[Histogram with added line plot](docs/histogram_line_plot.md)|![GAUSS histogram plot](images/histogram_line_plot_default.jpg)|
|[Log X-axis with Inset Plot](docs/logx_with_inset.md)|![GAUSS logX graph](images/logx_with_inset.jpeg)|
|[Log Y-axis with Inset Plot](docs/logy_with_inset.md)|![GAUSS logY graph](images/logy_with_inset.jpeg)|
|[Horizontally plotted odds ratios](docs/odds_ratio_horizontal.md)|![GAUSS horizontal odds ratio](images/odds_ratio_horizontal.jpeg)|
|[Polar rose plot](docs/polar_rose.md)|![GAUSS polar rose](images/polar_rose.jpg)|
|[Scatter plot with a trend line](docs/scatter_trend_line_plot.md)|![GAUSS polar rose](images/scatter_trend_line_default.jpg)|
|[Annotated time series plot](docs/time_series_annotated.md)|![GAUSS annotated time series](images/time_series_annotated.png)|
|[XY plot with added error bars](docs/xy_add_error_bars.md)|![GAUSS annotated time series](images/xy_add_error_bars_default.jpeg)|
|[XY plot with LaTex labels](docs/xy_latex.md)|![GAUSS XY plot with LaTex labels](images/xy_latex_default.jpeg)|
|[Grid scatter plot](docs/grid-plot-adjusted-canvas.md)|![GAUSS grid scatter plot](images/grid-plot-adjusted-canvas.jpeg)|
|[Annotated histogram](docs/annotated-bootstrap.md)|![GAUSS annotated histogram plot](images/annotated-bootstrap.jpeg)|

## Related Readings
More information about creating and editing GAUSS plots can be found on the [GAUSS Data Analytics blog](https://www.aptech.com/blog/).
1. [Introduction to Efficient Creation of Detailed Plots](https://www.aptech.com/blog/introduction-to-efficient-creation-of-detailed-plots/)
2. [Advanced Formatting Techniques for Creating AER Quality Plots](https://www.aptech.com/blog/advanced-formatting-techniques-for-creating-aer-quality-plots/)
3. [Visualizing COVID-19 Panel Data With GAUSS 22](https://www.aptech.com/blog/visualizing-covid-19-panel-data-with-gauss-22/) 
4. [How to Create Tiled Graphs in GAUSS](https://www.aptech.com/blog/how-to-create-tiled-graphs-in-gauss/)
5. [How to Interactively Create Reusable Graphics Profiles](https://www.aptech.com/blog/how-to-interactively-create-reusable-graphics-profiles/) 
6. [How to Mix, Match and Style Different Graph Types](https://www.aptech.com/blog/how-to-mix-match-and-style-different-graph-types/)
7. [Five Hacks For Creating Custom GAUSS Graphics](https://www.aptech.com/blog/five-hacks-for-creating-custom-gauss-graphics/) 
8. [Graph High Frequency Forex Data](https://www.aptech.com/blog/graph-high-frequency-forex-data/)    
    
    
## Authors
[Eric Clower](mailto:eric@aptech.com)  
[Aptech Systems, Inc](https://www.aptech.com/)  
[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]

<!-- links to social media icons -->
[1.1]: https://www.aptech.com/wp-content/uploads/2019/02/fb.png (Visit Aptech Facebook)
[2.1]: https://www.aptech.com/wp-content/uploads/2019/02/gh.png (Aptech Github)
[3.1]: https://www.aptech.com/wp-content/uploads/2019/02/li.png (Find us on LinkedIn)

<!-- links to your social media accounts -->
[1]: https://www.facebook.com/GAUSSAptech/
[2]: https://github.com/aptech
[3]: https://linkedin.com/in/ericaclower
<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

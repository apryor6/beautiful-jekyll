## Gallery (Under Construction)
Below is a collection of data visualizations. Each final image below links to the markdown output of a Jupyter notebook with the code required to make that image as well as exploration of other adjustable parameters for that type of plot. Each notebook is designed to explore mainly the parameters that are specific to that type of plot in the corresponding library in order to avoid repetition (e.g. adjusting labels or titles is usually the same for all types of plots within a library), and at the very end extra modifications are made to make the final result look nice.

### Table of contents 
- [**Seaborn**](#seaborn)  
&nbsp;&nbsp;&nbsp;&nbsp; - [Scatter/Line plot](#seaborn-lmplot)  
&nbsp;&nbsp;&nbsp;&nbsp; - [Bar plot](#seaborn-barplot)   
&nbsp;&nbsp;&nbsp;&nbsp; - [Strip plot](#seaborn-stripplot)   
&nbsp;&nbsp;&nbsp;&nbsp; - [Count plot](#seaborn-countplot)   
&nbsp;&nbsp;&nbsp;&nbsp; - [Box plot](#seaborn-boxplot)   
&nbsp;&nbsp;&nbsp;&nbsp; - [Violin plot](#seaborn-violinplot)   
&nbsp;&nbsp;&nbsp;&nbsp; - [Joint plot](#seaborn-jointplot)   
&nbsp;&nbsp;&nbsp;&nbsp; - [Heat map](#seaborn-heatmap)  
- [**Plotly**](#plotly)  
&nbsp;&nbsp;&nbsp;&nbsp; - [Line plot](#plotly-line)  
- [**Bokeh**](#bokeh)  
&nbsp;&nbsp;&nbsp;&nbsp; - [Glyphs](#bokeh-glyphs)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Annular Wedge](#bokeh-glyphs-annular_wedge)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Annulus](#bokeh-glyphs-annulus)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Arc](#bokeh-glyphs-arc)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Asterisk](#bokeh-glyphs-asterisk)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Bezier](#bokeh-glyphs-bezier)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Circle](#bokeh-glyphs-circle)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Circle Cross](#bokeh-glyphs-circle_cross)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Circle X](#bokeh-glyphs-circle_x)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Cross](#bokeh-glyphs-cross)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Diamond](#bokeh-glyphs-diamond)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Diamond Cross](#bokeh-glyphs-diamond_cross)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Ellipse](#bokeh-glyphs-ellipse)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Hbar](#bokeh-glyphs-hbar)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Image](#bokeh-glyphs-image)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Image RGBA](#bokeh-glyphs-image_rgba)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Image URL](#bokeh-glyphs-image_url)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Inverted Triangle](#bokeh-glyphs-inverted_triangle)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Line](#bokeh-glyphs-line)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Oval](#bokeh-glyphs-oval)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Patch](#bokeh-glyphs-patch)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Patches](#bokeh-glyphs-patches)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Quad](#bokeh-glyphs-quad)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Quadratic](#bokeh-glyphs-quadratic)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Ray](#bokeh-glyphs-ray)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Segment](#bokeh-glyphs-segment)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Square](#bokeh-glyphs-square)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Square Cross](#bokeh-glyphs-square_cross)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Square X](#bokeh-glyphs-square_x)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Text](#bokeh-glyphs-text)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Triangle](#bokeh-glyphs-triangle)   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Vbar](#bokeh-glyphs-vbar)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [Wedge](#bokeh-glyphs-wedge)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - [X](#bokeh-glyphs-x)  


<a name="seaborn"></a>
## Seaborn
<a name="seaborn-lmplot"></a>
[![png](visualizations/figures/lmplot.png)](../visualizations/seaborn/lmplot/lmplot)
<a name="seaborn-barplot"></a>
[![png](visualizations/figures/barplot.png)](../visualizations/seaborn/barplot/barplot)
<a name="seaborn-stripplot"></a>
[![png](visualizations/figures/stripplot.png)](../visualizations/seaborn/stripplot/stripplot)
<a name="seaborn-countplot"></a>
[![png](visualizations/figures/countplot.png)](../visualizations/seaborn/countplot/countplot)
<a name="seaborn-boxplot"></a>
[![png](visualizations/figures/boxplot.png)](../visualizations/seaborn/boxplot/boxplot)
<a name="seaborn-violinplot"></a>
[![png](visualizations/figures/violinplot.png)](../visualizations/seaborn/violinplot/violinplot)
<a name="seaborn-jointplot"></a>
[![png](visualizations/figures/jointplot.png)](../visualizations/seaborn/jointplot/jointplot)
<a name="seaborn-heatmap"></a>
[![png](visualizations/figures/heatmap.png)](../visualizations/seaborn/heatmap/heatmap)

<a name="plotly"></a>
## Plotly

<a name="plotly-line"></a>



<a name="bokeh"></a>
## Bokeh

#### Glyphs
Glyphs are the fundamental building block of plots in `Bokeh`.


<a name="bokeh-glyphs-annular_wedge"></a>
#### Annular Wedge ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/annular_wedge)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/annular_wedge/annular_wedge)
![Annular Wedge](../visualizations/bokeh/figures/annular_wedge.png)



<a name="bokeh-glyphs-annulus"></a>
#### Annulus ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/annulus)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/annulus/annulus)
![Annulus](../visualizations/bokeh/figures/annulus.png)



<a name="bokeh-glyphs-arc"></a>
#### Arc ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/arc)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/arc/arc)
![Arc](../visualizations/bokeh/figures/arc.png)



<a name="bokeh-glyphs-asterisk"></a>
#### Asterisk ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/asterisk)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/asterisk/asterisk)
![Asterisk](../visualizations/bokeh/figures/asterisk.png)



<a name="bokeh-glyphs-bezier"></a>
#### Bezier ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/bezier)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/bezier/bezier)
![Bezier](../visualizations/bokeh/figures/bezier.png)



<a name="bokeh-glyphs-circle"></a>
#### Circle ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/circle)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/circle/circle)
![Circle](../visualizations/bokeh/figures/circle.png)



<a name="bokeh-glyphs-circle_cross"></a>
#### Circle Cross ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/circle_cross)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/circle_cross/circle_cross)
![Circle Cross](../visualizations/bokeh/figures/circle_cross.png)



<a name="bokeh-glyphs-circle_x"></a>
#### Circle X ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/circle_x)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/circle_x/circle_x)
![Circle X](../visualizations/bokeh/figures/circle_x.png)



<a name="bokeh-glyphs-cross"></a>
#### Cross ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/cross)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/cross/cross)
![Cross](../visualizations/bokeh/figures/cross.png)



<a name="bokeh-glyphs-diamond"></a>
#### Diamond ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/diamond)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/diamond/diamond)
![Diamond](../visualizations/bokeh/figures/diamond.png)



<a name="bokeh-glyphs-diamond_cross"></a>
#### Diamond Cross ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/diamond_cross)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/diamond_cross/diamond_cross)
![Diamond Cross](../visualizations/bokeh/figures/diamond_cross.png)



<a name="bokeh-glyphs-ellipse"></a>
#### Ellipse ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/ellipse)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/ellipse/ellipse)
![Ellipse](../visualizations/bokeh/figures/ellipse.png)



<a name="bokeh-glyphs-hbar"></a>
#### Hbar ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/hbar)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/hbar/hbar)
![Hbar](../visualizations/bokeh/figures/hbar.png)



<a name="bokeh-glyphs-image"></a>
#### Image ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/image)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/image/image)
![Image](../visualizations/bokeh/figures/image.png)



<a name="bokeh-glyphs-image_rgba"></a>
#### Image Rgba ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/image_rgba)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/image_rgba/image_rgba)
![Image Rgba](../visualizations/bokeh/figures/image_rgba.png)



<a name="bokeh-glyphs-image_url"></a>
#### Image Url ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/image_url)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/image_url/image_url)
![Image Url](../visualizations/bokeh/figures/image_url.png)



<a name="bokeh-glyphs-inverted_triangle"></a>
#### Inverted Triangle ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/inverted_triangle)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/inverted_triangle/inverted_triangle)
![Inverted Triangle](../visualizations/bokeh/figures/inverted_triangle.png)



<a name="bokeh-glyphs-line"></a>
#### Line ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/line)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/line/line)
![Line](../visualizations/bokeh/figures/line.png)



<a name="bokeh-glyphs-oval"></a>
#### Oval ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/oval)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/oval/oval)
![Oval](../visualizations/bokeh/figures/oval.png)



<a name="bokeh-glyphs-patch"></a>
#### Patch ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/patch)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/patch/patch)
![Patch](../visualizations/bokeh/figures/patch.png)



<a name="bokeh-glyphs-patches"></a>
#### Patches ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/patches)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/patches/patches)
![Patches](../visualizations/bokeh/figures/patches.png)



<a name="bokeh-glyphs-quad"></a>
#### Quad ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/quad)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/quad/quad)
![Quad](../visualizations/bokeh/figures/quad.png)



<a name="bokeh-glyphs-quadratic"></a>
#### Quadratic ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/quadratic)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/quadratic/quadratic)
![Quadratic](../visualizations/bokeh/figures/quadratic.png)



<a name="bokeh-glyphs-ray"></a>
#### Ray ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/ray)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/ray/ray)
![Ray](../visualizations/bokeh/figures/ray.png)



<a name="bokeh-glyphs-segment"></a>
#### Segment ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/segment)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/segment/segment)
![Segment](../visualizations/bokeh/figures/segment.png)



<a name="bokeh-glyphs-square"></a>
#### Square ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/square)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/square/square)
![Square](../visualizations/bokeh/figures/square.png)



<a name="bokeh-glyphs-square_cross"></a>
#### Square Cross ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/square_cross)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/square_cross/square_cross)
![Square Cross](../visualizations/bokeh/figures/square_cross.png)



<a name="bokeh-glyphs-square_x"></a>
#### Square X ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/square_x)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/square_x/square_x)
![Square X](../visualizations/bokeh/figures/square_x.png)



<a name="bokeh-glyphs-text"></a>
#### Text ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/text)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/text/text)
![Text](../visualizations/bokeh/figures/text.png)



<a name="bokeh-glyphs-triangle"></a>
#### Triangle ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/triangle)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/triangle/triangle)
![Triangle](../visualizations/bokeh/figures/triangle.png)



<a name="bokeh-glyphs-vbar"></a>
#### Vbar ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/vbar)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/vbar/vbar)
![Vbar](../visualizations/bokeh/figures/vbar.png)



<a name="bokeh-glyphs-wedge"></a>
#### Wedge ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/wedge)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/wedge/wedge)
![Wedge](../visualizations/bokeh/figures/wedge.png)



<a name="bokeh-glyphs-x"></a>
#### X ([Interactive](http://alanpryorjr.com/visualizations/bokeh/figures/x)) [(code)](http://alanpryorjr.com/visualizations/bokeh/glyphs/x/x)
![X](../visualizations/bokeh/figures/x.png)


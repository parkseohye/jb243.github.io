higher category**:** 【Statistics】 [Statistics Overview](https://classroom.tistory.com/32) 

Kim, S.K., Park, J.B. (2022); [originally written in Korean](https://nate9389.tistory.com/1192)  

---

**1**. introduction 

**2\.** basic statistical terminology

**3\.** definition of data  

**4.** visualization of data   

---

**a.** [Quantile-Quantile Plot](https://classroom.tistory.com/54) 

---

<br>

## **1\. introduction** 

　　⑴ probability and Statistics

　　　　① probability **:** a mathematical and theoretical study of possibilities

　　　　② Statistics **:** the study of collecting, analyzing, interpreting, or expressing data

　　　　　　○ probability and statistics are similar but clearly different

　　　　③ descriptive Statistics **:** statistical technique that summarizes and describes data

　　　　④ inference Statistics **:** statistical techniques that calculate the probability of a value occurring beyond the summary of numbers

　⑵ the meaning of probability

　　　　① Frequentist

　　　　　　○ claims that probability is an intrinsic attribute of an object

　　　　　　○ example**:** a coin is an object that has a half probability at the front and the back

　　　　② Bayesianist 

　　　　　　○ claims that probability is nothing but human belief

　　　　　　○ example**:** investigating the frequency of the front and back of a coin does not really prove that each frequency is one-half

　　⑶ trends in Statistics

　　　　① major issues in classical Statistics**:** finding distribution, increasing power

　　　　② major issues in modern Statistics**:** big data, machine learning

<br>
<br>

## **2\. basic statistical terminology** 

　　⑴ average (mean)

　　⑵ most frequent number (mode)

　　⑶ central value (median)

　　　　① the value in the middle in order**:** both sides should be equal in width relative to the median in the probability distribution

　　　　② less sensitive to changes in distribution than average

　　　　　　[##_Image|kage@bvT77T/btrtDE1UoJv/Y6VA4qsN61SFdAkHIKK6Q1/img.jpg|CDM|1.3|{"originWidth":462,"originHeight":355,"style":"alignCenter","width":462,"height":355}_##]

　　　　　　**Figure 1.** mean (left) and median (right)[\]](https://papago.naver.net/apis/site/proxy?url=https%3A%2F%2Fnate9389.tistory.com%2F%2F1192#footnote_1192_1)

　　　　　　○ only change at the right-hand part of the median changes cannot change median value

　　　　　　○ thus, the median value is less sensitive 

　　　　　　○ unexpectedly, many people do not know

<br>
<br>

## **3\. definition of data**

&emsp;⑴ data, information, and knowledge

&emsp;&emsp;① data**:** given data

&emsp;&emsp;② information**:** Name of the data

&emsp;&emsp;③ knowledge**:** The relationship between information and information

&emsp;⑵ types of datasets

&emsp;&emsp;① relation

&emsp;&emsp;② tree

&emsp;&emsp;③ network

&emsp;⑶ type of attribute

&emsp;&emsp;① **class 1.** continuous type data**:** quantitative data 

&emsp;&emsp;&emsp;○ **1-1**. ratio scale (ratio scale)**:** **1st-ranked scale**

&emsp;&emsp;&emsp;&emsp;○ absolute zero + same interval + rank + category

&emsp;&emsp;&emsp;&emsp;○ concept of ratio between scales can be established

&emsp;&emsp;&emsp;&emsp;○ absolute zero exists**:** no negative concept

&emsp;&emsp;&emsp;&emsp;○ example**:** absolute temperature

&emsp;&emsp;&emsp;○ **1-2.** interval scale (interval scale)**:** **second-order scale**

&emsp;&emsp;&emsp;&emsp;○ same interval + rank + category

&emsp;&emsp;&emsp;&emsp;○ the concept of ratio between scales cannot be established

&emsp;&emsp;&emsp;&emsp;○ no absolute zero**:** negative concept exists

&emsp;&emsp;&emsp;&emsp;○ example**:** Celsius temperature, Fahrenheit temperature

&emsp;&emsp;② **class 2.** categorical data**:** qualitative data

&emsp;&emsp;&emsp;○ **2-1.** ordinal scale

&emsp;&emsp;&emsp;&emsp;○ rank + category

&emsp;&emsp;&emsp;&emsp;○ the intervals cannot be said to be equal to each other**:** quantification and averaging are impossible

&emsp;&emsp;&emsp;&emsp;○ example**:** 2 students in 3rd grade and 2 students in 1st grade cannot be considered as 2 students in 2nd grade on average

&emsp;&emsp;&emsp;○ **2-2.** nominal scale (categorical scale)

&emsp;&emsp;&emsp;&emsp;○ category**:** same as name for each material

&emsp;&emsp;&emsp;&emsp;○ example**:** gender, blood type

&emsp;⑷ attribute semantics

&emsp;&emsp;① spatial**:** quantitative 

&emsp;&emsp;② temporal**:** quantitative

&emsp;&emsp;③ sequential**:** ordinal

&emsp;&emsp;④ diverging**:** quantitative

&emsp;&emsp;⑤ cyclic**:** categorical, ordinal, quantitative

&emsp;&emsp;⑥ hierarchical**:** categorical 

<br>
<br>


## **4\. visualization of data**

&emsp;⑴ classification of analysis

&emsp;&emsp;① **frequency** **analysis****:** An analysis that identifies the characteristics of a distribution for one categorical variable

&emsp;&emsp;② **cross analysis****:** an analysis that identifies the characteristics of the combination distribution for two or more categorical variables. it is able to analyze independence and relevance

&emsp;⑵ advantageous forms of expression according to data types**:** the more advantageous the data type is at higher

&emsp;&emsp;① quantitative variable

&emsp;&emsp;&emsp;○ position

&emsp;&emsp;&emsp;○ length 

&emsp;&emsp;&emsp;○ angle

&emsp;&emsp;&emsp;○ slope

&emsp;&emsp;&emsp;○ area

&emsp;&emsp;&emsp;○ volume

&emsp;&emsp;&emsp;○ density

&emsp;&emsp;&emsp;○ color saturation 

&emsp;&emsp;&emsp;○ color hue

&emsp;&emsp;&emsp;○ texture

&emsp;&emsp;&emsp;○ connection

&emsp;&emsp;&emsp;○ containment

&emsp;&emsp;&emsp;○ shape 

&emsp;&emsp;② ordinal variable 

&emsp;&emsp;&emsp;○ position 

&emsp;&emsp;&emsp;○ density

&emsp;&emsp;&emsp;○ color saturation 

&emsp;&emsp;&emsp;○ color hue 

&emsp;&emsp;&emsp;○ texture 

&emsp;&emsp;&emsp;○ connection

&emsp;&emsp;&emsp;○ containment 

&emsp;&emsp;&emsp;○ length 

&emsp;&emsp;&emsp;○ angle 

&emsp;&emsp;&emsp;○ slope 

&emsp;&emsp;&emsp;○ area 

&emsp;&emsp;&emsp;○ volume 

&emsp;&emsp;&emsp;○ shape

&emsp;&emsp;③ nominal variable

&emsp;&emsp;&emsp;○ position 

&emsp;&emsp;&emsp;○ color hue 

&emsp;&emsp;&emsp;○ texture 

&emsp;&emsp;&emsp;○ connection 

&emsp;&emsp;&emsp;○ containment 

&emsp;&emsp;&emsp;○ density 

&emsp;&emsp;&emsp;○ color saturation 

&emsp;&emsp;&emsp;○ shape 

&emsp;&emsp;&emsp;○ length 

&emsp;&emsp;&emsp;○ angle 

&emsp;&emsp;&emsp;○ slope 

&emsp;&emsp;&emsp;○ area 

&emsp;&emsp;&emsp;○ volume 

&emsp;⑶ **class 1.** representation of two-dimensional information

&emsp;&emsp;① bar chart**:** categorical / ordinal (1D) + quantitative (1D)

&emsp;&emsp;&emsp;○ when categorical / oridnal variable is on the x-axis**:** long labeling is possible

&emsp;&emsp;&emsp;○ when categorical / oridnal variable is on the y-axis**:** it is possible to increase the number of variables

&emsp;&emsp;② line chart**:** ordinal / quantitative (1D) + quantitative (1D)

&emsp;&emsp;③ scatter plot**:** quantitative (1D) + quantitative (1D)

&emsp;&emsp;④ slope chart**:** quantitative (1D) + quantitative (1D). an alternative for scatter plot

&emsp;&emsp;⑤ histogram 

&emsp;&emsp;⑥ pie chart 

&emsp;&emsp;⑦ box plot 

&emsp;&emsp;⑧ stem and leaf figures

&emsp;⑷ **class 2.** representation of three dimensional information

&emsp;&emsp;① matrix**:** categorical / ordinal (1D) + categorical / ordinal (1D) + quantitative (1D, color) (+ quantitative (1D, point size))

&emsp;&emsp;② extended barchart**:** stacked bar chart, grouped bar chart, etc 

&emsp;&emsp;③ extended line chart**:** area chart (≒ stacked line chart), etc

&emsp;&emsp;④ extended scatter plot**:** bubble chart (cf. point size also can be a variable), etc

&emsp;&emsp;⑤ symbol map**:** spatial (2D) + quantitative (1D)

&emsp;⑸ **class 3.** representation of multidimensional information

&emsp;&emsp;① faceting**:** expressing two or three dimensional information for each parameter. multiple types of graphs are produced

&emsp;&emsp;② Chernoff face 

&emsp;&emsp;③ star plot**:** also called as spider plot, radar chart, cobweb chart, or polar chart

&emsp;⑹ **1-1.** bar chart (bar graph)

&emsp;&emsp;① definition**:** a graph of nominal scale data

&emsp;&emsp;② generally, there is a gap between bars

&emsp;&emsp;③ R programming 

<center>
```
plot(c(1, 2, 3), c(4, 5, 6), main = "BASIC PLOT")
```
</center>

&emsp;&emsp;④ Python programming**:** Bokeh is used for web-page visualization

<center>
**Figure. 2.** bar chart represented by Bokeh 
</center>

<center>
```
from bokeh.plotting import figure, output_file, show

output_file("stacked_bar.html")
graph = figure(width = 400, height = 400, title = "Bokeh Vertical Bar Graph", 
               tooltips=[("x", "$x"), ("y", "$y")] )
x = [1, 2, 3, 4, 5]
top = [1, 2, 3, 4, 5]
width = 0.5
graph.vbar(x, top = top, width = width)
show(graph)
```
</center>

&emsp;⑺ **1-2.** line chart

&emsp;&emsp;① Python programming**:** Bokeh is used for web-page visualization

<center>
**Figure. 3.** line chart represented by Bokeh
</center>

<center>
```
from bokeh.plotting import figure, output_file, show

output_file("line_chart.html")
p = figure(width=400, height=400, title = "Line Chart", 
           tooltips=[("x", "$x"), ("y", "$y")])
p.line([1, 2, 3, 4, 5], [6, 7, 2, 4, 5], line_width=2)
show(p)
```
</center>

&emsp;⑻ **1-3.** scatter plot

&emsp;&emsp;① definition

&emsp;&emsp;② scatter plot with marginal histogram 

&emsp;&emsp;③ Python programming**:** Bokeh is used for web-page visualization

<center>**Figure. 4.** scatter plot represented by Bokeh</center>

<center>
```
from bokeh.plotting import figure, output_file, show

output_file("scatter_plot.html")
p = figure(width=400, height=400, title = "Scatter Plot",
           tooltips=[("x", "$x"), ("y", "$y")])
p.circle([1, 2, 3, 4, 5], [6, 7, 2, 4, 5], size=20, color="navy", alpha=0.5)
show(p)
```
</center>

&emsp;⑼ **1-4.** histogram

&emsp;&emsp;① definition**:** determination of intervals for continuous data of ratio scale, interval scale and graphically expression

&emsp;&emsp;② generally no gap between bars

&emsp;&emsp;③ 3D Histogram

&emsp;&emsp;④ R programming

<center>
```
hist(c(1, 2, 2, 3, 3, 3), col = "light yellow")
```
</center>

&emsp;⑽ **1-5.** circle graph (pie chart)

&emsp;&emsp;① definition**:** a circular graph of continuous/discontinuous data on the ratio scale expressed in percent.

&emsp;&emsp;② R programming

<center>
```
pie(c(1, 2, 2, 3, 3, 3), label = c("a", "b", "c", "d", "e", "f"), main = "PIE CHART")
```
</center>

&emsp;⑾ **1-6.** box chart (whisker plot)

&emsp;&emsp;① quantile

&emsp;&emsp;&emsp;○ **quantile function****:** Inverse function of cumulative distribution function

&emsp;&emsp;&emsp;○ definitions**:**｛x 0 ≤ x ≤ 1｝

&emsp;&emsp;&emsp;○ range**:** Statistics of the group of interest

&emsp;&emsp;&emsp;○ depending on the number of sections, there are percentages, quartiles, etc.

&emsp;&emsp;② from the below lower bound, 1st quartile, median, 3th quartile, and upper bound are represented

&emsp;&emsp;&emsp;○ The average may noted, or otherwise may not

&emsp;&emsp;③ R programming

<center>
```
boxplot(c(1, 2, 2, 3, 3, 3))
```
</center>

&emsp;&emsp;④ example

<center>
**Figure. 5.** an example of box graph**:** the answer is ①
</center>

&emsp;⑿ **1-7.** stem and leaf

<center>
**Figure. 6.** stem and leaf 
</center>

&emsp;&emsp;① stems indicate tens place. leaves indicate ones place

&emsp;&emsp;② the numbers in parentheses refer the frequency of stems

&emsp;⒀ **1-8.** [quantile-quantile plot](https://classroom.tistory.com/54) 

&emsp;⒁ **2-1.** stacked bar chart

&emsp;&emsp;① Python programming**:** Bokeh is used for web-page visualization

<center>
**Figure. 7.** stacked bar chart represented by Bokeh
</center>

<center>
```
from bokeh.plotting import figure, output_file, show

output_file("hbar_stack.html")
p = figure(width=400, height=400, title = "Horizontal Stacked Bar Chart",
           tooltips=[("x", "$x"), ("y", "$y")])
source = ColumnDataSource(data=dict(
    y=[1, 2, 3, 4, 5],
    x1=[1, 2, 4, 3, 4],
    x2=[1, 4, 2, 2, 3],
))
p.hbar_stack(['x1', 'x2'], y='y', height=0.8, color=("grey", "lightgrey"), source=source)
show(p)
```
</center>

&emsp;⒂ **2-2.** area chart

&emsp;&emsp;① Python programming**:** Bokeh is used for web-page visualization

<center>
**Figure. 8.** area chart represented by Bokeh
</center>

<center>
```
import numpy as np

from bokeh.models import ColumnDataSource
from bokeh.plotting import figure, output_file, show

output_file("varea_stack.html")

source = ColumnDataSource(data=dict(
    x=[1, 2, 3, 4, 5],
    y1=[1, 2, 4, 3, 4],
    y2=[1, 4, 2, 2, 3],
))

p = figure(width=400, height=400, title = "Area Chart",
           tooltips=[("x", "$x"), ("y", "$y")])
p.varea_stack(['y1', 'y2'], x='x', color=("grey", "lightgrey"), source=source)
show(p)
```
</center>

&emsp;⒃ **2-3.** symbol map

&emsp;&emsp;① Python programming**:** Bokeh is used for web-page visualization

<center>
**Figure. 9.** symbol map represented by Bokeh
</center>

<center>
```
import numpy as np

from bokeh.io import output_file, show
from bokeh.plotting import figure
from bokeh.transform import linear_cmap
from bokeh.util.hex import hexbin

output_file("hex_tile.html")

n = 50000
x = np.random.standard_normal(n)
y = np.random.standard_normal(n)
bins = hexbin(x, y, 0.1)

p = figure(width=400, height=400, title = "Symbol Map", 
           match_aspect=True, background_fill_color='#440154',
           tooltips=[("x", "$x"), ("y", "$y")])
p.grid.visible = False

p.hex_tile(q="q", r="r", size=0.1, line_color=None, source=bins,
           fill_color=linear_cmap('counts', 'Viridis256', 0, max(bins.counts)))
show(p)
```
</center>
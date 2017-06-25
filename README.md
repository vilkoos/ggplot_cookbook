

### <FONT color='red'> *This is a work in progress, all is in flux*</FONT>

# ggplot cookbook [<font size="3" color="blue">(_toc_)</font>](./cookbook/000_toc.ipynb)

This cookbook is about data visualization with ggplot in Python (Grammar Graphics Plotting).  

The Grammar of Graphics is an abstract model of:
- what semantic elements a plot can have (points, lines, scales, title etc.)
- how to build a plot layer by combining these elements
- how to stack layers on top of each other to produce a complete plot

You specify in abstract terms exactly what plot you need.  
The computer figures out the technical details needed to create the plot.  
So you simply declare what you want, the computer does the work and creates it.

In 1999 the academic [Wilkinson Leland](https://en.wikipedia.org/wiki/Leland_Wilkinson) published the theory of "The Grammar of Graphics".  
In 2005 Hadley Wickham implemented an interpretation of this grammar in the [ggplot2](https://en.wikipedia.org/wiki/Ggplot2) package for R .  
In 2014 Yhat came with [ggplot](http://ggplot.yhathq.com/) for Python (a Python clone of R ggplot2).  
In 2016 Hassan Kibirige released [plotnine](https://plotnine.readthedocs.io/en/stable/#) (a better R ggplot2 clone for Python)

We will use plotnine.

### example

![ggplot2 example](http://i.imgur.com/4S7r3Z3.jpg)

With only four lines we can produce a complex plot.  

Note that this example was not produced with Python but with R.  
However that does not really matter, in Python it looks very much the same
[Have a look](./cookbook/apdx02_replication%20of%20R%20results.ipynb).

At first glance the first three lines come over as gobbledygook.  
There is clearly some explaining to do.   
But luckily the explanation is not that hard, have a look at 101-the basics. 

---

#### [goto the cookbook table of content](./cookbook/000_toc.ipynb)

----
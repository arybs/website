---
layout: page-no-title
title: Python
---

<header class="post-header">
    <h1 class="post-title" style="text-align:center"><i class="fab fa-python fa-fw fa-lg fa-notbold svv"></i>{{ page.title | escape }}</h1>
</header>

Python is a great language for scientific computing, most of the programming done by our group is in python. We provide below some links for learning this language, and below we offer many python code examples. You are invited to download these codes, tweak with them, break them, hack them as you wish!


Most codes focus on plotting, but other algorithms such as numerical integration and Fourier transforms can also be found. 

Some useful links for learning python:

* <a href="http://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb" target="_blank">Python Data Science Handbook</a>
* <a href="https://learnpythonthehardway.org/book/" target="_blank">Learn Python the Hard Way</a>
* <a href="http://nbviewer.jupyter.org/gist/rpmuller/5920182" target="_blank">A Crash Course in Python for Scientists</a>
* <a href="http://swcarpentry.github.io/python-novice-inflammation/" target="_blank">Software Carpentry</a>
* <a href="http://matthiaseisen.com/fwl/py/" target="_blank">Fun with Lists</a>
* <a href="https://www.codecademy.com/learn/python" target="_blank">Python | Codecademy</a>
* <a href="http://www.scipy-lectures.org/index.html" target="_blank">Scipy Lecture Notes</a>
* <a href="https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks" target="_blank">A gallery of interesting IPython Notebooks</a>
* <a href="http://greenteapress.com/thinkpython/html/index.html" target="_blank">Think Python: How to Think Like a Computer Scientist</a>  
* <a href="https://python-graph-gallery.com/" target="_blank">The Python Graph Gallery</a>  

This might be overwhelming, so I suggest you to follow this:
{% twitter https://twitter.com/jakevdp/status/906901174728536066 %}  

Start by downloading <a href="https://www.anaconda.com/distribution/" target="_blank">Anaconda</a>, a package manager application that will help you get started with python in all platforms.


Make sure you are acquainted with ipython (interactive python, <a href="https://www.pythonanywhere.com/try-ipython/" target="_blank">try it here</a>), and with <a href="http://jupyter.org/" target="_blank">Jupyter notebook</a>.
​

I recommend <a href="https://www.sublimetext.com/" target="_blank">Sublime Text</a> for writing code, and you can install the Anaconda package to it to have a smooth IDE. [not the same anaconda as mentioned above! Yes, it's confusing, I know.]

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Fitzhugh-Nagumo --- Labyrinthine Patterns

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/fhn', '_blank');">Jupyter notebook</button>

Main features:
how to make a movie, time-integration methods (semi-spectral and Euler)

<iframe width="560" height="315" src="https://www.youtube.com/embed/5au-G5FuI_A" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Conway's Game of Life, acorn initial conditionnn

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/gol', '_blank');">Jupyter notebook</button>

This is a (slightly) modified version of <a href="https://glowingpython.blogspot.co.il/2015/10/game-of-life-with-python.html" target="_blank">Glowing Python</a>'s code. I make it available here because it features a few nice things:

* how to make a movie using matplotlib.animation
* how to write a generator (function with yield)
* how to plot a sparce array (spy)  

Main features:
`matplotlib.animation, yield, with, matplotlib.pyplot.spy`

<iframe width="560" height="315" src="https://www.youtube.com/embed/lelsVltLZe4?rel=0" frameborder="0" allowfullscreen></iframe>

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Least squares fit of nonlinear function

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/leastsquares', '_blank');">Jupyter notebook</button>

Main features:
`LaTeX text, scipy.optimize.curve_fit, matplotlib.patches`  
![](/images/python_figures/least-squares.png)

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Fun with histograms

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/histograms', '_blank');">Jupyter notebook</button>

Main features:
`np.histogram, plt.hist, plt.bar, plt.barh, gridspec, least squares fit of nonlinear function, plt.hist2d`  
![](/images/python_figures/histograms.png)

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Fancy subplot grid

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/subplotgrid', '_blank');">Jupyter notebook</button>

Highly customizable subplot structure. Also, figure contains several axis configurations and labeling options.  
Main features:
`gridspec subplots; numpy-compatible heaviside; label, ticks and axis manipulations; log scale`
![](/images/python_figures/subplot-grid.png)

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Streamplot

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/streamplot', '_blank');">Jupyter notebook</button>

Streamplot of a two-dimensional linear system, with eigenvectors and nullclines. Python shows LaTeX equations beautifully.  
Main features:
`meshgrid, streamplot, contour, legend, LaTeX`
![](/images/python_figures/streamplot.png)

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## The time dependent Ginzburg-Landau equation

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/tdgle', '_blank');">Jupyter notebook</button>

Numerical integration of a parabolic partial differential equation, using finite differences: Euler step to advance time, and a 5-point stencil to approximate the Laplacian.  
Main features:
`imshow, colorbar, set_data`

<iframe width="560" height="315" src="https://www.youtube.com/embed/JgE9Px7zsQE" frameborder="0" allowfullscreen></iframe>

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## The double pendulum

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/doublependulum', '_blank');">Jupyter notebook</button>

Numerical integration of the equations of motion of the double pendulum. This time, scipy's ode itegrator was used. Nice example of how to make a movie.  
Main features:
`scipy.integrate.ode, set_data, set_aspect('equal'), remove plot, movie`

<iframe width="560" height="315" src="https://www.youtube.com/embed/-76LN_Kph7A" frameborder="0" allowfullscreen></iframe>

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## The Hilbert curve

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/hilbertcurve', '_blank');">Jupyter notebook</button>

Construction of the Hilbert curve as a Lindenmayer system (L-system).  
Main features:
`string operations, movie`

<iframe width="560" height="315" src="https://www.youtube.com/embed/Oudyl56GPJU" frameborder="0" allowfullscreen></iframe>


<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## A hysteresis mechanism

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/hysteresis', '_blank');">Jupyter notebook</button>

Hysteresis mechanism created by the bistability of states. System goes to minimum points u in the energy functional $f=u^4-2u^2+hu$. The parameter $h$ is ramped down and up during this simulation.  
Main features:
`sympy analytical calculations, numpy dtypes, movie`

<iframe width="560" height="315" src="https://www.youtube.com/embed/xgRDhOifFow" frameborder="0" allowfullscreen></iframe>

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Contour plot

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/contours', '_blank');">Jupyter notebook</button>

Contour plot with many customizable options. Also, a nice way to truncate a colormap so it gives the color range that you want.  
Main features:
`truncate_colormap, contour, contourf (fill), clabel (contour label)`

![](http://www.bitbucket.org/yairmau/notebooks/raw/master/figures/cont.png)

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Least action principle on the beach

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/bestpath', '_blank');">Jupyter notebook</button>

How should ​lifeguard run in order to save a drowning person in minimal time? Answer: by using Snell's law of refraction!  
This is a nice example how to use spines (x and y axis form a cross), instead of rectangular figures as usual. Also, "annotations" are used, where things can be labeled with the help of arrows.  
Main features:
`spines, matplotlib.patches.Rectangle, annotate`

![](/images/python_figures/bestpath.png)


<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## This website's logo

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/websitelogo.ipynb', '_blank');">Jupyter notebook</button>

Simple example of how to make a figure without any visible axes.  
Main features:
`set_axis_off, fill_between, matplotlib inline plot on Jupyter`

![](/images/python_figures/site-logo.png)

<hr style="border-top: 3px solid #ccc;">

<!-- ------------------------------------- -->
<!-- ------------------------------------- -->

## Bars

<button class="my_button" onclick="window.open('../../jupyter/2020/01/01/bars', '_blank');">Jupyter notebook</button>

Horizontal and vertical bars, with numeric legends. Unicode support.  
Main features:
`unicode, bar, barh, grid`

![](/images/python_figures/bars.png)


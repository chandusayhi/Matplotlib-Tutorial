## “Matplotlib is one of the most popular Python packages used for data visualization. It is a cross-platform library for making 2D plots from data in arrays. It provides an object-oriented API that helps in embedding plots in applications using Python GUI toolkits such as PyQt, WxPythonotTkinter. It can be used in Python and IPython shells, Jupyter notebook and web application servers also.
-------------

<p>
<h2>What is matplotlib?</h2>
    
Matplotlib is the most popular plotting library for Python. It was written by John D. Hunter in 2003 as a way of providing a plotting functionality similar to that of MATLAB, which at the time was the most popular programming language in academia.

Matplotlib offers a hierarchy of objects abstracting various elements of a plot. The hierarchy starts with the top-level Figure object that may contain a series of intermediate level objects and Axes – from Scatter, to Line and Marker, and all the way down to Canvas. In order to produce a plot on the screen, the matplotlib Figure instance must be coupled with one of the supported user interface backends such as TkInter, Qt, WxWidgets or MacOs. Outside of matplotlib documentation, user interface backends are typically referred to as “interactive”. In order to produce a file on a disk, matplotlib uses hardcopy backends for a variety of bitmap (png, jpg, gif) and vector (ps, ps, svg) file formats. Hardcopy backends are also called “non-interactive”.

A distinguishing feature of Matplotlib is the pyplot state machine which enables users to write concise procedural code. Pyplot determines the object to apply the relevant method from the context or creates the necessary objects on the fly, if they don’t exist. While this allows for fast experimentation, it can result in less reusable and less maintainable code.

In practice, it’s almost impossible to use matplotlib without pyplot. The Matplotlib user guide recommends using pyplot only to create figures and axes, and, once those are created, use their respective methods to create plots. This is reasonable, and we stick to this style in this tutorial, however I would advise not following it too rigidly when exploring new data. Having to look up which methods belong to which objects interrupts the flow of analytical thought and negatively affects productivity. The initial code can be easily converted to object-oriented style once you have finished exploring the data and know what visualizations you are going to need.

The ability to combine these two styles leads to great flexibility – according to the library maintainers, matplotlib makes easy things easy and hard things possible.
</p>

<p>
<h2>When to use matplotlib?</h2>
    
The question is, what is hard and what is easy to implement in matplotlib?
There are two areas where matplotlib is particularly powerful:

    exploratory data analysis
    scientific plotting for publication

Matplotlib’s strength in exploratory data analysis comes from the pyplot interface. With pyplot you can generate a variety of plots with a small number of keystrokes and interactively augment existing figures with new data. Additionally, the seaborn library built on top of matplotlib provides even more visualizations with some basic data analysis, such as linear regression or kernel density estimation, built in.

The second area of matplotlib’s excellence is data visualization for publication. It can generate vector images in a variety of formats using its hardcopy (non-interactive) backends. When generating bitmap images matplotlib provides aesthetically pleasing rendering using Anti Grain Geometry (Agg). The default selection of axis annotations, fonts and ability to render mathematical notation using LaTeX syntax make it perfect for preparing figures for scientific journals or homework.
 
</p>





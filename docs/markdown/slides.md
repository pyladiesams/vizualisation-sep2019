Who am I
---------------
<div>
  <img width="800px" style="display:block; margin-top:50px; margin-bottom:50px" src="images/carreer.svg">
  <img style="display:block" width="700px" src="images/cloud.svg">
</div>


What do I do
-----------------
<blockquote style="display:block; width:80%; font-size:.8em; background:#eeeeee; text-align:center">
I use computational models to understand how cells interact with eachother and their environment in development and disease.
</blockquote>

<div style="margin-top:50px; display: flex; flex-direction: row; font-size:.75em; justify-content: space-between; align-items: flex-end; text-align:center">
  <div style="width:350px; box-sizing: border-box;">
    <div style="margin-bottom:5px">angiogenesis</div>
    <video width="300px" controls loop autoplay>
    <source src="movies/dtc_Ct_0133.mp4" type="video/mp4">
    </video>
  </div>
  <div style="width:350px; box-sizing: border-box;">
  <div style="margin-bottom:10px">cell migration in ECM</div>  
  <video width="300px" controls loop autoplay>
  <source src="movies/track_1rod_polarized_0010.mp4" type="video/mp4">
  </video>  
  </div>
  <div style="width:350px; box-sizing: border-box;">
  <div style="margin-bottom:10px">2D cell migration</div>  
  <video width="300px" controls loop autoplay>
  <source src="movies/ma_multicell_0027-1.mp4" type="video/mp4">
  </video>  
  </div>
</div>


What do I know about data visualization
---------------------------------------------
* I'm not an expert, I just spent a lot of time visualizing data

<img src="images/plotting_experience.svg" style="display:block">

* I want to share my experience on
  * tools that help with visualization
  * making visualizations ready for reports, presentations, etc.



Why visualize data
---------------------------------
<div class="flex-row">
  <div style="text-align:center">
    <div> Exploration </div>
    <img width="400px" src="images/example_exploration.svg">
    <ul>
      <li> High information density </li>
      <li> Little effort in creation </li>
    </ul>
  </div>
  <div style="text-align:center">
    <div> Presentation </div>
    <img width="400px"  src="images/example_presentation.svg">
    <ul>
      <li> Low information density </li>
      <li> Lots of effort in creation </li>
    </ul>    
  </div>
</div>


How to get from exploration to presentation?
--------------------------------------------------
1. Make a *good* exploratory plot
  * Next steps are just refinements
2. Define message of the plot
  * What information should be in the plot?
  * What information should be highlighted?
  * What information can be left out?
3. Define presentation medium
  * What elements are suitable?
  * How long will the audience be looking at the plot?


What is (not) a *good* plot
--------------------------
<div style="text-align:center">
<img width="50%" src="https://serialmentor.com/dataviz/introduction_files/figure-html/ugly-bad-wrong-examples-1.png">
  <div style="font-size: .5em; text-align: center; margin-bottom: 20px">
  Image from Fundamentals of Data Visualization by Claus O. Wilke
  </div>
</div>


More examples
--------------------------
* Misleading axes

<img width="50%" style="display:block" src="images/yaxis.svg">

* Too many (?)
<img style="display:block" width="100%" src="images/too_many.svg">


Tools - plot types
-----------------------------
<img style="display:block" src="images/example_styles.svg">

* Try different plot types during exploration
* Use the most suiting one for presenting


Tools - plot types - finding the right type
-----------------------------------------------
* 2019 stack survey data on salaries for male/female respondents.
* ~45000 respondents, > 90% male

<div class="fragment">
  <img src="images/stack_plot1.svg">
  <div>Does this plot give a representative image?</div>
</div>


Tools - plot types - finding the right type
-----------------------------------------------
Show the distribution in more detail
<div>
  <img class="fragment" width="450px" src="images/stack_plot2.svg">
  <img class="fragment" width="450px" src="images/stack_plot3.svg">
</div>



Tools - plot elements
-------------------------------
<div>
<img src="https://serialmentor.com/dataviz/aesthetic_mapping_files/figure-html/common-aesthetics-1.png">
  <div style="font-size: .5em; text-align: center; margin-bottom: 20px">
  Image from Fundamentals of Data Visualization by Claus O. Wilke
  </div>
</div>

* Use for distinguishing data
* Use for highlighting the message of a plot


Tools - colors
-----------------------
* Issues:
  * not everyone can percieve all colors
  * not every beamer/printer reproduces colors as intendend
* Solutions:
  * use sequential color maps for values
  * match plot and legend order
  * make colors redundent if possible
  * use divergent colors for distinguishing


Tools - better colormaps
-------------------------------------
* Rainbow and Jet are evil, don't use them!
<img style="display:block;" src="images/sphx_glr_colormaps_014.png">
* Use sequential colormaps that also work with grey scale:
<img style="display:block;" src="images/sphx_glr_colormaps_008.png">



This workshop
-------------------------------
* Aims:
  * get a *taste* of creating good plots with Python
  * get some handles to continue on your own
* Topics:
  * Basic plotting with `matplotlib`
  * Utilize `pandas` together with `seaborn`
  * Utilize `seaborn` to make publication ready plots



Resources
---------------
* [Fundamentals of Data Visualization by Claus O. Wilke](https://serialmentor.com/dataviz/)
* [Data to Viz](https://www.data-to-viz.com/index.html)
* [Python Graph Gallery](https://python-graph-gallery.com)

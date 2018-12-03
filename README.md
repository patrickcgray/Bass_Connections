## Bass Connection - Deep Learning and Remote Sensing for Coastal Resilience and Disaster Response (2019-2020)

### NOTE: this readme and whole repo is still in development and changing constantly.

This website is specifically for students working on the 2019-2020 Bass Connections project but could be of interest to a wider ranger of folks interested in learning about scientific computing for geospatial analysis, remote sensing for change detection, and combining remote sensing with new deep learning and computer vision techniques.

### Project Overview ([full description](https://bassconnections.duke.edu/project-teams/deep-learning-and-remote-sensing-coastal-resilience-and-disaster-response-2019-2020)):

![Crystal Coast Before and After](https://github.com/patrickcgray/Bass_Connections/blob/master/before_after_flo_outflow.png)

The purpose of this project is to use Hurricane Florence's impacts on North Carolina’s coastline to develop a methodology for rapid and high-resolution monitoring of coastal areas in the face of storm impacts. We will do so by leveraging convolution neural networks (CNNs) to automate change detection in satellite imagery. The change detected via satellite will trigger a time-series of UAS surveys for areas that experienced substantial change.

#### Outcomes:

* Development of habitat classification and change detection tool for satellite imagery
* Publication in peer-reviewed journal. Potentially publishing on comparison of different methods, data inputs, model architectures for creating the best classifier for Southeast US coastal environments and or publishing on the methods and results of the tip-and-cue surveys to understand impact and recovery from Hurricane Florence
* Lay the foundation for future research and grants to explore using a coordinated satellite and drone system to monitor and evaluate ecosystem services provided by coastal habitats

### Spring Semester Independent Study

This independept study will have three components: self-led learning, a journal club, and an independent project.

#### Potential Projects:
All of these are flexible and will be dependent on student interests and skills but provide a starting place.

* initial CNN based classification of satellite and drone imagery
* paper on tip-and-cue methods and applications in storm/disaster response
* methods for analyzing and visualizing geospatial data using open source tools like python, jupyter notebooks, etc
  *   * https://github.com/HyperionAnalytics/PyDataNYC2014
* Docker based API capable of ingesting imagery and outputting a classified map 
  * we will develop the model to do the classifying during the summer, but just the API 
* interactive website capable of visualizing maps, images, and classified products
* exploring new CNN architectures for analyzing remote sensing data
* paper discussing how rapid monitoring can facilitate management of coastal areas
* novel ways to visualize geospatial data
  * e.g. https://blog.mapbox.com/high-resolution-land-cover-and-land-use-data-classification-in-unity-e101ab119e98
  * e.g. https://blog.mapbox.com/combining-the-power-of-aws-lambda-and-rasterio-8ffd3648c348

#### Papers:

* Lecun et al. 2015 Deep Learning
  * https://www.nature.com/articles/nature14539
* Convolutional Neural Networks for Large-Scale Remote-Sensing Image Classification 
  * https://ieeexplore.ieee.org/document/7592858
* Zhu et al. 2017 Deep Learning in Remote Sensing
  * https://ieeexplore.ieee.org/document/8113128/
* Weinstein. 2018 A computer vision for animal ecology
* https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap

#### Educational Resources:

##### Students will choose from these resources for a total of 8 weeks of work in this section. We'll be open to other suggestions if they seem of sufficient quality, rigor, and relevance.

* Remote Sensing
  * Scientific Computing for for Remote Sensing
    * https://github.com/profLewis/geogg122
    * http://blog.rtwilson.com/resources-for-learning-python-for-remote-sensing-or-switching-from-idl/
  * Fundamentals of Remote Sensing
  * NASA Disaster Mgmt: https://arset.gsfc.nasa.gov/disasters/webinars/disaster-overview-2016 
  * Ocean RS: https://arset.gsfc.nasa.gov/land/webinars/coastal-oceans-2016 
  * HAB RS: https://arset.gsfc.nasa.gov/water/webinars/HABs17 
  * Ecoforcasting: https://arset.gsfc.nasa.gov/land/webinars/scenario-based-ecoforecasting-17 
* Coding
  * Software Carpentry with Python (1 week)
    * http://swcarpentry.github.io/python-novice-inflammation/
  * Udacity Intro to Python (3 weeks) 
    * https://www.udacity.com/course/introduction-to-python--ud1110
  * Learn Python the Hard Way (3 weeks)
    * https://learnpythonthehardway.org/python3/
  * Python Like you Meant It (1 weeks)
    * https://www.pythonlikeyoumeanit.com/
  * Head First Python by Paul Barry
* GIS
  * ArcPro Intro (2 weeks)
    * ArcPro GIS course 
  * Python
    * rasterio - Reading and writing geospatial data (rasters)
    * shapely - Manipulation and analysis of geometric objects (vectors)
    * fiona - Reading and writing geospatial data (vectors)
    * https://gist.github.com/jacquestardie/0d1c0cb413b3b9b06edf#file-modern-geospatial-python-md
* Data Science and Visualization (also Geospatial Visualization)
  * Udacity Intro to Data Analysis (4 weeks)
    * https://www.udacity.com/course/intro-to-data-analysis--ud170
  * Python Data Science Handbook (3 weeks)
    * https://jakevdp.github.io/PythonDataScienceHandbook/
  * Data Visualization and D3.js (4 weeks)
    * https://www.udacity.com/course/data-visualization-and-d3js--ud507
  * Adobe Illustrator
* Machine Learning
  * An intuitive understanding of Neural Networks - 3Blue1Brown (.5 weeks)
    * https://www.youtube.com/watch?v=aircAruvnKk
  * Google's Machine Learning Crash Course (1 week)
    * https://developers.google.com/machine-learning/crash-course/
  * Coursera Deep Learning Specialization (12 weeks)
    * https://www.coursera.org/specializations/deep-learning
    * Convolutional Neural Network Subset of this Specialization (3 weeks)
      * https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning
  * Deep Learning with Python Book (3 weeks)
    * https://www.amazon.com/Deep-Learning-Python-Francois-Chollet/dp/1617294438
  * https://github.com/llSourcell/Learn_Deep_Learning_in_6_Weeks
  * https://github.com/patrickcgray/deep_learning_ecology
* Generally useful Tools
    * Git
    * How to read code documentation

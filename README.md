![UCL](docs/images//ucl_logo.png)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/profLewis/GEOG0027.git/master)

[ReadTheDocs](https://geog0027-environmental-remote-sensing.readthedocs.io/en/latest/)

# GEOG0027 Environmental Remote Sensing

## Course Tutors 2022/23

[Prof. M. Disney](http://www2.geog.ucl.ac.uk/~mdisney)

[Dr Harry Heorton](mailto:h.heorton@ucl.ac.uk)


Department of Geography
    
University College London
    
    
[[Educational Aims and Objectives of the Course](#Education)]  [[Course workload and assessment](#workload)]  [[Timetable 2022-23](#Timetable)]   [[Reading List](#ReadingList)]

![](docs/images/Mission_Minerva_Big_Picture_London.jpg)
[London from the International Space Station, August 2022, taken by astronaut Samantha Cristoferetti.](https://www.esa.int/ESA_Multimedia/Images/2022/09/Mission_Minerva_Big_Picture_London#.Y7P38Vr0nwQ.link)

-----------------------------------


#### <a name="Education">Educational Aims and Objectives of the Course</a>

 To enable the students to: 
 
+ Understand the nature of remote sensing data and how they are acquired
+ Understand different types of remote sensing instruments and their missions
+ Understand basic image representation and processing
+ Understand how Earth Observation data can be combined with other sources of data and data techniques (e.g. GIS)
+ Understand how EO data can be used in environmental science (particularly via classification and monitoring)
+ Develop practical skills in these areas, which may be useful in planning of dissertations
+ Develop links with the second year course on Geographic Information Systems Science and with othet courses as appropriate (e.g. hydrology, environmental systems)

-----------------------------------


#### <a name="workload">Course workload and assessment</a>

##### Expected Course Load

|Component 	|Hours|
|-------  | :--------:|
| Lectures | 	10|
|Private Reading 	|80
|Supervised Laboratory Work (Computing) |	20|
|Independent Laboratory Work (Computing) |	20|
|Required Written Work |	10|
|TOTAL |	140|

Usual range 100-150 for 1/2 course unit 


-----------------------------------


##### Assessment

+ 100% Assessed Practical (3000 words) - submission date standard 2nd year submission date i.e. Mon 24th April 2023 (12 noon).
+ For details of the coursework, please see [https://github.com/UCL-EO/GEOG0027_Coursework](https://github.com/UCL-EO/GEOG0027_Coursework) or READ-ONLY VERSION at [ReadTheDocs](https://geog0027-coursework-2020-2021.readthedocs.io/en/latest/)

N.B.

- Penalties for late submission and over length WILL be applied
- Different arrangements for JYA/Socrates (make sure you inform the lecturers if this affects you)

-----------------------------------


#### <a name="Timetable">Timetable 2021-22</a>
Thursday Practicals will be in two groups, set at the beginning of term.


|  | Monday Lecture 11:00-12:00 | Thursday Practical 09:00-11:00 and 11:00-13:00 |
| ------------------- | :-------------------: | :-----------------: | 
| Week 1 |  LECTURE 1 [Introduction to course](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=5) | 12/1/2023 COMPUTING 1 [Image Display](docs/ImageDisplay.ipynb) |
| Week 2 | LECTURE 2 [Image Display and Enhancement](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=6) | 19/1/2023 [Image Display](docs/ImageDisplay.ipynb) Intro to [Google Earth Engine](docs/Intro_to_GEE.ipynb) |
| Week 3 | LECTURE 3 [Spatial Information](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=7) | 26/1/2023 COMPUTING 2 [Spatial Filtering](docs/SpatialFiltering.ipynb) |
| Week 4  | LECTURE 4 [Image Classification](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=8) | 2/2/2023 COMPUTING 3 [Classification](docs/Classification.ipynb) | 
| Week 5 | LECTURE 5 [Spectral Information](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=9) | 9/2/2023 COMPUTING 3 [Classification](docs/Classification.ipynb)  |
| Week 6 | READING WEEK | READING WEEK |
| Week 7 | LECTURE 6 [Environmental Modelling: I](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=10) | 23/2/2023  COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework) |
| Week 8 | LECTURE 7 [Environmental Modelling: II](https://moodle.ucl.ac.uk/course/view.php?id=26363&section=11)  | 2/3/2023 COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework)| 
| Week 9 | 6/3/2023 COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework) | 9/3/2023 COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework)| 
| Week 10 | 13/3/2023 COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework)| 16/3/2023 COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework)| 
| Week 11 | 20/3/2023 COMPUTING 4 [Project](https://github.com/UCL-EO/GEOG0027_Coursework) | 23/3/2023 COMPUTING 4  [Project](https://github.com/UCL-EO/GEOG0027_Coursework)|  

Monday lectures are in are in NWW G07 and Thursday practical sessions will be in North West Wing Room 110 ('Unix lab')

#### ENVI Software
ENVI is available on the machines in NWW 110, though there are othe roptions for independent learning.

ENVI 5.5.3 is available to registered students through Virtual UCL PCs during the live sessions via UCL Desktop Anywhere (see help info at https://www.ucl.ac.uk/isd/how-to/how-to-log-to-virtual-teaching-pc). 

For ad-hoc use of ENVI software outside of the live hours, it can be accessed from UCL Desktop Anywhere. We will use the ENVI 5.5.3  (not ENVI Classic 5.5.3) version for the guided practicals before half term. Additionally, you can install ENVI on your personal computer with a UCL license (http://swdb.ucl.ac.uk/package/view/id/142?filter=envi). However, support might be limited from the teaching staff. Thus, we recommend using Desktop@UCL during the term time for best support and accessibility. 

Google Earth Engine is accessed from within IPython notebook. These can be easily run on [UCL jupyter hub](https://jupyter.data-science.rc.ucl.ac.uk/), accessible using a standard UCL login. The notebooks can also be used wthin a open-source conda distribution, though setting up all the libraries can be cumbersome and staff will not have the time to support this.


-----------------------------------


#### <a name="ReadingList">Reading List</a>

- Jensen, John R. (2006) Remote iSensing of the Environment: an Earth Resources Perspective, Hall and Prentice, New Jersey, 2nd ed.
- Jensen, John R. (1995, 2004) Introductory Digital Image Processing: A Remote Sensing Perspective (Prentice Hall Series in Geographic Information Science)
- Jones, H. G and Vaughan, R. A. (2010) Remote Sensing of Vegetation, OUP, Oxford.
- Lillesand, T., Kiefer, R. and Chipman, J. (2004) Remote Sensing and Image Interpretation. John Wiley and Sons, NY, 5th ed.
- Mather, P. (2004) Computer processing of remotely sensed images: an introduction 


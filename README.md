Intermediate Computational Meteorology
======================================

*These course materials are currently under development by [Jon Thielen](https://github.com/jthielen) as an Honors Project at Iowa State University during the Spring 2019 semester (Project Advisor: Dave Flory). This is not an actual course at Iowa State at this point in time, but these resources are meant to be available openly for any potential future course or independent learning. For any questions, please contact Jon.*

Course Overview
---------------

**Description**

This course aims to prepare meteorology students for the kinds of computer programming they are likely to undertake in advanced coursework, research, and operations. It takes a survey-level approach to a breadth of topics: the utilization of the Python programming language (and numerous scientific packages therein) in academic, research, and forecasting settings, the use of version control systems and other supporting tools, collaboration on the development of scientific software, and commonly-encountered operational problems. Emphasis is placed on projects meant to provide practical demonstrations of course topics.

**Structure**

This course is structured into [five modules](#modules), each designed to take roughly three weeks, with the following class and assignment/assessment breakdown (for a 3 day per week schedule):

- Classes
	- Five or six lectures
	- Two or three interactive work days
	- One or two retrospective, demonstration, or presentation days
- Assignments/Assessments
	- One quiz (formative)
	- One in-class/lab assignment (formative)
	- One small project (except Module 5, which has the final project)

Online resources will be made available on this GitHub repo or through external links in lieu of a textbook.

**Grading**

- Quizzes: 15% (3% each)
- In-Class Assignments: 15% (3% each)
- Small Projects: 40% (10% each)
- Final Project: 30%

Modules
-------

**Module 1: Intermediate Python**

Learning Objectives:

- Gain proficiency in using Jupyter notebooks and scripts to run Python code
- Have ability to effectively use list comprehensions, generators, objects, and anonymous functions in Python
- Have basic familiarity with procedural, object-oriented, and functional paradigms
- Use numeric arrays with NumPy and xarray

Project: Demonstrate skill in using Python features covered in this module through a set of coding problems

**Module 2: Version Control and Open Development**

Learning Objectives:

- Be able to effectively use SSH, bash, and standard command line utilities
- Develop a basic working knowledge of git (especially branches and commits) and GitHub (issues and pull requests)
- Have ability to write well-documented and well-tested code (following style guides, using basic unit tests, etc.)
- Know how code reviews are conducted
- Become familiar with the open source software community in the geosciences

Project: Submit a pull request on GitHub to improve or add to course materials (use of code tests and good documentation practices required)

**[Module 3: Statistical Analysis and Figure Creation for Publications](module3/)**

Learning Objectives:

- Be able to effectively use matplotlib and supplementary plotting libraries to create informative, publication-quality figures
- Conduct statistical analysis using scipy and pandas
- Gain familiarity with best-practices for creating scientific figures for publications and presentations
- Be able to implement basic equations in figures using LaTeX

Project: Create an analysis notebook for a research dataset (class example or data from students' own research)

**Module 4: Meteorological Calculations and Basic Numerical Methods**

Learning Objectives:

- Be able to effectively use xarray and MetPy for conducting meteorological calculations on gridded model/analysis data and sounding data
- Understand how open source projects implement calculations
- Be able to implement new, previously-unimplemented calculations from literature
- Gain basic familiarity with standard numerical methods for integration, differentiation, interpolation, and smoothing

Project: Implement a set of meteorological calculations, with proper documentation and tests, and include a brief demonstration notebook

**Module 5: Tacking Practical Problems in Operational Meteorology**

Learning Objectives:

- Gain familiarity with real-time data access and archive data retrieval
- Know how to work with common meteorological data formats (netCDF, GRIB, text formats, and others)
- Understand the nuances of working with common operational data (Doppler radar, models, satellite, upper air observations, and surface observations)
- Have basic understanding of objective analysis techniques

Project: [Final Project](#final-project)

Final Project
-------------

The final project is meant as a practical demonstration of all skills learned in this course. It will be focused on an individual operational analysis or research question, and it typically takes the form of a case study or short research project. The components of the project are:

- Obtain data
- Analyze data and produce figures
- Demonstrate understanding of the type(s) of data used
- Take into account data quality issues
- Write short paper (i.e., an extended abstract) and share the paper and supplementary materials (at a minimum, well-explained notebooks) on GitHub
- Give a short (10-minute) presentation

Project topics should be approved by the instructor by mid-term. Students are encouraged to begin work on the final project during earlier portions of the course, especially with any needed literature review. Note that some useful background concepts will not be covered until the final module.

*This project will be due at the end of Dead Week, with presentations occurring during the final exam period (and during the final class of Dead Week if needed).*

References
----------

The following sources were used in the development of this course:

Chastang, J., and Coauthors, 2018: Unidata Python Training Workshop. Accessed 16 September 2018, https://unidata.github.io/unidata-python-workshop/ 

DeCaria, A. J., 2012: *Python Programming and Visualization for Scientists*. Sundog Publishing, 270 pp.

Goebbert, K., 2018: met330. Accessed 16 September 2018, https://github.com/kgoebber/met330. 

Heistermann, M., S. Collis, M. J. Dixon, S. Giangrande, J .J. Helmus, B. Kelley, J. Koistinen, D. B. Michelson, M. Peura, T. Pfaff, and D. B. Wolff, 2015: The Emergence of Open-Source Software for the Weather Radar Community. *Bull. Amer. Meteor. Soc.*, **96**, 117–128, https://doi.org/10.1175/BAMS-D-13-00240.1

Horel, J. D., D. Ziegenfuss, and K. D. Perry, 2013: Transforming an Atmospheric Science Curriculum to Meet Students' Needs. *Bull. Amer. Meteor. Soc.*, **94**, 475–484, https://doi.org/10.1175/BAMS-D-12-00115.1

Irving, D., 2016: A Minimum Standard for Publishing Computational Results in the Weather and Climate Sciences. *Bull. Amer. Meteor. Soc.*, **97**, 1149–1158, https://doi.org/10.1175/BAMS-D-15-00010.1

Lin, J. W., 2012: *A Hands-On Introduction to Using Python in the Atmospheric and Oceanic Sciences.* 209 pp.

Lin, J. W., 2012: Why Python Is the Next Wave in Earth Sciences Computing. *Bull. Amer. Meteor. Soc.*, **93**, 1823–1824, https://doi.org/10.1175/BAMS-D-12-00148.1

Schultz, D. M., 2009: *Eloquent Science: A Practical Guide to Becoming a Better Writer, Speaker, and Atmsohperic Scientist*. Amer. Meteor. Soc., 412 pp.

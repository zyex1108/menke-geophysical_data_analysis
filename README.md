﻿# Geophysical Data Analysis: Discrete Inverse Theory  

### William Menke
Third Edition  
Transcribed and translated (from Matlab to Python) by Joshua Poirier  


### Purpose  
The purpose of this repository is solely for personal development and is intended strictly as a remote copy of the version controlled repository.  All material is credited to **William Menke**'s 2012 Third Edition of "*Geophysical Data Analysis: Discrete Inverse Theory (Matlab Edition)*" and its publisher **Academic Press**.  The data contained in this repository was originally downloaded from the books companion website [here](http://www.elsevierdirect.com/v2/companion.jsp?ISBN=9780123971609), along with PowerPoint presentations of related lecture material, and Matlab code.  

**NOTE:**  Much of the LaTeX is not properly rendered/formatted by GitHub.  Locally, it all looks good for me.  

### Repository Description  

This repository differs from the book in that the Matlab code has been translated to Python, intermingling with a subset of the books text via iPython Notebooks.  

* **\data**  

  * These are the related data files used by the notebooks  

* **\nb**  

  * **ch00.ipynb** Introduction  
    * I.3 A very quick Python tutorial  
    * I.4 Review of vectors and matrices and their representation  
    * I.5 Useful Python operations  

  * **ch01.ipynb** Describing inverse problems  
    * 1.1 Formulating inverse problems  
    * 1.2 The linear inverse problem  
    * 1.3 Examples of formulating inverse problems  

  * **ch02.ipynb** Some comments on probability theory  
    * 2.1 Noise and random variables  
    * 2.2 Correlated data  
    * 2.3 Functions of random variables  
    * 2.4 Gaussian probability density functions  
    * 2.5 Testing the assumption of Gaussian statistics  
    * 2.6 Conditional probability density functions  
    * 2.7 Confidence intervals  
    * 2.8 Computing realizations of random variables  

  * **ch03.ipynb** Solution of the linear, Gaussian inverse problem, Viewpoint 1  
    * 3.1 The lengths of estimates  
    * 3.2 Measures of length  
    * 3.3 Least squares for a straight line  
    * 3.4 The least squares solution of the linear inverse problem  
    * 3.5 Some examples  
      * 3.5.1 The straight line problem  
        * Using simulated data  
      * 3.5.2 Fitting a parabola  
        * Kepler's Third Law - The cube of the orbital radius of a planet equals the square of its orbital period  
      * 3.5.3 Fitting a plane surface  
        * Fitting a geologic fault planar surface using earthquake's along Kurile subduction zone  
    * 3.6 The existence of the least squares solution  
      * 3.6.1 Underdetermined problems  
      * 3.6.2 Even-determined problems  
      * 3.6.3 Overdetermined problems  
    * 3.7 The purely underdetermined problem  
    * 3.8 Mixed-determined problems  
    * 3.9 Weighted measures of length as a type of *a priori* information  
      * 3.9.1 Weighted least squares  
      * 3.9.2 Weighted minimum length  
      * 3.9.3 Weighted damped least squares  
    * 3.10 Other types of *a priori* information  
      * 3.10.1 Example: Constrained fitting of a straight line
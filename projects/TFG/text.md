## Wood skis optimization through the virtualization of experimental essays
### DESCRIPTION
This project was the thesis for the BSc in Industrial Engineering (18 ECTS). It was carried out in collaboration with <a href="https://www.likenskis.com/en/" target="_blank"> Liken Skis</a>, a start-up that designs and manufactures high-performance and handcrafted wood skis. The thesis was supervised by <a href="https://www.linkedin.com/in/xayneto/" target="_blank"> Xavier Ayneto Gubert</a>,  a well-known senior professor at UPC with 40+ years of experience.

### OBJECTIVES
The main objective of the project was to define and work with a methodology to optimize a wood skis model. The optimization intended to reduce its weight without performance or features loss.

Secondary goals of the project were to execute lab tests, apply design of experiments (DOE) and virtualize experimental essays using FEM.

### METHODOLOGY

##### WOOD ANISOTROPY AND LAB TESTS
The project started with research in anisotropic materials and its characterization, specifically wood. This research was used to plan two tests in the lab. These tests intended to characterize the mechanical properties used for manufacturing the skis by finding the experimental values of the Young's modulus (E) and shear modulus (G). One of those tests can be seen in the video below.

<iframe width="100%" height="280px" src="https://www.youtube.com/embed/GyFxTksXt-E" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

##### FEM
The second part of the project was to set a model of the wood skis and define the simulation for the subsequent DOE. Since the skis are manufactured not only using wood but also glass fibre and epoxy, setting a suitable model was a huge challenge. In *Fig.1*, the modelled skis can be observed. 

<center><figure>
  <img src="TFG_ANSYS_1.JPG" alt="Modelled skis for the FEM analysis" style="width:110%" class="center">
  <figcaption>Fig.1: Modelled skis for the FEM analysis using ANSYS</figcaption>
</figure></center>

Apart from defining the model, setting a suitable mesh, boundary condition and forces involved was a demanding task. Finally, the model was simulated. These first results can be observed in the video below:

<iframe width="100%" height="280px" src="TFG_ANSYS_v1.mp4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

##### DESIGN OF EXPERIMENTS (DOE) AND OPTIMIZATION
The final part of the project combined DOE with FEM simulations. The input variables were three geometric parameters of the skis, see *Fig.2*, and the responses were the weight of the skis and the maximum deformation and stress. The factorial design was composed of 8 different simulations, experiments, that were carried out using the before explained FEM model.
<center><figure>
  <img src="TFG_parameters.JPG" alt="Geometric parameters used in the DOE" style="width:120%" class="center">
  <figcaption>Fig.2: Geometric parameters used in the DOE</figcaption>
</figure></center>

### RESULTS AND CONCLUSIONS
Finally, the results were analysed and conclusions were drawn. The statistical analysis was intended to minimize the weight of the skis while keeping, or even improving, the maximum deformation and stresses of the initial design. Several plots were obtained, for instance, the cube plot presented in *Fig.3.* which is showing the weight of the skis when different geometric parameters are combined.

<center><figure>
  <img src="TFG_DOE.JPG" alt="Cube plot with a factorial design" style="width:120%" class="center">
  <figcaption>Fig.3: Cube plot with a factorial design</figcaption>
</figure></center>
The final result was a new design which reduced 4% of the total weight, 0.5% of maximum deformation reduction and just a 2% of maximum stress increment.

### FILES AND LINKS
<a href="https://upcommons.upc.edu/handle/2117/127991" target="_blank"> Link to official Bachelor's Thesis document</a>
<center> <embed src="tfgadriabaro.pdf" type="application/pdf" width="100%" height="600px" /> </center> 

### PROJECT GRADE: 10/10 (10-point grading scale, ECTS mark=A+)
[Back to other projects](../../index.md)

___
Copyright © 2020 by Adrià Baró Biosca. All rights reserved.

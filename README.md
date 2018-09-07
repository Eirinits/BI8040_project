# BI8040_project

This github project contains a jupyter notebook built in the context of the [BI8040](https://www.ntnu.edu/studies/courses/BI8040#tab=omEmnet) course entitled "__Logical Modeling for Experimental Design in Current and Future Biotechnology and Biomedicine__", held at Norwegian University of Science and Technology (NTNU) in August 2018. 

## What is it about?
The objectives of this course were to successfully use software tools like GINsim, Pint, MaBoSS, etc. to build, simulate and study logical models behaviour. We focused on the cell cycle example based on the published model of [Traynard et al.](https://doi.org/10.1093/bioinformatics/btw457). The goals of this notebook are to reproduce the results presented in the paper and construct new analysis using the tools presented in the context of this course.

## How to run the notebook?

1. Install the colomoto docker image. [More information](https://github.com/colomoto/colomoto-docker). 
We tested the notebook with the version ```2018-08-17```.
2. Install ```jupyter notebook```. [More information](http://jupyter.org/).
3. Clone our repository: ```https://github.com/Eirinits/BI8040_project.git```. 
4. Go to the project repository and launch the notebook with colomoto docker: ```colomoto-docker -V 2018-08-17```
5. The notebook will be available in your web browser at ```http://localhost:8888/```

### Important note 
This version of colomoto-docker (```2018-08-17```) does not support one of the python package used in our notebook: ```seaborn```.
Consequently, to obtain the heatmaps we created, instead of launching the notebook with colomoto-docker, just launch it with ```jupyter-notebook```
Future version of the colomoto-docker should support this package.

The documentation to each tool used can be accessed through the notebook.


## Contributors
This notebook was developed by Eirini Tsirvouli and Vasundra Touré.

 
## Some references
* Traynard et al. (2016) Logical model specification aided by model-checking techniques: application to the mammalian cell cycle regulation. [DOI](https://doi.org/10.1093/bioinformatics/btw457)
* Naldi et. al (2018) The CoLoMoTo Interactive Notebook: Accessible and Reproducible Computational Analyses for Qualitative Biological Networks. [DOI](https://doi.org/10.3389/fphys.2018.00680)
* Naldi et al. (2018) Logical Modeling and Analysis of Cellular Regulatory Networks With GINsim 3.0. [DOI]( https://doi.org/10.3389/fphys.2018.00646)


# CMS_FCNC_Projects

## Search for flavor-changing neutral currents in processes in  <img src="https://latex.codecogs.com/gif.latex?t\bar{t}" /> multilepton final states in proton-proton collisions with the CMS detector.

This repository contains the final projects of the courses "Laboratory of Computational Physics - Mod B" (LOCP) and "Management and Analysis of Physics Datasets - Mod B" (MAPD) of "Physics of Data" MSc at University of Padua, done in collaboration with Tommaso Stentella, Samuele Piccinelli and Cristina Venturini.

The main purpose of the work is to set an upper limit to the branching fraction of FCNC decay of the top quark in the multilepton channel <img src="https://latex.codecogs.com/gif.latex?t\bar{t}\to\text{Hq+Wb}\to\text{multilepton}">. More specifically, in our work the limit is set on the strength 𝜇 of the signal. The analyzed dataset is composed by simulated FCNC samples, simulated background samples and CMS Data (Run 2016/2017/2018) contaned in `.root` files stored on Cloud Veneto's VMs.

The notebooks [LOCP_CMS_FCNC_pt1](LOCP_CMS_FCNC_pt1.ipynb) and [LOCP_CMS_FCNC_pt2](LOCP_CMS_FCNC_pt2.ipynb) contain our full analysis done using Pyroot v.6.24, while the notebook [MAPD_CMS_FCNC](MAPD_CMS_FCNC.ipynb) contains a reduced analysis done with a distributed approach using Apache Spark.


<img align='right' src='https://raw.githubusercontent.com/TommasoStentella/LCP_B-CMS_FCNC/master/Plots/inv_m01_final_histogram_3.png' alt='Drawing' style='width:400px;'/>
<img align='left' src='https://raw.githubusercontent.com/TommasoStentella/LCP_B-CMS_FCNC/master/Plots/MET_pt_final_histogram_3.png' alt='Drawing' style='width:400px;'/>

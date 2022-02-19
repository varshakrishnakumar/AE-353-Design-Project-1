# AE-353-Design-Project-1
Designing and implementing a Control Moment Gyroscope (CMG)

*Version February 2022*

### Abstract
The objective of this exploration is to implement and verify a feedback controller that uses a single-gimbal control moment gyroscope (CMG) to reorient and control the direction of a spacecraft platform in a gravitational field. The controller and simulation are implemented, designed, and tested in a Python Jupyter Notebook environment. 

### Instructions for compilation
The main file, *CMG_Model_Generator.ipynb*, runs on an *ae353* anaconda environment. The instructions given below will set up the user's system for project compilation.

    conda create -n ae353
    
After creating the environment, if Jupyter and Git are not enabled on Anaconda's system, follow the instructions below

    conda activate ae353
    conda config --env --add channels conda-forge
    conda config --env --set channel_priority strict
    conda install python=3 numpy scipy sympy matplotlib
    conda install notebook ipywidgets imageio imageio-ffmpeg pybullet
    conda install git
    
 Next, clone this repository.
 
    git clone https://github.com/varshakrishnakumar/AE-353-Design-Project-1.git
 
 On an Anaconda Powershell terminal, locate the cloned repository and open Jupyter
    
    conda activate ae353
    cd *location of cloned repository*
    jupyter notebook
 
 Upon completion of the instructions, a new Jupyter notebook will be opened. Navigate to *CMG_Model_Generator.ipynb* to compile the project, and *K_eigen_plots.ipynb* to obtain plots for linear state feedback analysis.
 

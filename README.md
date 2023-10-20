# GraFT-Application-Dev

This repository contains the open source development of the stand-alone application for GraFT using MATLAB.

GraFT (Graph-Filtered Temporal) dictionary learning is a signal extraction method for spatio-temporal data. GraFT uses a diffusion map to learn a graph over spatial pixels that enables for stochastic filtering of learned sparse representations over each pixel's time-trace. The sparse representations are modeled as in a hierarchical dictionary learning framework with correlated decompositions over the graph.

# GraFT-analysis

https://github.com/adamshch/GraFT-analysis

# GraFT2 Executable

1. Prerequisites for Deployment 

Verify that MATLAB Runtime(R2023b) is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2023b 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-GraFT2.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 


3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.

# Manuscript

The details of GraFT are described in:

A.S. Charles, N. Cermak, R. Affan, B. Scott, J. Schiller & G. Mishne. GraFT: Graph Filtered Temporal Dictionary Learning for Functional Neural Imaging.

App Development by Alex Estrada

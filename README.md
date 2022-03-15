

# Directories of SmartFrame
## analysis
Post-processing and data analysis tools for numerical simulations by SmartFrame, including tools to compute and plot undersirable behaviours
- *commons.py*: Basic functions
- *successive_extract.py*: Extract specific output data
### successive_heatmap.py
Plot heatmaps from output data
### successive_statistics.py
Obtain statistical analysis and plots from output data
### successive_tables.py
Prepare CSV and Latex tables from output data
### successive_tools.py
Other Python tools


## datasets
Datasets used in testing including the source and follow-up datasets that are basically collections of photos
### CH2_001
Original Udacity dataset
### MTS_001
Datasets in SmartFrame with different related metamorphic groups
### copy.py
Python script to copy a certain images from multiple folders
### count.py
Python script to count total images in all folders for the purpose of identifying 


## models
Model source codes used in SmartFrame, currently are steering angle based-models with Chauffeur, Autumn and Rambo. Models are configured to run on Supercomputer, however, they can be modified to run on local workstation as well.
### autumn_successive.py
Source code of Autumn model
###  autumn_successive.sh and autumn_successive.slurm
Bash and sbatch scripts to execute Autumn models in Swinburne Supercomputer
### chauffeur_successive.py
Source code of Chauffeur model
### chauffeur_successive.sh and chauffeur_successive.slurm
Bash and sbatch scripts to execute Chauffeur models in Swinburne Supercomputer
### rambo_successive.py
Source code of Rambo model
### rambo_successive.sh and rambo_successive.slurm
Bash and sbatch scripts to execute Rambo models in Swinburne Supercomputer


## params
Model parameters including architecture and weights (Chauffeur, Autumn and Rambo) drived from Udacity
## autumn
The Autumn model
## chauffeur
The Chauffeur model
## rambo
The Rambo model


## tools
Pre-processing tool that is used to generate Sequences of Metamorphic Groups from a source dataset
### add
A tool to add objects into the image at different locations, scale and shapes
### effect
A tool to create effects (rain, snow, gravel, brightness, etc.) in the images with different scale (0: none to 1: maximum).
### arrow
A tool to add annotated arrows into the images
### label
A tool to add annotated labels into the images



---

Unless otherwise stated, all packages are developed by Luu Quang Hung, luuquanghung@gmail.com

***

MIT License

Copyright (c) 2021 Luu Quang Hung

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


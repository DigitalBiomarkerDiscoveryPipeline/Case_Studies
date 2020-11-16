# Case Study on Using Wearables to Detect Stress

In this case study, we will be using wearable sensor data to detect stress. This case study was developed by [Brinnae Bent](https://www.runsdata.org) and [Dr. Amy Herring](https://forge.duke.edu/amy-h-herring-scd). 

This case study is part of dbdpED, the educational resource available through the [Digital Biomarker Discovery Pipeline](https://www.dbdp.org).

### Level
Advanced. You should know Python/R very well and have experience working with datasets in one of the languages. This tutorial is not a step-by-step guide. Rather, it provides the structure and resources for you to explore the data, build your own prediction models, and draw your own conclusions. 

### System Requirements
* Python(3.0.0+) or R
* Either sufficient space on your personal computing machine to download the data OR ability to work on a cluster. If you have Google Drive, we recommend [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) (it's free!).

### Objectives

* Learn how to work with sensor data from wearables
* Learn how to use the DBDP for digital biomarker discovery (including pre-processing, exploratory data analysis, and machine learning)
* Determine whether sensor data from wearables can be used to predict stress

### Dataset
We will be using the Wearable Stress and Affect Dataset (WESAD). It is available on the UCI Machine Learning data repository ([Link](https://archive.ics.uci.edu/ml/datasets/WESAD+%28Wearable+Stress+and+Affect+Detection%29)). We recommend that you read and cite the data release paper, available [here](https://dl.acm.org/doi/10.1145/3242969.3242985).

### Steps for Digital Biomarker Discovery
1. Watch the lectures above either before you get started or while you are working through the data. They cover a lot of pitfalls that may be useful! 
2. Download the dataset and get comfortable with the file system. Read the README of the dataset, since it contains valuable information
3. Pre-process the data. There are a few options for you. If you want to use the pickle file structure, we have a mini-tutorial on dealing with pickle data in Python (see Resources, below). If you want to use the wrist-worn wearable sensor only, we provide pre-processing of the wearable used in the dataset (Empatica E4) in both Python and R.
4. Exploratory Data Analysis. Here is where you want to dive into your data and examine all of the information. 
5. Feature Engineering. Dive into the domain- we recommend reading the "Other Recommended Resources" below if you are unfamiliar with the physiology of stress. Remember, you want to engineer features that are predictive of stress. We provide the Heart-Rate-Variability module to get you started! The wearablecompute package is coming soon!
6. Develop Predictive Models. We encourage your creativity here. We provide some resources for ML and highly recommend trying multiple methods and adapting our code in new, exciting ways.
7. Explore your models! *coming soon*
8. If you created anything that doesn't currently exist in the DBDP (i.e. new exploratory data methods, *******************

### Recommended DBDP Resources


| Resource | How to use it | Language |
| ------ | ------ | ------ | 
| [Getting Started](https://github.com/DigitalBiomarkerDiscoveryPipeline/DBDP/wiki/USER-GUIDE) | User Guide for the DBDP | NA |
| [Pre-process E4](https://github.com/DigitalBiomarkerDiscoveryPipeline/Pre-process/tree/master/Empatica_E4) | Pre-processing wearable E4 data | Python, [R](https://github.com/DigitalBiomarkerDiscoveryPipeline/Education/tree/main/Case-Studies/Case-Study-Stress/Code) |
| [Pickle Data](https://github.com/DigitalBiomarkerDiscoveryPipeline/Education/tree/main/Case-Studies/Case-Study-Stress/Code) | Handling the pickle data format | Python |
| [Exploratory Data Analysis](https://github.com/DigitalBiomarkerDiscoveryPipeline/Exploratory-Data-Analysis) | Explore data, examine missingness, unsupervised learning | Python, R | 
| [Heart Rate Variability](https://github.com/DigitalBiomarkerDiscoveryPipeline/Heart-Rate-Variability) | Feature Engineering Heart Rate Variability | Python |
| wearablecompute | Feature Engineering *(coming soon)* | Python |
| [ML - Random Forests](https://github.com/DigitalBiomarkerDiscoveryPipeline/ML-Methods/tree/master/loocvRF) | Random Forest ML with LOOCV | Python |

### Other Recommended Resources

* [Physiology of Stess Textbook](https://samples.jblearning.com/0763740411/Ch%202_Seaward_Managing%20Stress_5e.pdf)
* [Publication on dataset](https://dl.acm.org/doi/10.1145/3242969.3242985)


### Questions

If you have questions about this Case Study, please [open an issue]() in this repo! 



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

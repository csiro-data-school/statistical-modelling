---
title: Setup
---

## Software

This lesson assumes you have the R, RStudio software installed on your computer.

R can be downloaded [here](https://cran.r-project.org/mirrors.html).

RStudio is an environment for developing using R.
It can be downloaded [here](https://www.rstudio.com/products/rstudio/download/).
You will need the Desktop version for your computer.

Once you have R and RStudio, please open Rstudio and install the packages 'tidyverse' and 'emmeans'. 

## Data

We recommend making a new R project for this lesson, for example called `statistics`.

Please download the zipped data ([csv_files.zip]({{ page.root }}/data/csv_files.zip) and unzip it to a folder called `data` within your `statistics` project folder.

For example, you could use gitbash (or another terminal application) to navigate to your `statistics` folder and use the command line to unzip the data: 

~~~
cd statistics
ls
~~~
{: .language-bash}

~~~
csv_files.zip
~~~
{: .output}

~~~
unzip csv_files.zip -d data 
~~~
{: .language-bash}

~~~
Archive:  csv_files.zip
  inflating: data/csv_files/Arabidopsis_nitrogen.csv  
  inflating: data/csv_files/barley_yield.csv  
  inflating: data/csv_files/cabbage_data.csv  
  inflating: data/csv_files/calcium_pot_trial.csv  
  inflating: data/csv_files/dark_respiration.csv  
  inflating: data/csv_files/drought_data.csv  
  inflating: data/csv_files/forest.csv  
  inflating: data/csv_files/mock_LWR.csv  
  inflating: data/csv_files/nematode.csv  
  inflating: data/csv_files/pea_data.csv  
  inflating: data/csv_files/photosynthesis.csv  
  inflating: data/csv_files/plant_growth.csv  
  inflating: data/csv_files/respiration_data.csv  
  inflating: data/csv_files/seed_orchard_data.csv  
  inflating: data/csv_files/wheat_yield.csv  
  inflating: data/csv_files/wheat_yield_PLUS.csv  
~~~
{: .output}

Check the files are where you want them, then remove the original zip archive to clean up:

~~~
rm csv_files.zip
~~~
{: .language-bash}

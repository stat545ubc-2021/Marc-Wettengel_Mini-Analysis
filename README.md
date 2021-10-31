# STAT545A Mini Data Analysis Project
### Author: Marc Wettengel
### Data set chosen: vancouver_trees

This repository contains all files necessary to complete the STAT545A Mini Analysis Porject and all three Milestones! This analysis was done on the vancouver_trees data set.

### Milestones
- [x] Milestone 1
      - Milestone 1 includes exploratory analysis on multiple data sets from the *datateachr* package. Goal of this deliverable is to visualize the structure of data sets of interest and to postulate potential research questions.  
- [x] Milestone 2
      - After selecting a data set of interest, the *dplyr* and *tidyr* packages were used to become familiar with the structure of the data set of interest and to format the data frame to make it more tangible to the research quesetions created in Milestone 1. By the end of this deliverable, two questions were finalized and final work addressing these questions were conducted in Milestone 3. 
- [x] Milestone 3 
      - The last deliveralbe in the Mini Data Analysis. Milestone 3 further dove into the manipulation of the data set, and produced some conclusions to one of my research questions. 



### How to engage with this repository:

There are a few options with how to navigate this repository. First, you can decide to downlaod all the .Rmd files contained in each Milestone folder and run the code yourself! If this is how you would like to understand the process used to explore and analyze the *vancouver_trees* data set, there are a few installations needed prior to running the coded files. 

```{r}
install.packages("devtools")
devtools::install_github("UBC-MDS/datateachr")
``` 

After installing the *datateachr* package, you can next install the necessary packages used in my analysis. To do this use *install.packages("data_package_name")*. Here are the packages required:

```{r}
tidyverse
ggplot2
here
dplyr
```
After installing all the packages, you're now able to run the code! In each milestone .Rmd file, There are coded "chuncks" where the analsis and exploration is performed. There is some dialogue on what the commands do, and the purpose and expectations on running each command.

If you're just wanting to view the final results and publications for each milestone, there is a .md file in each of the milestone folders for easy reading and presentation! With these .md files, there is no code needing to be run and therefore nothing needs to be installed on your computer.













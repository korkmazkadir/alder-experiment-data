# Experiment Results
The repository hosts the data collected from experiments.

The repository uses git lfs, after checkout, you need to use following command to fetch large files:

```git lfs fetch --all```

***raw_data*** folder contains the raw data of experiments and the scripts that produce the plots for the article.


***plot_data*** folder contains the data that is used to produce the final plots, and example plots in ***pdf*** format.


If you have any questions regarding the data, you should inspect the corresponding ***./raw_data/%experiment_name%/\*.Rmd***  R script that is used to produce the data file by processing raw data.

Note: The scripts are also available under ***plot_data*** folder. If you want to reproduce plots, you should run the scripts under ***raw_data*** folder, because the scripts under ***plot_data*** might not produce plots, they are put there for demonstration purposes.
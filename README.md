# R_learning
getwd()    #get your working directory
#if you donot know your working directory, it causes trouble when you want to read or edit some file
    #eg: read.csv("filename.csv")    #if the filename.csv is not in your working diretory, this line is wrong. So you have two options to be chose, (1) move your file in your working directory or change your working directory in the file directory;
setwd()    #set working directory in latest directorty

Working your R scripts in R console
Save your script in your WD 
dir()    #find your script file
source("filename.R")    #load your script in your R console

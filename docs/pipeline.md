# Oultine a Pipeline
In this assignment, you will develop a birds-eye view of your analysis project. Y
ou can do this for a research project that you are currently working on, or one that you have completed already. 
Ideally, this lays the basis for your final project, but this is not required.

The current goal is to layout the different steps in an analysis pipeline for your project. This should be schematic.

At the coarsest level, your pipeline includes steps for 
1. reading the data
1. preprocessing
1. analyzing
1. visualizing

but your assignment is to fill in more detail.

You will do this in two complementary formats. 

* The first is a PowerPoint (or Visio or Word) to generate a block diagram or flow-chart, explaining the overall pipeline of your project.
Add this document to the _docs/_ folder of this module. 


* The second format consists of M-files that you create. 
You start from the _read.m_ ,_preprocess.m_, _analyze.m_, and _visualize.m_ m-files that are in the _code/_ folder. But you can add files, for instance to define additional functions, or you can rename these 
files to make their filenames reflect better what goes on inside. 


*** Note that none of this involves writing working code. ***

Instead, in each of these m-files you only write the documentation of the code that you plan to write.

For instance, in the _read.m_ file, you describe your data, briefly in two or three sentences. 
Then describe what the input and out variables are for your _read_ function. 
Maybe a filename as input, and a big ND array of EEG recordings, or reaction times as output? 
Describe what kind (type) of variables you will use (a struct, a table, an ND array) and explain why. 


In the _preprocess.m_ file you follow the same strategy. Describe what goes into this function and what comes out. 
Which parameters need to be set? When is a value considered an outlier and removed from the data? 

In the _analyze.m_ file you describe what kind of analysis you would like to do. Structure the file with cells to make the logical sequence of steps clear. 
if your analysis will require additional functions, add those as m-files to, and write their documentation. 
If you use an external toolbox for most of the preprocessing or even core analysis, don't bother describing exactly what it does; or motivating its input/output. Just treat the external toolbox as a built-in Matlab function that is beyond your control. 


The _visualize.m_ file documents the ultimate results figure that you will generate. This will be a function, so what kind of input will this function receive? 

It is perfectly fine if some stages are still unclear - just recognizing that there are stages is important! The goal is for you to take a step back and think about the code without writing any. 
Once you have completed your pipeline outline, add all relevant m-files to this module's repository, commit, and push to GitHub.



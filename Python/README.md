# Cocaine Dependence

Code and data for reproducing key results in the paper "[Utility of Machine-Learning Approaches to Identify Behavioral Markers for Substance Use Disorders: Impulsivity Dimensions as Predictors of Current Cocaine Dependence](http://journal.frontiersin.org/article/10.3389/fpsyt.2016.00034/full)".

Installation
------------

Run the following in a shell:

```shell
git clone https://github.com/CCS-Lab/cocaine-dependence.git
cd cocaine-dependence/Python
conda env create -f environment.yml
source activate cocaine-dependence
```

If you encounter a clear bug, please file a [minimal reproducible example](http://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example) on [github](https://github.com/CCS-Lab/cocaine-dependence/issues).

Getting started
---------------

To achieve the original results, run the following in a shell:

```shell
python analysis.py
```

or, 

```shell
python easy_glmnet.py
```

Citation
--------

If you found our work useful please cite us in your work:

```
@Article{10.3389/fpsyt.2016.00034,
         Author = {Ahn, Woo-Young and Ramesh, Divya and Moeller, Frederick Gerard and Vassileva, Jasmin},
         Title = {Utility of Machine-Learning Approaches to Identify Behavioral Markers for Substance Use Disorders: Impulsivity Dimensions as Predictors of Current Cocaine Dependence}, 
         Journal = {Frontiers in Psychiatry}, 
         Volume = {7}, 
         Pages = {34}, 
         Year = {2016}, 
         URL = {http://journal.frontiersin.org/article/10.3389/fpsyt.2016.00034}, 
         DOI = {10.3389/fpsyt.2016.00034}, 
         ISSN = {1664-0640},   
}
```

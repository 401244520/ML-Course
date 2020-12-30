# LDA 线性判别分析

## Inrtoduction
This is a course exercise, applying LDA in single cell Hi-C data.

## Prerequisites
- python 3.7
- numpy
- pandas
- matplotlib
- sklearn

## Rerduction
### Three type cell lines single cell Hi-C data with labels, each of them include 77 samples.The yellow represent OSN cells,purple represent mESC cells, while green represent NMuMG cells, all of them are mapped to mm10 refrence genmome and binned in a specific way.
![result](https://github.com/401244520/ML-Course/blob/master/reduction.png?raw=true)

## Classifier
### We use different amount of sample to fit the classifier, here we use anothor test sample to evaluate the classifier.The value 0 and value 1 represent the test sample(which are mESC cells) was classified as mESC and NMuMG cell, respectively.
![result](https://github.com/401244520/ML-Course/blob/master/202020.png?raw=true)
![result](https://github.com/401244520/ML-Course/blob/master/777777.png?raw=true)
![result](https://github.com/401244520/ML-Course/blob/master/2007799.png?raw=true)

## Usage
### python classify.py 



## Content WIP

**NOTE**: This repository is still in the works

-------------------------

# Classification methods used on new data sources

This repository is a companion [to the online handbook](https://unstats.un.org/wiki/display/GWGSD/Handbook+on+utilising+new+data+sources+in+the+production+of+consumer+price+statistics) developed by the [UN Task Team on Scanner data](https://unstats.un.org/bigdata/task-teams/scanner/index.cshtml) to guide National Statistical Offices (NSOs) in the implementation of new data sources such as transaction data and web scraped data in the production of consumer price statistics -- specifically to classification methods applicable on this data. Thus this repository aims to hosts standardized code, public demonstration datasets (where applicable), and notebooks -- that NSOs can review as a companion to the material written in the [Classification section of the online handbook](https://unstats.un.org/wiki/display/GWGSD/Classification). It also is the storage location of some key artifacts that workstream developing classification used throughout the guidance (such as diagrams).

## Folder structure

The repository is structure around the following structure

```
├── data                    # Placeholder folders for demo data used in the repository
│   ├── raw                 # For raw data
│   └── final               # Cleaned data for use in the example notebooks
├── notebooks               # Exploration notebooks demonstrating the various classification methods
└── docs                    # Documentation supporting this repository
    └── images              # Images and diagrams
```

## Note on Programming Language use

Note - while notebooks as well as code in this repository is written primarily in Python, there is no 'correct' programming language for classification or other work NSOs could do. Classification workstream members chose Python to demonstrate classification methods as Python is a very popular language for Data Science and especially Machine Learning (Method 4), can be written in a quite easy to read syntax, as well as that based on workstream member experience, many NSOs utilize Python for their classification work. NSOs should however choose a programming language as they see fit, such as depending on their preference those their officers and ability to maintain the code base. 

For contributors who want to contribute in another language, please feel free to do so! Note that notebooks (such as in R markdown) can also be saved in the `/notebooks/` folder.
# GSU_EffectiveArguments

This readme file was generated on 2022-30-06 by Nikita Tejwani.  It was last updated on 2022-30-06.
The template for this file was provided by Cornell University's Research Data Management Service Group: https://cornell.app.box.com/v/ReadmeTemplate


### GENERAL INFORMATION

Title of Dataset: Predicting Effective Arguments

Co-Investigator Information
Name: Nikita Tejwani
ORCID: 0000-0002-6493-6145
Institution: Teachers College, Columbia University
Email: nt2590@tc.columbia.edu

Co-Investigator Information
Name: Wendy Weng
ORCID:
Institution: 
Email: 

Co-Investigator Information
Name: Mark Mahasandana
ORCID:
Institution: 
Email: 

The dataset was provided by Georgia State University and The Learning Agency Lab through the Kaggle competition "Feedback Prize - Predicting Effective Arguments".  The competition can be found at this link: https://www.kaggle.com/competitions/feedback-prize-effectiveness/overview
    
The data was collected in the United States from essays written by students in grades 6-12.  The dates and location(s) of collection are unknown to the team.


### SHARING/ACCESS INFORMATION

Licenses/restrictions placed on the data: 
- https://opensource.org/licenses/MIT
- In accordance with competition rules, the team agrees to "use reasonable and suitable measures to prevent persons who have not formally agreed to [competition] Rules from gaining access to the Competition Data.

Links/relationships to ancillary data sets: The file 'dtm.csv' contains a document term matrix derived from the original dataset.

Recommended citation for this dataset: Georgia State University. (2022). Predicting Effective Arguments. *Kaggle*. Retreived from https://www.kaggle.com/competitions/feedback-prize-effectiveness/data


### DATA & FILE OVERVIEW

File List:
- README.md: current file
- ExploratoryAnalysis.ipynb: exploration of Kaggle dataset (described below) through descriptive statistics and associated visualizations
- TrainToDTM.ipynb: create a document term matrix from the Kaggle dataset
- dtm.csv: document term matrix for the Kaggle dataset, indexed by discourse ID
- DTM_Visualizations.ipynb: visualizations for effective, adequate, and ineffective discourse, derived from the document term matrix and lexical measures

Additional related data collected that was not included in the current data package: The Kaggle dataset is not included in the current data package due to the competition rules.


### METHODOLOGICAL INFORMATION

Description of methods used for collection/generation of data: <include links or references to publications or other documentation containing experimental design or protocols used in data collection>

Methods for processing the data: <describe how the submitted data were generated from the raw or collected data>

Instrument- or software-specific information needed to interpret the data: <include full name and version of software, and any necessary packages or libraries needed to run scripts>
- @article{harris2020array,
    title = {Array programming with {NumPy}},
    author = {Charles R. Harris and K. Jarrod Millman and St{\'{e}}fan J.
                 van der Walt and Ralf Gommers and Pauli Virtanen and David
                 Cournapeau and Eric Wieser and Julian Taylor and Sebastian
                 Berg and Nathaniel J. Smith and Robert Kern and Matti Picus
                 and Stephan Hoyer and Marten H. van Kerkwijk and Matthew
                 Brett and Allan Haldane and Jaime Fern{\'{a}}ndez del
                 R{\'{i}}o and Mark Wiebe and Pearu Peterson and Pierre
                 G{\'{e}}rard-Marchant and Kevin Sheppard and Tyler Reddy and
                 Warren Weckesser and Hameer Abbasi and Christoph Gohlke and
                 Travis E. Oliphant},
    year = {2020},
    month = sep,
    journal = {Nature},
    volume = {585},
    number = {7825},
    pages = {357--362},
    doi = {10.1038/s41586-020-2649-2},
    publisher = {Springer Science and Business Media {LLC}},
    url = {https://doi.org/10.1038/s41586-020-2649-2}
    }
- @article{Hunter:2007,
    Author = {Hunter, J. D.},
    Title = {Matplotlib: A 2D graphics environment},
    Journal = {Computing in Science \& Engineering},
    Volume = {9},
    Number = {3},
    Pages = {90--95},
    abstract = {Matplotlib is a 2D graphics package used for Python for
    application development, interactive scripting, and publication-quality
    image generation across user interfaces and operating systems.},
    publisher = {IEEE COMPUTER SOC},
    doi = {10.1109/MCSE.2007.55},
    year = 2007
    }
- @software{lex,
    author = {Shen, Lucas},
    doi = {10.5281/zenodo.6607008},
    license = {MIT license},
    title = {{LexicalRichness: A small module to compute textual lexical richness}},
    url = {https://github.com/LSYS/lexicalrichness},
    year = {2022}
    }
- @inproceedings{sklearn_api,
    author = {Lars Buitinck and Gilles Louppe and Mathieu Blondel and
               Fabian Pedregosa and Andreas Mueller and Olivier Grisel and
               Vlad Niculae and Peter Prettenhofer and Alexandre Gramfort
               and Jaques Grobler and Robert Layton and Jake VanderPlas and
               Arnaud Joly and Brian Holt and Ga{\"{e}}l Varoquaux},
    title = {{API} design for machine learning software: experiences from the scikit-learn
               project},
    booktitle = {ECML PKDD Workshop: Languages for Data Mining and Machine Learning},
    year = {2013},
    pages = {108--122},
    }
- @book{Python 3 Reference Manual, 10.5555/1593511,
    author = {Van Rossum, Guido and Drake, Fred L.},
    title = {Python 3 Reference Manual},
    year = {2009},
    isbn = {1441412697},
    publisher = {CreateSpace},
    address = {Scotts Valley, CA}
    }
- @software{reback2020pandas,
    author = {The pandas development team},
    title = {pandas-dev/pandas: Pandas},
    month = feb,
    year = 2020,
    publisher = {Zenodo},
    version = {3.10.5},
    doi = {10.5281/zenodo.3509134},
    url = {https://doi.org/10.5281/zenodo.3509134}
- @article{Waskom2021,
    doi = {10.21105/joss.03021},
    url = {https://doi.org/10.21105/joss.03021},
    year = {2021},
    publisher = {The Open Journal},
    volume = {6},
    number = {60},
    pages = {3021},
    author = {Michael L. Waskom},
    title = {seaborn: statistical data visualization},
    journal = {Journal of Open Source Software}
    }
- @software{wordcloud,
    author = {Mueller, Andreas},
    license = {MIT license},
    title = {{word_cloud}},
    url = {https://github.com/amueller/word_cloud},
    year = {2018}
    }
    

Standards and calibration information, if appropriate: 

Environmental/experimental conditions: 

Describe any quality-assurance procedures performed on the data: 

People involved with sample collection, processing, analysis and/or submission: 


### DATA-SPECIFIC INFORMATION FOR: [FILENAME]
<repeat this section for each dataset, folder or file, as appropriate>

Number of variables: 

Number of cases/rows: 

Variable List: <list variable name(s), description(s), unit(s) and value labels as appropriate for each>

Missing data codes: <list code/symbol and definition>

Specialized formats or other abbreviations used: 
# Folder structure template for a Data science thesis

This is the basic folder structure I want to use for my data science thesis - let's see whether I'll stick to it. :-)

## Structure

### The Document
The `00_Document` folder is supposed to contain the written thesis. I included a Latex [template](https://www.sharelatex.com/project/51fa85c3db89c3c351085071) by [sharelatex.com](https://www.sharelatex.com).

### The Data science
In the `01_Data-science` folder the data magic will happen. I used the folder structure proposed by [Matthew Gentzkow](https://people.stanford.edu/gentzkow) and Jesse M. Shapiro in their fabulous publication *"Code and Data for the Social Sciences: A Practitioner's Guide"*, (see [html](http://web.stanford.edu/~gentzkow/research/CodeAndData.xhtml) and [pdf](http://web.stanford.edu/~gentzkow/research/CodeAndData.pdf)). They propose a fully automated workflow which is triggert by a shell script (Example see in subfolder [`/01_Data-science/01_build-data-set/02_code`](https://github.com/nhukretep/data-thesis-template/tree/master/01_Data-science/01_build-data-set/02_code)).

### The Data
A backup of the original data sets can be found in the `02_Data-source` folder. This is in case something goes wrong while performing data science.

### The Literature
Finally, the `03_Literature` folder is supposed to contain all the literature that I use.

## Whats next?

### Top-level folder connections

I am not sure yet to which extend I should connect the top-level folders. Should the .tex file in the `00_Document` folder use output-files directly from the `01_Data-science` folder or is it better to leave them seperated? Same goes for the original data: Should my shell script copy them into the `01_Data-science` folder automatically? Let'see.

### Comments and suggestions
Please let me know if you have any comments or suggestions.
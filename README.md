# Molecular Biology Projects

The field of molecular biology involves a LOT of data analysis! Here I share with you all a few projects I worked on and analyzed using R or Excel. I hope you find this easy to navigate and use for your own personal means of data analysis too!

**Note: All of the html files are too big to view from Github. I recommend downloading the raw html file on Github in order to view it (otherwise you can view the .rmd file in the Project folders as well)!**


## [Project: Proteomics Analysis from Mass Spectrometry Data Part 1](https://github.com/tamxto/MolecularBiologyProjects/blob/main/Projects/Project_ProteomicsAnalysis/ET_Analysis.html)

This project focuses on analysis of proteomics data to identify protein expression patterns, interactions with molecular networks, etc. to make comparative conclusions between samples. 

I had designed this experiment, prepped isolated protein samples in the lab, then sent them to mass spectrometry for protein identification/quantification. Super cool getting to see results come back beginning from wet lab and ending with dry lab techniques. 

This first part of the analysis works on inspecting, cleaning, and preprocessing the dataset.

<img align="center" src="MainPageImages/NETsIFpng.png" width="300"/> <img align="center" src="MainPageImages/PCA.png" width = "320"/>


## [Project: Proteomics Analysis from Mass Spectrometry Data Part 2](https://github.com/tamxto/MolecularBiologyProjects/blob/main/Projects/Project_ProteomicsAnalysis/ET_Analysis_Pt2.html)

In this part of the project, we use the preprocesssed data and analyze the relative protein abundances with different data visualization methods.

<img align="center" src="MainPageImages/volcano_example.png" width = "320"/>


## [Project: Sequence Alignment, Preprocessing, and Quality Control of scRNAseq Data](https://github.com/tamxto/MolecularBiologyProjects/blob/main/Projects/Project_SequencingQualityControl/Project_scRNAseqQualityControl.html)

Here I go over what to do when you get back raw files from the sequencing core! How to download/upload the large data sets (Unix/Linux Command line), align the sequences, check for quality, then preprocess and normalize the data in R.

This was probably what I struggled with the most when I first started since it's a bunch of "figuring out what works with your laptop/PC" kinda deal. Otherwise, everything is straightforward once you have everything downloaded and the code ready to go!

<img align="center" src="MainPageImages/featurecounts.png" width = "200"/> <img align="center" src="MainPageImages/tsne.png" width = "400"/>


## [Project: Expanding Acne Dataset](https://github.com/tamxto/MolecularBiologyProjects/blob/main/Projects/Project_ExpandingAcneDataset/ExpandingAcneData.html)

For this project, I'm working on expanding a publicly available dataset based off a paper that compared normal vs. acne skin using single-cell RNA sequencing (scRNAseq). scRNAseq is an effective tool for analyzing genetic and molecular profiles of individual cells. This allows us to study changes in specific cell types based on the types of disease lesions. We can know which genes are differentially expressed in each cell type and each condition. In this case, we can know how gene expression differs between cell types in normal vs. acne skin lesions. It's a powerful way for elucidating unknown pathogeneses and identifying potential targets for therapeutics.

The publicly available data can be found [here](https://github.com/modlab246/scRNAacne).

The paper I'm referencing is cited here: Tran H. Do et al. ,TREM2 macrophages induced by human lipids drive inflammation in acne lesions.Sci. Immunol.7,eabo2787(2022).DOI:10.1126/sciimmunol.abo2787.

Do, Tran H. et al. already did quality control and integrated the data, but my goal is to expand the lymphocyte dataset.

Originally, the authors named 5 cell clusters in this dataset, however, I plan to figure out if we can expand it into more cell types so that the data is more specific for generating hypotheses (as shown below). This will allow researchers to more specifically narrow down where a gene of interest is being expressed. After expanding the dataset, I plan to analyze the single cell data in through different graphical representations (shown in the next project).

<img align="center" src="MainPageImages/OldUMAP.png" width="200"/> <img align="center" src="MainPageImages/NewUMAP.png" width="250"/>


## [Project: Graphical Analysis of New Acne Dataset](https://github.com/tamxto/MolecularBiologyProjects/blob/main/Projects/Project_AcneGraphicalAnalyses/AcneGraphicalAnalyses.html)

This project utilizes the newly expanded lymphocyte dataset constructed from the "Expanding Acne Dataset" project. 

In this project, I demonstrate how to use various packages and generate different types of visual analyses such as dot plots, violin plots, bar plots, etc. Furthermore, I include other methods of analysis with single cell data such as gene ontology (EnrichR included), subsetting, etc. 

These are fundamental packages to understand how we can analyze single cell sequencing data. It's definitely very powerful!

<img align="center" src="MainPageImages/proportion_cells.png" width = "200"/> <img align="center" src="MainPageImages/Th17volcanoplot.png" width = "235"/> 


## [Project: Graphical Analysis of New Acne Dataset Part 2](https://github.com/tamxto/MolecularBiologyProjects/blob/main/Projects/Project_AcneGraphicalAnalyses_Part2/Project_AcneGraphicalAnalyses_Part2.html)

Here we explore pseudotime trajectories and cell-cell interactions/communications. You can get a bunch of information from doing these analyses. In this project, I go over a few graphs and information we can generate from monocle3 and CellChat.

<img align="center" src="MainPageImages/ccl5_ccr4 copy.png" width="400"/>


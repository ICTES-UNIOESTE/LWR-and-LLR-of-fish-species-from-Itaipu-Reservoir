This repository provides the data and annotated R scripts necessary to replicate the analyses presented in the paper:

“Length–weight and length–length relationships of freshwater fish species caught by professional fishermen in the Itaipu Reservoir, Paraná River basin, Brazil”

The repository includes:

📂 Excel spreadsheets with raw data for a fish species (_Acestrorhynchus lacustris_) used as example;

📄 Detailed R Markdown (.Rmd) and HTML (.html) files that guides users through the process of:

 -Fitting Length–Weight Relationships (LWR files)
 
 -Fitting Length–Length Relationships (LLR files)
 
 Each file contains methods for:

 -Detecting and removing outliers

 -Adjusting linear models

 -Testing for sexual dimorphism using ANCOVA

 -Exporting results as .xlsx and .png files
 
⚠️ Note: The scripts are set to save results to the user’s Desktop on Windows. If you are using macOS or Linux, you’ll need to adjust the desktop_path accordingly.

The purpose of this repository is to promote reproducibility and offer a learning resource for fisheries biologists and quantitative ecologists working with morphometric relationships in fish populations.

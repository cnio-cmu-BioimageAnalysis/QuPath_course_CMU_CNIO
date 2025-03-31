# QuPath Course - Confocal Microscopy Unit at CNIO

This is a repository with the guide and datasets created for a QuPath course in the Confocal Microscopy Unit at CNIO. This course covers image analysis for brightfield and fluorescence images.

During this course, you will learn to use QuPath from the most basic tasks to some complex workflow, with practical examples, using microscopy datasets.

## Contents

- **Documents folder**: Contains a PDF file with a presentation explaining basic concepts before starting with QuPath, and a step-by-step guide to complete all the practical exercises of this course.
- **Datasets**: All the datasets used during this course are uploaded to Google Drive and can be downloaded by accessing the URL contained inside `Datasets download.txt`.

## Exercises

1. **Brightfield Images Analysis**
   - Exercise 1: `Positive & Negative cells Analysis.zip`. You will learn to deconvolve stainings on a brightfield image, to detect a tissue, to detect cells and to classify them.
   - Exercise 2: `RNAScope Detection.zip`. You will learn to analyze spots in DAB staining after staining deconvolution, tissue detection and cell detection.

2. **Fluorescence Images Analysis**
   - Exercise 3: `endothelial_analysis.zip`. You will learn how to perform an endothelial analysis using pixel classifiers in a fluorescence image. You will learn how to generate a script for batch analysis of a dataset.
   - Exercise 4: `spatial_analysis.zip`. You will learn how to detect cells on a fluorescence image using QuPath's threshold-based cell detection and with deep learning tool [Cellpose](https://github.com/MouseLand/cellpose).
     You will learn to detect tumor region inside the tissue. You will learn to classify cells and to calculate distances from cells to tumor and from a cell class to other cell classes.

## Getting Started

1. Download the datasets from [here](https://drive.google.com/drive/folders/13JEtxtspc8KR-JfI_tGM0_K2-m4Xv80R?usp=drive_link).
2. Download presentation from [here](https://github.com/cnio-cmu-BioimageAnalysis/QuPath_course_CMU_CNIO/blob/main/Documents/Introduction_to_Qupath_CNIO.pdf).
3. Download course guide from [here](https://github.com/cnio-cmu-BioimageAnalysis/QuPath_course_CMU_CNIO/blob/main/Documents/Qupath%20Guide_definitive.pdf).
4. Visualize the entire `Introduction_to_Qupath_CNIO.pdf`.
5. Uncompress datasets. They should be four in total.
6. Follow the step-by-step guide `Qupath Guide_definitive.pdf` to complete the exercises.

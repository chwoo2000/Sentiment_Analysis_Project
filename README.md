# Sentiment Analysis of Social Media Posts: A Literature Review

## Project Overview

This project provides a systematic literature review (SLR) of sentiment analysis techniques applied to social media data. It emphasizes machine learning and NLP methods, highlighting methodologies, findings, and research gaps. The review examines recent studies to understand the current state of sentiment analysis research and identify areas for future work. Key areas covered include:

*   Machine Learning and Deep Learning approaches
*   Hybrid models combining lexicon-based and machine learning techniques
*   Challenges related to multilingual sentiment analysis, real-time processing, and handling contextual nuances

## Repository Contents

This repository contains the following files:

*   `Sentiment Analysis of Social Media Posts.tex`: The LaTeX source file for the literature review document.
*   `references.bib`: The BibTeX file containing all cited references.
*   `Sentiment Analysis of Social Media Posts.pdf`: The compiled PDF of the literature review document.
*   `README.md`: This file, providing an overview of the project and instructions for local compilation.
*   `Literature Review.pptx`: The Powerpoint Presentation slides of the Literature Review.
*   `Literature Review.xls`: This excel file contains the Literature Review analysis and findings.

## Steps to Compile the Document Locally

To compile the LaTeX document locally, follow these steps:

1.  **Install a LaTeX Distribution:** Ensure you have a LaTeX distribution installed on your system (e.g., MikTeX for Windows, TeX Live for Linux, or MacTeX for macOS).

2.  **Install Required Packages:** Make sure you have the necessary LaTeX packages installed. The main packages used in this project are:

    *   `graphicx`
    *   `amsmath`
    *   `amssymb`
    *   `booktabs`
    *   `tabularx`
    *   `ragged2e`
    *   `longtable`
    *   `hyperref`
    *   `filecontents`

    You can install these packages using your LaTeX distribution’s package manager. For example, in TeX Live, you can use `tlmgr`:

    ```
    tlmgr install graphicx amsmath amssymb booktabs tabularx ragged2e longtable hyperref filecontents
    ```

3.  **Compile the LaTeX Document:** Open a command prompt or terminal, navigate to the directory where you saved the `main.tex` and `references.bib` files, and run the following commands in sequence:

    ```
    pdflatex main.tex
    bibtex main
    pdflatex main.tex
    pdflatex main.tex
    ```

    *   The first command compiles the `main.tex` file.
    *   The second command generates the bibliography using BibTeX based on the `references.bib` file.
    *   The third and fourth commands compile the `main.tex` file again to include the bibliography and any cross-references.

4.  **View the Compiled PDF:** After successful compilation, you will find the `main.pdf` file in the same directory. Open this file to view the compiled literature review document.

## Key Studies and Techniques

The literature review covers the following key studies and techniques:

*   **Borkar and Kolhe (2019):** Explored machine learning techniques for sentiment analysis on Twitter data, highlighting SVM's superior performance.
*   **Kim, Chen, and Park (2021):** Analyzed deep learning models across multiple platforms, noting Bi-LSTM's effectiveness in handling language variability.
*   **Gupta and Reddy (2022):** Surveyed sentiment analysis techniques, emphasizing the benefits of hybrid models and deep learning advancements.
*   **Lopez, Singh, and Kim (2021):** Investigated sentiment analysis of health-related social media posts using LSTM networks, with insights into vaccine hesitancy.
  *   **Obulapuram et al. (2023):** The review notes that the accuracy performance of lexicon-based and machine learning techniques is similar.
  *   **Wang et al. (2023):** Highlighted that Text outperforms images in unimodal sentiment recognition

## Resources

*   **Borkar and Kolhe (2019):**  \href{https://www.ijetir.org/viewpaper.php?title=A-Review-on-Sentiment-Analysis-of-Twitter-Data-Using-Machine-Learning-Techniques}{International Journal of Emerging Technologies and Innovative Research}
*   **Kim, Chen, and Park (2021):** \href{https://ieeexplore.ieee.org/document/947735}{IEEE Access}
*   **Gupta and Reddy (2022):** \href{https://dl.acm.org/doi/abs/10.1145/3453489}{ACM Computing Surveys}
*   **Lopez, Singh, and Kim (2021):** \href{https://pubmed.ncbi.nlm.nih.gov/33186914/}{Journal of Biomedical Informatics}
*   **Obulapuram et al. (2023):** \href{https://ieeexplore.ieee.org/document/10100189}{IEEE Xplore}
*   **Wang et al. (2023):** \href{https://dl.acm.org/doi/abs/10.1145/3573942.3573947}{ACM Digital Library}

## GitHub Repository

This project is synchronized with a private GitHub repository. The repository includes the LaTeX source files, the compiled PDF, the bibliography file, and this README file.

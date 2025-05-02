# BEE-102-Spring-2025-Assignment
CSE Assignment: DNA Fragment Analysis, Rescaling, Markov Models, PCA, and More
This repository contains Python scripts and documentation for completing the CSE assignment, which includes tasks such as fragment length frequency analysis, rescaling, building a Markov transition matrix, converting multi-line FASTA to single-line, implementing the Viterbi algorithm, generating a V-plot, and performing Principal Component Analysis (PCA). Below is a detailed description of each task and instructions for running the code.
Prerequisites
Ensure you have Python 3.8+ installed along with the following libraries:

numpy
pandas
matplotlib
seaborn (for enhanced plotting)
scipy (for statistical operations)
gzip (for handling compressed files)

Install dependencies using:
pip install numpy pandas matplotlib seaborn scipy

Additionally, download the required data files:
note that mapped.bed and query.bed files are not uploded in this repo due to their size. you will find here [query.bed.gz](https://figshare.com/ndownloader/files/53306780?private_link=727f8d920a1b8415f09a)  and [mapped.bed.gz](https://figshare.com/ndownloader/files/49307590?private_link=972ecdfe69d6ce038ca0)
Place these files in a data/ directory within the project folder.


Tasks and Descriptions  [click here](https://github.com/satyanarayan-rao/BEE-102-2025-Assignment)

Notes
Ensure all data files are placed in the data/ directory before running the scripts.
Output files (plots and text) are saved in the output/ directory, which will be created automatically if it doesn't exist.
The scripts assume the data files are in the correct format as provided. Verify file integrity if errors occur.
For the Viterbi algorithm, the implementation prioritizes correctness over optimization, as the maximum likelihood path may trivially be all 'E' states.
PCA implementation follows the Nature Primer, ensuring the scatter plot and PC1 projection patterns are similar to Figure 1a and 1c, though exact data points may vary slightly.

Contact
For issues or clarifications, please contact the course instructor or refer to the assignment guidelines.


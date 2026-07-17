## Reproduction record

**1. Directory Structure & Relative Paths**
To guarantee that the relative paths in the `find_exam_data()` helper function resolve correctly, extract the submission archive into a single working directory containing the following exact structure:

    ASESII_24A02_ProjectQuiz1_Group05/
    ├── Group05_ProjectQuiz1.Rmd
    ├── Group05_ProjectQuiz1.pdf
    ├── references.bib
    ├── README.txt
    └── data/
        └── fat.csv

**2. Clean Environment Initialization**
1. Launch a completely clean R session (e.g., by opening a new RStudio Project in the `ASESII_24A02_ProjectQuiz1_Group05` directory). Do not load any previous `.RData` workspaces. 
2. Ensure the strictly required packages (`tidyverse`, `glmnet`, `broom`, `knitr`) are installed. 
3. Execute the rendering process via the console: `rmarkdown::render("Group05_ProjectQuiz1.Rmd")` or by using the RStudio "Knit" button. 
4. The environment snapshot, including package versions and system information, is automatically appended to the end of this report via `sessionInfo()`.

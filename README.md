Directory Structure
--------------------

    .
    ├── config  <- any configuration files, parameters and output results
    ├── data
    │   ├── 01_raw <- original unmodified data acting as source of truth and provenance
    │   ├── 02_interim <- data in intermediate processing stage
    │   ├── 03_processed <- data after all preprocessing has been done
    │   ├── 04_models <- compiled model .pkl or HDFS or .pb format
    │   ├── 05_model_output <- output model
    │   ├── 06_reporting <- data for reporting   
    │   └── 07_predictions <- predictions output data
    ├── notebooks <- jupyter notebooks for exploratory analysis and explanation "date-cs-title.ipynb"
    ├── references  <- usage documentation or reference papers
    ├── results <- generated project artefacts eg. visualisations or tables
    └── src - scripts for processing data eg. transformations, dataset merges etc.
    │   ├── d01_raw <- original unmodified data acting as source of truth and provenance
    │   ├── d02_interim <- data in intermediate processing stage
    │   ├── d03_processed <- data after all preprocessing has been done
    │   ├── d04_models <- scripts for generating models
    │   ├── d05_model_output <- output model
    │   ├── d06_reporting <- data for reporting
    │   ├── d07_visualization <- scripts for visualisation during EDA, modelling, error analysis etc. 
    │   ├── d08_predictions <- predictions output data 
    │   └── tools <- general tools
    ├── LICENSE
    ├── README.md
    |--- requirements.txt <- file with libraries and library versions for recreating the analysis environment
   

# Illumina_ReadBased_metagenomics
Basic Metagenomics analyses for short pair-end Illimina reads

## Create project directories
This project environment requires the following directories: `resources/Data/` `resources/Databases` `resources/Logs` `resources/Outputs` `results/`.
The script `create_env_directories.sh` will create all this directories: 
run this   `bash create_env_directories.sh`

## Link Data and Databases to Projects directories
Bring the data you want to analyze to the directory `resources/Data/` and the databases required (e.g., kraken2_db) to `resources/Databases/`

## Test the snakemake script: 
Move to `workflow/` directory and run the following code to test the script:
`
conda activate snakemake
snakemake -n --use-conda
`



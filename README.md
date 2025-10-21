# Buscophy pipeline for generation of phylogenetic trees from busco genes

create base conda environment with
`conda env create --file base_snakemake.yml`


I have tested this with conda and singularity. It should also work with apptainer
`snakemake --use-conda --cores 40 #--conda-frontend conda`
`snakemake --cores 40 --use-singularity --singularity-args="--cleanenv --no-home --bind /path/to/cwd/"`



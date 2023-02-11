# GSFM_AnalystForecasts


create new environment without file: mamba create -n "name (without "")" python=3.10
create environment file from .yml: mamba env create -f environment.yml
Update the environment.yml file: mamba env export --from-history>environment.yml
update your own environment with the missing packages: mamba env update --file environment.yml --prune
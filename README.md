# Querying Gaia tables using astroquery

The notebook in this repo shows how to use [astroquery](https://astroquery.readthedocs.io/en/latest/) to:

- Select a list of sourceids from one of the [variability tables](https://gea.esac.esa.int/archive/documentation/GDR3/Gaia_archive/chap_datamodel/sec_dm_variability_tables/)
- Obtain the photometric data through the datalinks interface
- Retrieve the variability features 

To install the dependencies and run the notebook I suggest creating a conda environment

    conda create -n gaia jupyter matplotlib pandas astropy astroquery -c conda-forge
    conda activate gaia
    jupyter notebook

Or a regular python environment.

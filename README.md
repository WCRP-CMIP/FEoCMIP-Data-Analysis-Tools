# Fresh Eyes on CMIP - Aggregating Data Analysis Tools

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/WCRP-CMIP/FEoCMIP-Data-Analysis-Tools/HEAD)

This repository contains climate data analysis tools for CMIP models, contributed by members of Fresh Eyes on CMIP.

We aim to provide a set of tools for analysing CMIP data that can be reused by the wider community. Given the inherent complexity of climate data analysis, we take a practical approach: the use cases and workflows are designed to be simple enough to reproduce while remaining extensible to more advanced applications. Launch the [Binder](https://mybinder.org/v2/gh/WCRP-CMIP/FEoCMIP-Data-Analysis-Tools/HEAD) to get started.

This repository focuses on [Python](https://www.python.org/) and standard climate data analylsis tools like [xarray](https://xarray.dev/).

## Data access

[Acquiring CMIP data](https://wcrp-cmip.github.io/cmip7-guidance/docs/CMIP7/Guidance_for_users/#1-accessing-cmip7-data) is not straightforward. CMIP data is stored in [NetCDF](https://wcrp-cmip.github.io/cmip7-guidance/docs/CMIP7/Guidance_for_users/#4-cmip7-data-format) format, which requires specialised libraries for effective data handling.

Data can be accessed either by downloading NetCDF files or through remote data access. For lightweight workflows, remote access avoids unnecessary downloads. However, for more data-intensive workflows, remote access may be inefficient, making it necessary to download the NetCDF files.

See the [example notebook on data access](main.ipynb) for an illustration of both approaches.

## Data analysis tools

... we need to think of use cases ...

## Contributor Information and Affiliations

- Ezequiel Cimadevilla, Instituto de Física de Cantabria, Spain
- Onur Karakus
- Naveen Senthil
- Nina Crnivec

### Previous contributors

- Keighan Gemmell, University of British Columbia, Canada 
- Júlia Crespin Esteve, Universitat de Barcelona, Spain
- Anja Katzenberger, Potsdam Institute of Climate Impact Research, Germany

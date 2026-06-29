This is a repository holding data of SNe Ia occuring in the Virgo Cluster and their host galaxies.

### raw_data/
Contains original light curve data downloaded from:
- LOSS / KAIT surveys
- LOWZ PS1 sample
- Pantheon+ auxiliary files
- Open Supernova Catalog
- other open source data publications

These files are unprocessed and may contain inconsistent formatting,  missing error values, and "BAD" data points

### photometry
This directory contains cleaned and homogenized SN photometry in SNANA format. Duplicate data points across sources were removed, "BAD" or non-detection 
points were removed and upper-limit points are indicated. Instrument/surveys were indicated if known. 

Note for pre-2000 supernovae, many SN had no available data that contained mag/flux errors. These are left as -999 (NaN) and should be estimated if used in 
light curve fitting pipeline. 

For pre-2000s raw data, please see https://github.com/lmenotti/virgo-snana, along with this info spreadsheet: https://docs.google.com/spreadsheets/d/1L9vTdwbA-fix6-kZjoUcZ8ZOfWbcPplP7jHP-OlQvo0/edit?gid=1711250567#gid=1711250567. 




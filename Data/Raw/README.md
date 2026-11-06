# Raw data

These files are not stored in this repository because of their size. Download each one into this folder without renaming it.

| File | Source | Link |
|---|---|---|
| `UADAggs_ent_sf_tract_v3_3.zip` | FHFA Uniform Appraisal Dataset Aggregate Statistics, Enterprise single-family, census tracts | https://www.fhfa.gov/sites/default/files/2024-12/UADAggs_ent_sf_tract_v3_3.zip |
| `ICPSR_141121-V3.6.zip` | Historic Redlining Indicator (Meier & Mitchell), openICPSR; free account required | https://www.openicpsr.org/openicpsr/project/141121/version/V3/view |
| `list1_2023.xlsx` | OMB 2023 county-to-metro delineation | https://www2.census.gov/programs-surveys/metro-micro/geographies/reference-files/2023/delineation-files/list1_2023.xlsx |

American Community Survey data is pulled automatically through the Census API on the notebook's first run, using the key stored in the `CENSUS_API_KEY` environment variable.

Data dictionaries: the [UAD Aggregate Statistics dictionary](https://fhfa.gov/document/uad-aggregate-statistics-data-file-dictionary.pdf) describes every field in the FHFA file.
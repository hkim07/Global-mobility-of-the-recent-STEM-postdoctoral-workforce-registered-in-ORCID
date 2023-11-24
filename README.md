# Global mobility of the recent STEM postdoctoral workforce registered in ORCID

This Github repository shares Jupyter notebooks and a data set "_dat_orcid_2022_postdoc_trajectories.csv.gz" containing selected postdoctoral researchers' career trajectories cleaned from ORCID's 2022 public data. This data set is used in "2_field_assignment_dimensions.ipynb" and "3_analysis.ipynb".

As part of the paper, the selected ORCID iDs' academic fields were inferred based on the publications in the Dimensions database. Therefore, a Dimensions API key is required to make all Jupyter notebooks fully operate. 

To load the data "_dat_orcid_2022_postdoc_trajectories.csv.gz", the following Python line can be used.

```
dat = pd.read_csv("_dat_orcid_2022_postdoc_trajectories.csv.gz", compression="gzip")
```

A preprint can be found at https://osf.io/preprints/socarxiv/cugv6/

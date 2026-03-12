This repository is used to hold all python geoprocessing code to run global inland desert wetlands calculations.
This repository does not store large geospatial datasets. Instead, it expects users to download required data separately and place them into a standardized local folder structure. It also expects the user to use ArcGIS Notebooks environment to run code. Data citations for datasets can be found in the supporting information section of the manuscript.
```
Expected Folder Stucture:
repo_root/
├── data/
│   ├── Global-AI_ET0_annual_v3/
│   ├── Global-AI_ET0_v3_annual
│   ├── GLWD_v2_0_combined_classes_tif/
│   └── GLWD_v2_0_combined_classes
└── outputs/
├── inland_desert_wetland_calc_script.ipynb
```

repo_root/ Project repository root. Users must use this data path as the `path_folder` attribute in first code block in order to run script.
data/ All input data required to run the scripts.
outputs/ All generated outputs produced by the scripts

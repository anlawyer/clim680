# Climate Data (CLIM 680)
Class work for Climate Data class at GMU. 

## Data set
I'm using data from the [ERA5 post-processed daily statistics reanalysis](https://cds.climate.copernicus.eu/datasets/derived-era5-single-levels-daily-statistics?tab=overview), specifically looking at the 2m temperature variable (`t2m`) for the max daily temperature recorded at 0.25° x 0.25° (atmosphere) / 0.5° x 0.5° (ocean waves) resolution around the entire globe. 

## Assignment 1
### Multi-panel monthly climatology map

This [project](https://github.com/anlawyer/clim680/blob/main/multipanel-climatology.ipynb) uses `xarray` and `cartopy` to create a facet grid of mean monthly max temperature across the globe: 

<img width="800" alt="image" src="https://github.com/user-attachments/assets/3ea5b104-3482-4a38-93ce-da9c5601135e" />

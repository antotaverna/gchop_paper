# Plots of GalaxyChop Paper

## df_stars.ipynb: Generates the pickle file of Stars DataFrame to make all plots.
## agmm_du.ipynb : Generate pickles of describe() output of all galxies Du.

## xy_plane.ipynb: Plot Spatial distribution of the galaxy
- Full Galaxy
- Spliting in components

## circ_plots.ipynb: Plot of dynamical space
- Energy vs Jz
- Pairplot of all dynamical properties
- Distributions of Circularity parameters

## read_agmm_du.ipynb: Read pickle files of AGMM decomposition of Du galaxies.

##  matrix_models.ipynb: Models Comparison

# Labels


|           | Label 0      | Label 1   | Label 2               | Label 3                |
|-----------|--------------|-----------|-----------------------|------------------------|
| Abadi     | Bulge        | Disk      | --                    | --                     |
| Threshold | Bulge        | Disk      | --                    | --                     |
| Cristiani | Bulge        | Disk      | --                    | --                     |
| KMeans    | Bulge        | Disk      | --                    | --                     |
| GMM       | Bulge        | Disk      | --                    | --                     |
| KMeans+3  | Bulge        | Thin Disk | Thick Disk            | --                     |
| GMM+3     | Bulge        | Thin Disk | Thick Disk            | --                     |
| KMeans+4  | Stellar Halo | Bulge     | Thin Disk             | Thick Disk             |
| GMM+4     | Stellar Halo | Bulge     | Thin Disk             | Thick Disk             |
| Auto GMM  | Stellar Halo | Bulge     | Thin Disk / Cold Disk | Thick Disk / Warm Disk |

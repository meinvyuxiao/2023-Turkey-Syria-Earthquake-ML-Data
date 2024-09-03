# 2023-Turkey-Syria-Earthquake-ML-Data
This is the clean and sorted data prepared for the classification model in the paper "Intelligent assessment of building damage of 2023 Turkey-Syria Earthquake by multiple remote sensing approaches".

Please refer to the paper for more details.

If you apply the data and methodology in this paper, please add the citation: 

Yu, X., Hu, X., Song, Y., Xu, S., Li, X., Song, X., Fan, X., & Wang, F. (2024). Intelligent assessment of building damage of 2023 Turkey-Syria Earthquake by multiple remote sensing approaches. npj Natural Hazards, 1(1). https://doi.org/10.1038/s44304-024-00003-0


We have processed 5 features to establish the machine learning model, i.e., Amplitude Dispersion Index (adi), Damage_Proxy_from_Sentinel (dpm), Damage_Proxy_from_ALOS (dpm_alos),  Normalized Difference Built-up Index (ndbi), and Peak ground acceleration (pga). The ground truth (GT) file is included too. All features are selected within each damage level. 

There are three folders attached:

**resampled_tifs**: A collection of all features' raster files in GeoTiff format.


The data used in the paper only includes 3 damage levels (0,1,2), i.e., no damage(0), slight damage(1), serious damage(2).

The “no damage” means the buildings were not affected, “slight damage” indicates the damages were generally repairable, and “serious damage” indicates that the buildings were heavily damaged (concrete construction and structure destroyed), to be demolished (partially collapsed buildings, e.g., those standing still with the first floor collapsing and disappearing), and collapsed (buildings in ruins).

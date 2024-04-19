# 2023-Turkey-Syria-Earthquake-ML-Data
This is the clean and sorted data prepared for the classification model in the paper "Intelligent assessment of building damage of 2023 Turkey-Syria Earthquake by multiple remote sensing approaches".

Please refer to the paper for more details.

If you apply the data and methodology in this paper, please add the citation: 

Yu, X., Hu, X., Song, Y., Xu, S., Li, X., Song, X., Fan, X., & Wang, F. (2024). Intelligent assessment of building damage of 2023 Turkey-Syria Earthquake by multiple remote sensing approaches. npj Natural Hazards, 1(1). https://doi.org/10.1038/s44304-024-00003-0


We have processed 5 features to establish the machine learning model, i.e., Amplitude Dispersion Index (adi), Damage_Proxy_from_Sentinel (dpm), Damage_Proxy_from_ALOS (dpm_alos),  Normalized Difference Built-up Index (ndbi), and Peak ground acceleration (pga). The ground truth (GT) file is included too. All features are selected within each damage level. 

There are three folders attached:

**resampled_tifs**: A collection of all features' raster files in GeoTiff format.

**GT_ka_shps**: The ground truth of 5 damage levels in the city of Kahramanmaraş, Turkey in shp format.

**all_features_4damge_level_select_within_shps**: A collection of all features' raster files selected within the corresponding damage level in GeoTiff format.


There are 8 columns in the summary file - 'data_collection.txt', in the order of 1. Longitude, 2. Latitude, 3. Amplitude Dispersion Index, 4. Damage_Proxy_from_Sentinel1, 5. Damage_Proxy_from_ALOS2, 6. Normalized Difference Built-up Index, 7. Peak ground acceleration, 8. Ground_Truth.

For the ground truth ranging from 0-4, the meaning is:
0:  no damage;
1: slight damage;
2: heavily damaged;
3: to be demolished;
4: collapsed;

The data used in the paper only includes 3 damage levels (0,1,2), i.e., no damage(0), slight damage(1), serious damage(2).

The “no damage” means the buildings were not affected, “slight damage” indicates the damages were generally repairable, and “serious damage” indicates that the buildings were heavily damaged (concrete construction and structure destroyed), to be demolished (partially collapsed buildings, e.g., those standing still with the first floor collapsing and disappearing) or collapsed (buildings in ruins)

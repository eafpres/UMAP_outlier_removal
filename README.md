# UMAP_outlier_removal
Demonstrate the use of UMAP to find outliers in high-dimensional tabular data
  
Jupyter notebook to apply UMAP to a demonstrate data set with ~ 80 dimensions and find outliers  
  
The approach is to map to 3 dimensions then fit the point cloud to a 3D ellipsoid  
Once the ellipsoid is fit, a radius threshold can be applied to select points outside a given distance from the center  
  
The approach has been used to obtain percent level improvement in xgboost regression models validation performance

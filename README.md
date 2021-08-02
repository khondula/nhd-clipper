# nhd-clipper

Find HUC8 and NHD data for a polygon (aop flightboxes)

* First downloads all HUC 2s from WBD, then reads in huc8s shp to intersect with your polygon, then gets HUC8 id(s) to download NHD.
* Saves maps of flowlines, waterbodies, areas, and zoom in of polygon
* tabulates flowline length by FCode

[FCodes](https://nhd.usgs.gov/userGuide/Robohelpfiles/NHD_User_Guide/Feature_Catalog/Hydrography_Dataset/Complete_FCode_List.htm)

## Characterizing Flood Risk in the Canal District

### UC Berkeley Landscape Architecture Studio 201: Ecological Factors of Urban Design

**This repository contains Marin County Tax Assessor based parcel information for 2023 for areas in the Canal District in San Rafael, CA that are within the flood zone during a the 1' sea-level rise scenario produced by USGS.** 

Overtopping information from  the Bay Conservation and Development Commission for the San Rafael under a 12" sea-level rise scenario is included and joined with parcel information.

Parcel analysis code is included in this repository. To run this code, please download the entire folder titled *SanRafaelCanalParcels* containing the datasets. Within the R Code are pathway shortcuts that require the R markdown and datasets to be in the same folder.

.jpeg files are maps of the Canal District showing flood inundation, saltwater wedge footprint, and building characteristics.

.lyrx files may be used in ESRI ArcGIS products to spatially reference parcels and overtopping areas. The "Groundwater Footprint 0.25mslr" layer identifies the predicted saltwater, freshwater, and tidal footprints under a 0.25m sea-level rise scenario as modeled by [Befus et al. 2023](https://www.nature.com/articles/s41558-020-0874-1). The "Flood Depth (in) 1ftslr" layer includes the flooding depth in inches under USGS's 1 foot of sea-level rise scenario as modeled by [Adapting to Rising Tides](https://www.adaptingtorisingtides.org/maps-and-data/).

Parcel polygons were downloaded from: [Marin County GIS Open Data](https://gisopendata.marincounty.gov/datasets/marincounty::parcels/explore?location=37.966279%2C-122.506203%2C13.00)

Overtopping data was downloaded from: [BCDC Shoreline Vulnerability Index](https://data.cnra.ca.gov/dataset/shoreline-vulnerability-index-bcdc-2021)

Parcel-specific data was collected from: [Marin County Tax Assessor Records](https://apps.marincounty.org/TaxRollSearch)

Contour lines were developed using [Marin County Vegetation and Landcover 2019 LiDAR](https://vegmap.marincounty.org/pages/lidar-products-and-derivatives)

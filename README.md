# ni-shapefiles

Shape files for Northern Ireland

## Process

1. Download zipped shapefile
2. Upload to [mapshaper](https://mapshaper.org/)
3. Simplify to 5% (or until just before details start to disappear)
4. Use the Console to convert to WGS84 `proj wgs84`
5. Export as TopoJSON
6. Upload to GitHub

## Sources

* [Small Areas SA2011](https://www.nisra.gov.uk/sites/nisra.gov.uk/files/publications/SA2011_Esri_Shapefile.zip)
* [Super Output Areas SOA2011](https://www.nisra.gov.uk/sites/nisra.gov.uk/files/publications/SOA2011_Esri_Shapefile_0.zip)
* [Health and Social Care Trusts HSCT](https://www.opendatani.gov.uk/dataset/department-of-health-trust-boundaries/resource/7fa52dde-90b8-446e-bb79-4871d1028cb4)

# traktour
Simple Tractor Navigation Via GraphHopper


## Getting Started

1. Download files (config.yml and graphhopper-web-0.13-SNAPSHOT.jar)
2. Due to the maxmimum size of 25 MB per file you have to download the OSM file from a different source.
   We suggest to use Geofabrik.de. Download your prefered region and copy it into the same folder:            
   http://download.geofabrik.de/europe/germany/brandenburg-latest.osm.pbf
3. run GraphHopper Maps: 
   java -Dgraphhopper.datareader.file=brandenburg-latest.osm.pbf -jar graphhopper-web-0.13-SNAPSHOT.jar server config.yml

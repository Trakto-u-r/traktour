# ![TrakTo(u)r](http://www.geoinfo.io/projects/traktour/traktour500x90.gif)
Simple Tractor Navigation Via GraphHopper

## Getting Started

1. Download files (config.yml and graphhopper-web-0.13-SNAPSHOT.jar)
2. Due to the maximum size of 25 MB per file you have to download the OSM file from a different source.
   We suggest to use Geofabrik.de. Download your prefered region and copy it into the same folder:            
   http://download.geofabrik.de/europe/germany/brandenburg-latest.osm.pbf
3. run GraphHopper Maps: 
   java -Dgraphhopper.datareader.file=brandenburg-latest.osm.pbf -jar graphhopper-web-0.13-SNAPSHOT.jar server config.yml
4. If everything works fine you should get a message like ([main] INFO  o.e.jetty.server.AbstractConnector - Started    
   application@63dfdad0{HTTP/1.1,[http/1.1]}{localhost:8989}). Simply open your browser then and open localhost:8989. The 
   routing should be working now.

Make sure the latest JRE is installed.


![TrakTo(u)r - Example](http://www.geoinfo.io/projects/traktour/tractor_screen.png)

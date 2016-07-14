# IITC Ingress Portal CSV Export
This is a plugin for the [Ingress Total Conversion](http://github.com/iitc-project/ingress-intel-total-conversion) userscript. It allows you to parse the name, image, and coordinates for all Ingress portals within the viewport. This portal data can then be downloaded as a CSV file or viewed in-browser (in CSV format).

This plugin was written with the intention of building a Google Map for Pokemon Go gym and pokestop locations.

### Usage
After installing the userscript, navigate to the [Ingress intel page](https://www.ingress.com/intel).

You will see a new toolbox added to the IITC sidebar. Once your zoom level is set to 15 (displayed in the plugin) you can start the scraper. The zoom restriction is required as lower zoom levels do return the full set of data for portals, only their coordinates.

The scraper will not download any portal data until the current map view has finished loading.

Once map data has loaded and the viewport has been scraped, the plugin will draw a green rectangle over the viewport boundaries on the map layer. This makes it easier to pan around and capture large areas (due to the zoom restriction) while keeping track of what has already been captured.

#### Credits
Many of the helper functions were taken from the [IITC Maxfields Exporter](http://github.com/itayo/IITC-Ingress-Maxfields-Exporter) plugin by [itayo](http://github.com/itayo).


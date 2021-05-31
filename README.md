# Indian Government Compliant World Map

The North Indian union territories jaamu & kashmir and ladakh have disputed territories with china and pakistan. [The government of India has made it illegal within India to show India's map without disputed territories](https://timesofindia.indiatimes.com/india/7-year-jail-rs-100-crore-fine-for-wrong-depiction-of-india-map/articleshow/52133221.cms).
I couldn't find a government compliant geojson of world map online so I created one.

## &#128295; Tools Used

* [geojson-maps.ash.ms](https://geojson-maps.ash.ms/)
* [geojson.io](geojson.io)
* [mapshaper.org](https://mapshaper.org/)

## &#128220; Methodology
* I created two geojson files using [geojson-maps.ash.ms](https://geojson-maps.ash.ms/) one including India, Pakistan and China and one with rest of world. 
* Then imported first file in [geojson.io](geojson.io) and changed boundaries to get required map then imported second file and tried fixing alignments of boundaries and did some other finishings.
* Then exported whole map as single geojson file.
* Imported this geojson file in [mapshaper.org](https://mapshaper.org/) and repaired line intersections and exported file as world_map_ind_gov_compliant.geojson.
    
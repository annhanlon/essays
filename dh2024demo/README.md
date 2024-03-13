.ve-header "DH Workshop 2024: An Introduction to Juncture"

This workshop will walk you through the steps to set up a Juncture/GitHub account and create a simple digital visual essay. You can do a lot with Juncture, but it's also a great jumping-off point to dip your toe into the GitHub, IIIF, geographic location, and Wikidata waters, if you want it to be. 

#Codex of Huamantla

.ve-media https://www.loc.gov/item/2021667607/manifest.json
The context in which this codex was created is unknown, but its purpose clearly is to tell the story of the Otomi people of Huamantla. The center of the painting depicts the migration of a group of ==Otomi=={Q1132647} from Chiapan, in the present-day state of Mexico, to Huamantla, which is located in present-day Tlaxcala state. The migration, which took place in the Post-Classical period, was undertaken under the protection of the goddess Xochiquétzal and of Otontecuhtli, lord of the Otomi and of fire. The glosses contain the names of the leaders who led the migration. In the depiction of Teotihuacan (location of the large pyramids of the Classical period), the pyramids are shown covered in vegetation, i.e., abandoned. In the 16th century, Otomi culture appears to have been permeated with Nahua material culture, language, and mythology; alongside the pyramids is a representation of the Nahua myth of the birth of the sun. The second pictographic group, added above the first by another artist, uses less space and a smaller scale to show the participation of the Otomi in the conquest of Mexico and the lives of the Otomi under Spanish domination.

#Multi-page
.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/25576/manifest.json seq=4 left
This map is from the April 1936 City of Milwaukee Housing Survey created by the Board of Public Land Commissioners. It consists of multiple pages and includes data on population statistics, land use, transportation, etc. And here, you can zoom into the part of the map that is ==now UWM=={7348,3670,1339,1717}. 

#San Juan Ñumí
.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/2328/manifest.json right
These images are part of a mid-sixteenth century Mesoamerican painted manuscript on deer hide presented as a map in land litigation in 1802. The codex begins with Mixtec text naming the boundaries of ==San Juan Ñumí=={1983,3185,666,520}, a town in northern Oaxaca. The rest of the codex is pictorial and reads from top to bottom. A mythological origin scene is followed by the genealogies of two ruling dynasties from the polities of Acatlán and likely Chila in the Mixtec-speaking region of southern Puebla. The manuscript is also known as Codex Huamelulpan.

#Tira de Santa Catarina Ixtepeji
.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/14325/manifest.json


#Using images from Wikimedia Commons
.ve-media wc:Aztlan_codex_boturini.jpg left
Wikimedia Commons describes this image as part of the Boturini Codex. The licensing information indicates that this image is in the public domain. I have used the "left" position tag in order to shrink it to 50% size and position it at the left margin of the screen, with this text on the right. [^1]

You can zoom in to see the artist's depiction of the ==Mexica departing from Aztlán=={200,200,400,400}.

#New section
.ve-media https://www.loc.gov/item/2021667610/manifest.json

##Comparing images
You can compare two images in the essay. 
.ve-media compare caption="Comparing two completely different celestial maps"
    - https://collections.lib.uwm.edu/iiif/info/celestial/66/manifest.json
    - https://collections.lib.uwm.edu/iiif/info/celestial/81/manifest.json


#Where is all this?
.ve-map Q37836 8 marker left
Both of the scrolls featured in this essay were made in the Oaxaca region of Mexico. We are using an OpenStreetMap to mark the location of the Oaxaca region on a map. The way we are pointing to the region in this section is by using the Wikidata ID for ==Oaxaca=={Q34110}, which can be found by looking up Oaxaca in [Wikidata](https://www.wikidata.org/) . 

#How else could we show the Oaxaca region?
.ve-map  Q34110 8 marker basemaps=Esri_WorldImagery right
In this case, the only change is the basemap, which is now using the Esri World Imagery map.

#Full width
And here the 50% width limitation has been eliminated, making it easier to see the location of Oaxaca on the Pacific coast of Mexico, with Veracruz and the Gulf of Mexico to the north. But those locations are not labeled. The best place to find other ways to show maps and locations are here:. [Basic map examples in Juncture](https://www.juncture-digital.org/components/map?id=basic-map-examples)
.ve-map  Q34110 8 marker basemaps=Esri_WorldImagery 

#Map layer and Wikidata
.ve-map 17.055,-96.653889 8 width=50% 
    - Q986132 layer=Cities
    - Q10812451 layer=Cities
    - Q131429 layers=Cities
In this example, the cities are identified simply by locating their Wikidata ID. One note - the zoom here is important. If it is too narrow, not all of the cities will appear by default. This is something you can play around with until you get it right.     

[^1]: File accessed from Wikimedia Commons on August 2, 2023, at [https://commons.wikimedia.org/wiki/File:Aztlan_codex_boturini.jpg](https://commons.wikimedia.org/wiki/File:Aztlan_codex_boturini.jpg)

#A note on formatting
This workshop instructor recommends approaching formatting as simply as possible. Dividing your essay into sections under headers seems to be the best way to approach formatting. Additionally, consider the Juncture visual essay a scroll, essentially! We are continuing a long tradition, exemplified by the Codex Tulane.
.ve-media gh:annhanlon/media/codex-tulane/Codex_Tulane_Full_Scroll.jpg width=60%



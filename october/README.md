.ve-header "DH Workshop 2023: An Introduction to Juncture"

This workshop will walk you through the steps to set up a Juncture/GitHub account and create a simple digital visual essay. You can do a lot with Juncture, but it's also a great jumping-off point to dip your toe into the GitHub, IIIF, geographic location, and Wikidata waters, if you want it to be. 

#Codex Tulane or Códice Hamelulpan

.ve-media gh:annhanlon/media/codex-tulane/Codex_Tulane_on_exhibit.jpg right
The Codex Tulane or Códice Hamelulpan provides a fascinating example of the adaptability and re-purposing of native texts within changing historical contexts.  Like most post-contact codices, the Codex Tulane was likely composed in the early decades of Spanish rule (ca. 1550s) to establish an authoritative lineage or lineages vying for territorial rights and privileges.  Painted on gessoed pieces of deer hide are 15 generations of royal ancestors spanning 300 years of marital history from two ==Mixtec-speaking=={Q36363} towns, Acatlán and Chila, located in what is today southern Puebla and northern Oaxaca, Mexico.  The document was painted for Mixtec elites to support their claims before Spanish colonial administrators who likely would not have understood the Mixtec glyphs or the rolled out format but would have respected its native provenance and visual impressiveness.  This alone would have conferred on the document a kind of discursive authority which local caciques deployed in their favor. The physical characteristics and textual content of the piece combine pre-contact pictorial conventions of both Mixtec and Aztec indigenous scribes, such as the deerskin substrate and the use of the native calendar, hieroglyphics, and iconography.  Notable too is the continued indigenous practice of beginning the manuscript with references to the creation of the world, iconic places, and principal deities, thereby extending the reign of these two noble houses back into the mythological past and connecting them to the political history of the region.

#Lineage (zooming)
.ve-media gh:annhanlon/media/codex-tulane/Codex-Tulane.jpg left 
The far end of the document depicts the royal genealogy of Acatlan. In the image below, zoom in on the ==royal couple=={1945,2192,1998,2193}, where symbols depict their xyz... You can find the zoom by creating the media on this page, zooming in to the destination and moving your mouse over the bottom right to find the image coordinates to input. There will be four numbers separated by commas and no spaces. 

#San Juan Ñumí
.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/2328/manifest.json right
These images are part of a mid-sixteenth century Mesoamerican painted manuscript on deer hide presented as a map in land litigation in 1802. The codex begins with Mixtec text naming the boundaries of ==San Juan Ñumí=={1983,3185,666,520}, a town in northern Oaxaca. The rest of the codex is pictorial and reads from top to bottom. A mythological origin scene is followed by the genealogies of two ruling dynasties from the polities of Acatlán and likely Chila in the Mixtec-speaking region of southern Puebla. The manuscript is also known as Codex Huamelulpan.

#Tira de Santa Catarina Ixtepeji
.ve-media https://collections.lib.uwm.edu/iiif/info/agdm/14325/manifest.json
This manuscript map, known as the Tira de Santa Catarina Ixtepeji and housed at the University of Wisconsin-Milwaukee Library's American Geographical Society Library, is hand-painted and recounts part of the history of Santa Catarina Ixtepeji, in the Ixtlán District in the Sierra Norte region of Oaxaca in southwestern Mexico. The scroll tells the history of leadership and land ownership, and is believed to have been written in both the local Zapotec and Spanish languages. Its purpose was to regularize land titles and ownership in the eyes of the bureaucracy of the Spanish Empire. There are two dates (1691 and 1709 A.D.) inscribed on it that are believed to be the dates it was used as a visual aid in making a presentation to Imperial officials. Similar to the Tulane Codex, this is also post-contact but nearly a century older.

#Using images from Wikimedia Commons
.ve-media wc:Aztlan_codex_boturini.jpg left
Wikimedia Commons describes this image as part of the Boturini Codex. The licensing information indicates that this image is in the public domain. I have used the "left" position tag in order to shrink it to 50% size and position it at the left margin of the screen, with this text on the right. [^1]

You can zoom in to see the the artist's depiction of the ==Mexica departing from Aztlán=={200,200,400,400}.

.ve-media wc:Milwaukee_Art_Museum_1_(Mulad).jpg

#Side by side
.ve-media 
    - gh:annhanlon/media/codex-tulane/Codex-Tulane.jpg
    - gh:annhanlon/media/codex-tulane/Acatlan.jpg
    - gh:annhanlon/media/codex-tulane/Chila.jpg


##Comparing images
You can compare two images in the essay. 
.ve-media 
    - https://collections.lib.uwm.edu/iiif/info/celestial/66/manifest.json
    - https://collections.lib.uwm.edu/iiif/info/celestial/81/manifest.json


#Where is all this?
.ve-map Q34110 8 marker left
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



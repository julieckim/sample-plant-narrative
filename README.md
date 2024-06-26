<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url=https://upload.wikimedia.org/wikipedia/commons/4/47/Bartholomeus_Johannes_van_Hove%2C_Het_Mauritshuis_te_Den_Haag.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Quassia amara

_Quassia amara_ is a plant named after Graman Kwasimukambe (also known as Kwasi), an Afrodescendant naturalist who lived in Suriname in the eighteenth century. A botanical illustration of _Quassia amara_ appeared in an 1800 issue of William Curtis' famed _The Botanical Magazine; Or, Flower-Garden Displayed_, one of the leading botanical publications of its time. Sydenham Edwards was the artist who created the illustration. His name appears in the <span data-mouseover-image-zoomto="202,1764,1600,1447">caption</span> at the bottom of the illustration. 

<param ve-image 
       url="https://www.biodiversitylibrary.org/pageImage/469068"
       label="Quassia amara" 
       description="Botanical illustration from William Curtis' Botanical Magazine"
       license="Public domain"
       fit="contain">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Suriname

Kwasi found _Quassia amara_ growing in Suriname. The capital of Suriname is <span data-mouseover-map-flyto="5.8237, -55.1747, 12">Paramaribo</span>. The Surinaams Museum in Paramaribo is dedicated to preserving Suriname's history and culture.

<param ve-map 
       center="Q730" 
       zoom="7"
       Title="Suriname"
       show-labels>
<param ve-map-marker
       url="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Fort_Zeelandia.jpg/800px-Fort_Zeelandia.jpg"
       coords="5.8252, -55.149872"
       size="800, 541" 
       circle="true">

## Suriname River Journey

This map shows a journey down the Suriname River from Paramaribo. 

<param ve-map
       center="5.1566, -55.0882"
       zoom="5"
       Title="Suriname River Journey"
       prefer-geojson>
<param ve-map-layer geojson
       url="https://raw.githubusercontent.com/julieckim/sample-plant-narrative/main/surinameriver.json"
       show-labels
       stroke-width="0">

## Suriname in Colonial Narratives of Exploration

Suriname and its nature have been the subject of many colonial narratives of exploration.

<param ve-iframe
       src="https://books.google.vu/books?id=6r8WAAAAYAAJ&pg=PA156-IA2&output=embed">

## Timeline of Suriname Colonizations

Many European powers wanted to colonize Suriname, and it changed hands at several points in its early colonial history.

<param ve-knightlab-timeline
       source="1QRf1OqwL5Awyus1LveVmNVPbNt3gw8BhzSH8b--lMHw"
       timenav-position="bottom"
       hash-bookmark="false”
       initial-zoom="1"
       height="750">

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)

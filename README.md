<a href="https://www.juncture-digital.org"><img src="https://juncture-digital.github.io/juncture/static/images/ve-button.png"></a>

<param ve-config 
       title="Mimosa pudica"
       author="Sabrina Freidus"
       layout="vertical">

### Introduction
[_Ilexparaguariensis_](https://powo.science.kew.org/taxon/urn:lsid:ipni.org:names:315555-2) is an evergreen shrub or tree native to the subtropical forests of Brazil, Paraguay, Uruguay, and Argentina that can grow up to forty-nine feet tall. It’s a plant species of the genus ilex (or “holly”) that contains caffeine as well as other alkaloid components, and it has stimulant, diuretic, antioxidant, and antimicrobial properties that made it attractive to both the indigenous Guaraní people and to Spanish colonial settlers. After being dried, roasted, and powdered, mate leaves are used to prepare a hot or cold beverage, also known as mate or Paraguayan Tea. The loose powder is typically steeped in hot water and strained through a <span data-mouseover-image-zoomto="893,847,445,374">metallic straw</span>, or bombilla, shared by many people, passing from mouth to mouth. During the 19th century, the drink became associated with South American *gauchos*. The same mate and bombilla are shared in social gatherings, a habit that has endured despite recent public health campaigns to prevent COVID-19 pandemic. The flower is beautiful and pink. 

<param ve-compare curtain url="https://upload.wikimedia.org/wikipedia/commons/c/c2/Gauchos_mateando.jpg" label="Gauchos drinking mate" description="Photograph" license="public domain" >
<param ve-entity eid="Q155" title="Brazil">
<param ve-entity eid="Q46429" title=“Guarani people”>
<param ve-entity eid="Q84263196" title=“COVID-19 pandemic”>
<param ve-compare url="Mimosa.jpg" label="Mimosa pudica flower">

## New Section Test

I am trying to start a new paragraph! I hope it works. 
<param ve-video vid="DF-b6TsO1DM">

## Plant specimen

To the right, you will see a specimen of Mimosa pudica.
<param ve-plant-specimen jpid="10.5555/al.ap.specimen.bnrh0000364">

## Primary source text

Now we are trying to embed primary source text. We can use either Google Books or archive.org. We're going to try archive.org for now. copy and paste the whole link. 

<param ve-iframe src="https://archive.org/details/sbaww_124_0507-0528/page/n20/mode/2up?view=theater">

## Timeline!

Lets see if the timeline shows up! 

<param ve-knightlab-timeline
source="14w7zD7sNWltsUVesaHF_xVvB4yDoXZuaUNchFP-sTkA"
timenav-position="bottom"
hash-bookmark="false"
initial-zoom="1"
height="705">

## Maps! 

Now we're going to code a map. "Esri_WorldPhysical" shows a world map without modern political borders.

<param ve-map basemap="Esri_WorldPhysical">

New paragraph. Use center to focus the map on a specific location. Zoom zooms in! You can also get coordinates on Google Maps. 
<param ve-map center="Q733" zoom=3>


## new image

trying to annotate an image. in order to annotate, click on the little comment thing with the pen. then press shift and command, and then draw a rectangle with the mouse. you can add annotations. up to 5 annotations should be aliright, but don't do more. And then you can play the slideshow buttun, which will present the annotations to the reader! it doesn't support more than one image (so no galleries or comparisons)

<param ve-image url="https://upload.wikimedia.org/wikipedia/commons/e/e7/Mimosa_leaves_detail.jpg">

## more maps

mapping! find the coordinates on google map to center your map. then use zoom if desired. to draw shapes or drop points, use geojson.io. the code is written on the right side of the page automatically. when you're done making the changes you want to the map, copy the code. in gitbub, go to the repositories and create a new file. paste all of the code from geogson. then name the file anything.json, and commit changes. you can add as many layers as you want, but you have to make a new repository for each geojson file. we're not going to try <span data-mouseover-map-flyto="-23.393234459064555, -46.59150010356098, 14">connecting</span> words in the text to the map. i deleted the map layer.

<param ve-map title="test map" center="-23.55250132365363, -46.64158231085635" zoom="3">
<param ve-map-layer geojson url="https://raw.githubusercontent.com/sabrina758/test/main/maplayers.json">

it didn't work, so i amawe're not going to try <span data-mouseover-map-flyto="-23.578856648290582, -46.47665865939823, 14">connecting</span> words in the text to the map. i deleted the map layer.

<param ve-map title="test map" center="-23.55250132365363, -46.64158231085635" zoom="3">

now we are getting a map from natural earth on geojson. https://github.com/martynafford/natural-earth-geojson is the link we used. then we found a file and got the raw data. then we used command f to find a country. 

# Changes made to this rendering
This page describes changes made [here](https://github.com/SomeoneElseOSM), [here](https://github.com/SomeoneElseOSM/SomeoneElse-style-legend) and [here](https://github.com/SomeoneElseOSM/openstreetmap-carto-AJT), visible [here](http://map.atownsend.org.uk/maps/map/map.html).

## 28/08/2017 style updates
Removed rendering of verges on secondary roads at z12.

## 26/08/2017 release
Welsh-speaking areas rendered using "name:cy" in place of "name; Scots Gaelic areas similarly use "name:gd".  The rest of England, Wales and Scotland use "name:en"; Ireland and Northern Ireland use "name".  See [here](https://github.com/SomeoneElseOSM/SomeoneElse-style/blob/master/update_render.sh) for the script that handles this.
Added "unmade_road" to the list of handled designations for UCR.
If name:en exists but name does not, use name:en.
Added another spelling of PNFS.
If "bridge_name" or "bridge:name" exist, render those on bridges in place of "name".
If it exists, append "lock_ref" to the end of "lock_name" or "name" in brackets.
Added more signs to be displayed using the "information=sign" icon.
Added various "tourist" values so that they show in green as nonspecific leisure.
Improved rendering of holiday cottages and synonyms.

## 17/08/2017 release
Car washes now have their own icon
Added craft=roofer to the "house fixing" group icon.

## 08/08/2017 release
Added support for shop=tourism, office=advertising, shop=fuel.
Added support for waterway=aqueduct.
Show parking spaces as private parking areas (which actually mirrors usage in UK).
Added support for a couple of variations of pet grooming.
Improvements car repair display and added icon for car parts and synonyms.
Added support for more fast food cuisines.
Added support for leisure=club, and sailing and sport clubs.
Added icons for bicycle parking, waste_basket.

## 27/06/2017 release
Further improvements to shop rendering based on their use according to taginfo.
Change aerodrome tagging to not show small, disused or military airports.
Change runway tagging to show grass strips less prominently.
Show flood banks and embankments where there's no highway on top.
Show flood banks and embankments in some easy-to-categorise cases where there is a highway on top.
Show different sorts of information - board, office, etc., and add to legend.

## 17/06/2017 01:49 release
Further improvements to shop and office rendering based on their use according to taginfo.
Added display of defibrillators at high zooms in healthcare red.
Added more fast food icons.
Support more bridge and tunnel types and "man_made=bridge".

## 05/06/2017 23:08 release
Render pubs with a microbrewery with a characteristic icon and add to legend.

## 29/05/2017 18:25 release
Added more shop and leisure types.
Added different sorts of milestones.
Changed "fast food" display so that different but similar icons are used for different cuisine types.
Made highway=road less prominent.
Improved rendering of long distance paths.
Added name for sundial icon.
Added map legend based on [this](https://github.com/SomeoneElseOSM/SomeoneElse-style-legend) repository.

## 03/04/2017 00:43 release
Improvements to shop and office rendering based on their use according to taginfo.
Added support for emergency phones.
Added different sorts of lesser-used waterways.
Added the display of roadside verges (green as opposed to grey for sidewalks).
Change fonts use to "Noto" to work with non-latin characters.

## First map.atownsend.org.uk release - 19/02/2017
Added different but similar icons for different types of pubs.
Added support for vacant shops.

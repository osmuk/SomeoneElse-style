# Changes made to this rendering
This page describes changes made [here](https://github.com/SomeoneElseOSM), [here](https://github.com/SomeoneElseOSM/SomeoneElse-style-legend) and [here](https://github.com/SomeoneElseOSM/openstreetmap-carto-AJT), visible [here](http://map.atownsend.org.uk/maps/map/map.html).


## 23/10/2017 release
Added support for boundary stones.
Added sluice gates (named, and as infrastructure).
Like trail_visibility, suppress some demanding sac_scale paths if no designation.
Treat waterway=fish_pass like waterway=drain.
Added private parking to legend.
Changed parking to use a .png and added support for "fee parking".

## 11/10/2017 release
New symbol for route markers (as distinct from guideposts et al).
Added icon for shopmobility and selected for it in style file.

## 01/10/2017 release
Added more leisure values.  
Added more mistaggings and aliases for e.g. swimming_pool.
Updated legend with existing and new leisure values.

## 27/09/2017 release
Added public_bath to nonspecific leisure.
Added support for names on barriers.
Various legend updates including cars, education, rail and aeroway.
Added shop=milk and amenity=van_rental.
Remove man_made=tower from wind turbines.
Added healthcare=therapy, various tutoring places.
Treat access=permit as access=private.
If a street has different names on each side, render it.
Render natural=fell as natural=heath ("generic upland").
Added shop=milk and amenity=van_rental.

## 22/09/2017 release
Changed survey point et al names to black.
Changed embassy to brown and changed similar brown z17 names to the same font.
Changed ATM to use operator if set as the name.
Changed lighthouse to black.
Only render bus_stop on joint bus_stop/waste_baskets and fix rendering of bus_stop name in the legend.
Render names for bicycle_rental, bicycle_parking etc.
Changed water tower to render at z15 and added name.
Changed other classes of points to render similarly (see the rows in the legend) and added names.
Changed ventilation_shaft to man_made.

## 18/09/2017 map layer change
Added German Style layer to https://map.atownsend.org.uk/maps/map/map.html

## 14/09/2017 style updates
Added more feature names.  See Legend for details of current coverage.
Moved more features (e.g. slipway) to amenity brown.

## 13/09/2017 release
Added road names for primary sidewalk and verge.
Added more prow_ref names.
In legend, split primary, trunk and motorway into sidewalk and trunk etc.
Added a couple of prow_ref to show up on the legend.
Added a "legend generator" to generate the "pub" legend and use that legend in reload scripts.
Add support for parcel lockers.
Add building tag to lighthouses.

## 07/09/2017 release
Added support for left luggage lockers.

## 04/09/2017 release
Added support for sidewalks and verges on primary roads.

## 29/08/2017 style updates
Further improved road rendering at z13-z19.  
Added more granularity, including explicit z18 settings.
Adjusted the size of verges to allow for the extra prominence of the colour.
Reduced width of residential/unclassified at high zooms.
Reduced service casing.

## 28/08/2017 style updates
Removed rendering of verges on secondary roads at z12.
Split verge width from sidewalk width.  
Reduced sidewalk width slightly at z13 and reduced verge width significantly at z13.
Rendered sidewalks/verges for unclassified / residential.

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


Radio Map (Radio Ga Ga)
========

Pulls in radio stations, determines broadcast ranges, displays available stations nearest a location

Sources:
US Database
http://www.fcc.gov/encyclopedia/fm-query-broadcast-station-search

Canadian Database
http://www.ic.gc.ca/eic/site/smt-gst.nsf/eng/h_sf09484.html


References:
http://publicradiomap.com/

Problem attempting to solve:
I want to know what radio stations are nearby when I travel, spefically NPR or college radio

But really:
Just want to make a cool visualization that could be useful to someone, too


TODO:

- Grab station and frequency data given a location using above sources 
    Can data give probable broadcast range or do we need to determine by algorithm?
      Yes?  Cool.
      No?   Find or create an algorithm that could take geological data into consideration including
            signal strength, interference, weather, and other factors that may affect range.
- Generate a list of all the stations in a given area
- Allow a user to input a certain station, ex. NPR, to find that station's frequency given their location
- Build controls that allow you to change station coverage based on time (if data is provided
- Colorize data by genre or commercial vs public
- Also.... find a visual library that would be able to display this stuff easily :>
- Node for backend? Probably. Research backbone and angular a bit



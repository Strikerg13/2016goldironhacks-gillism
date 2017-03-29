This is the ReadMe for Matt Gillis' project.

         ____                                   __
        /\  _`\               __               /\ \__
        \ \ \L\ \_ __   ___  /\_\     __    ___\ \ ,_\
         \ \ ,__/\`'__\/ __`\\/\ \  /'__`\ /'___\ \ \/
          \ \ \/\ \ \//\ \L\ \\ \ \/\  __//\ \__/\ \ \_
           \ \_\ \ \_\\ \____/_\ \ \ \____\ \____\\ \__\
            \/_/  \/_/ \/___//\ \_\ \/____/\/____/ \/__/
                             \ \____/
                              \/___/
 ______                               __      __                      __
/\__  _\               __            /\ \  __/\ \                    /\ \
\/_/\ \/ _ __    __   /\_\    ___    \ \ \/\ \ \ \  _ __    __    ___\ \ \/'\
   \ \ \/\`'__\/'__`\ \/\ \ /' _ `\   \ \ \ \ \ \ \/\`'__\/'__`\ /'___\ \ , <
    \ \ \ \ \//\ \L\.\_\ \ \/\ \/\ \   \ \ \_/ \_\ \ \ \//\  __//\ \__/\ \ \\`\
     \ \_\ \_\\ \__/.\_\\ \_\ \_\ \_\   \ `\___x___/\ \_\\ \____\ \____\\ \_\ \_\
      \/_/\/_/ \/__/\/_/ \/_/\/_/\/_/    '\/__//__/  \/_/ \/____/\/____/ \/_/\/_/

Translation:
  01010000 01110010 01101111 01101010 01100101 01100011 01110100
01010100 01110010 01100001 01101001 01101110  01010111 01110010 01100101 01100011 01101011

- For this project I will be getting data from the data.gov website on veggies (probably).

	Edit: The project description said we're supposed to be finding veggies, but the mandatory dataset
	      is climate data! How does this make any sense?! 

	Edit: The project now has nothing to do with veggies. It is using a datasource for historical climate 
	      data, and a 2nd datasource from the house pricing index. 

- I'll probably pull the data into a list & display the list for veggies nearby (or not, haven't really decided yet)

	Edit: none of this will happen...the cake is a lie!


Datasets used:
- Global Historical Climatology Network - Daily (GHCN-Daily), Version 3: https://gis.ncdc.noaa.gov/geoportal/catalog/search/resource/details.page?id=gov.noaa.ncdc:C00861
- FHFA House Price Indexes (HPIs): https://catalog.data.gov/dataset/fhfa-house-price-indexes-hpis

Visualization (from d3) used:
- Choropleth: http://bl.ocks.org/mbostock/4060606
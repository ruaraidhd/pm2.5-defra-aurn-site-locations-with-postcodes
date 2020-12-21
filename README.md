#DEFRA AURN site locations with postcodes
This file includes all DEFRA automatic urban and rural network PM2.5 
monitoring sites by name, code, lat, lng, site_type (urban, rural etc),
and postcode. They are correct as of 21 December 2020.

Sites were downloaded through the [OpenAir R package](https://davidcarslaw.github.io/openair) (with thanks to
David Carslaw). Postcodes were assigned using the LocationIQ reverse
geocoding API. Where postcodes were not correctly assigned (as in 24
cases) the latitudes and longitudes were assessed manually using Google
Maps.

Note that these are **only sites monitoring PM2.5**, not necessarily other 
pollutants.

Ruaraidh Dobson PhD
Institute for Social Marketing and Health
University of Stirling

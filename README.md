<details>
<summary>Version history</summary>

Version 1: June 18 2026 10:49pm est added categories to use

Version 2: June 18 2026 11:35pm est added first batch of links

Version 3: November 21 2026 9:05pm est added historical weather satellite archives (GOES-12 and earlier), astronaut photography, and more air photo sources

Version 4: November 21 2026 9:15pm est reorganized into Current (still collecting new imagery) and Historical (finished collections or retired satellites)

Version 5: November 21 2026 9:20pm est added GridSat-GOES


</details>

# Current

Sources that are still running and still adding new imagery. Many of these also have a deep archive, noted as "back to".

<details>
<summary>Satellite Imagery</summary>

## World wide

[Google earth](https://earth.google.com/web/) - historical imagery slider in the desktop version
[Bing maps](https://www.bing.com/maps)
[Esri imagery](https://hub.arcgis.com/maps/10df2279f9684e4a9f6a7f08febac2a9/explore)
[Esri imagery wayback](https://livingatlas.arcgis.com/wayback/#mapCenter=116.40978%2C39.51004%2C14&mode=explore&active=10842) - every past version of the Esri basemap, back to 2014
[Mapbox Satellite](https://docs.mapbox.com/data/tilesets/reference/mapbox-satellite/)
[OpenAerialMap](https://openaerialmap.org)
[Copernicus Browser](https://browser.dataspace.copernicus.eu) - Sentinel-2 back to 2015
[Apple maps](https://maps.apple.com/search)
[Earth Explorer](https://www.usgs.gov/tools/earthexplorer) - Landsat back to 1972, also hosts declassified spy satellite film
[NASA Worldview](https://worldview.earthdata.nasa.gov) - daily global MODIS/VIIRS true colour, good for checking clouds on a given day, back to 2000

## North America only

## South America only

## Africa only

## Europe only

## Asia only

</details>

<details>
<summary>Weather Satellite Imagery</summary>

Useful for checking cloud cover on a specific date, e.g. to confirm when a ground or space photo was taken.

## World wide

[NOAA CLASS](https://www.class.noaa.gov) - NOAA's main archive. GOES imager data (GVAR_IMG) for GOES-8, 9, 10, 12 and later back to late 1994, plus polar-orbiter (POES/AVHRR) data. Free account, order then download
[NOAA CLASS GOES GVAR imager glossary](https://www.aev.class.noaa.gov/glossary/GVAR_IMG.htm) - what the GOES-12 (G12) file fields and formats mean
[SSEC Satellite Data Services GOES archive (Univ. of Wisconsin)](https://www.ssec.wisc.edu/datacenter/goes-archive) - one of the largest geostationary archives, every GOES satellite back to the 1970s plus international satellites. Accessed through McIDAS/ADDE
[SSEC Data Center archive table](https://www.ssec.wisc.edu/datacenter/archive) - which satellites and date ranges SSEC holds (includes GMS-1 from 1978)
[GIBBS - Global ISCCP B1 Browse System](https://www.ncei.noaa.gov/gibbs/) - quick browser for global geostationary images every 3 hours, back to 1980 (some earlier). Easiest way to just look at a date
[GridSat-B1 (NCEI)](https://www.ncei.noaa.gov/products/gridded-geostationary-brightness-temperature) - all geostationary satellites merged onto one 0.07 degree global grid, every 3 hours, back to 1980. Visible channel is low quality, IR is the good one
[GridSat-B1 THREDDS download by year](https://www.ncei.noaa.gov/thredds/catalog/cdr/gridsat/catalog.html)

## North America only

GOES East/West cover the Americas. Use CLASS or SSEC above.

## South America only

## Africa only

## Europe only

## Asia only

[JMA Meteorological Satellite Center data archives](https://www.data.jma.go.jp/mscweb/en/product/library_data.html) - GMS/Himawari date ranges back to Sept 1977, and where to get them
[Kochi University weather satellite images](http://weather.is.kochi-u.ac.jp/) - processed Himawari/GMS images, back to 1994

</details>

<details>
<summary>Astronaut / Crewed Mission Photography</summary>

## World wide

[Gateway to Astronaut Photography of Earth (NASA JSC)](https://eol.jsc.nasa.gov/searchphotos/) - astronaut photos of Earth back to 1961 (Mercury, Gemini, Apollo, Shuttle, ISS). Search by place, mission-roll-frame number, or map. Metadata often includes date, time and nadir point

</details>

<details>
<summary>Aerial Imagery</summary>

## World wide

## North America only

## South America only

## Africa only

## Europe only

## Asia only

</details>

# Historical

Collections that are finished: the satellite is retired, the survey is done, or the original site is gone.

<details>
<summary>Satellite Imagery</summary>

## World wide

[US spy satellite declassified imagery](https://spacefromspace.com/declassified-satellite-images/) - CORONA, GAMBIT, HEXAGON (1960s to 1980s)

## North America only

## South America only

## Africa only

## Europe only

## Asia only

</details>

<details>
<summary>Weather Satellite Imagery</summary>

## World wide

[NSIDC Nimbus Data Rescue](https://nsidc.org/data/nimbus) - scanned Nimbus 1-3 film images from 1964, 1966 and 1969-70, including daily global composites and GeoTIFFs

## North America only

[GridSat-GOES direct download (NCEI)](https://www.ncei.noaa.gov/data/gridsat-goes/) - GOES East and West (GOES-8 to 15, including GOES-12) already calibrated and gridded at 0.04 degrees (~4 km) in netCDF, Oct 1994 to Dec 2017. Hourly full disk over the Americas and Atlantic, every 15 min over the continental US. Much easier than raw CLASS files for comparing an old photo against the clouds
[GridSat-GOES dataset landing page](https://doi.org/10.7289/V5HM56GM) - description and citation

## South America only

See GridSat-GOES under North America (full disk covers South America too).

## Africa only

[EUMETSAT Meteosat First Generation](https://www.eumetsat.int/meteosat-first-generation) - Meteosat-1 to 7 (1977 to 2017) at 0 degrees, sees all of Africa and Europe, full disc every 30 min
[EUMETSAT data rescue](https://www.eumetsat.int/data-calibration-and-rescue) - recovered Meteosat-1 data (found in the US in 2015)

## Europe only

See EUMETSAT under Africa.

## Asia only

## Notes on how far back you can go

- Before ~1978 there were no full-disc geostationary images every 30 minutes, so early dates depend on polar orbiters (Nimbus, ESSA, NOAA-1 to 5) passing once or twice a day.
- NOAA-2 (1972 onward) imagery is the earliest good option for something like the Apollo 17 Blue Marble photo (7 Dec 1972, 10:39 UTC). The north and south passes have to be stitched into one mosaic.
- From 1980 on, GIBBS and GridSat-B1 give a picture every 3 hours almost everywhere.
- From late 1994 on, CLASS has full-resolution GOES (GOES-8 and later, including GOES-12). For 1994 to 2017, GridSat-GOES has the same satellites already gridded and calibrated.

</details>

<details>
<summary>Aerial Imagery</summary>

## World wide

## North America only

[1954 Air Photos of Southern Ontario](https://utoronto.maps.arcgis.com/apps/mapviewer/index.html?webmap=6847f7c14bcb4f7cb978772a514b3f85)
[Canada National Air Photo Library](https://www.eodms-sgdot.nrcan-rncan.gc.ca/index-en.html) - federal air photos from the 1920s on
[Western Libraries Air Photo Collection London ON](https://experience.arcgis.com/experience/ee8857ecdec04649a72af07c2dc200fe/page/Page/)
[University of Waterloo Kitchener-Waterloo historical air photos (via Wayback Machine)](https://web.archive.org/web/*/lib.uwaterloo.ca/locations/umd/project/*) - site is offline. The tile pages (IM1.html, IM2.html...) and TIF/TFW files from 1930 and 1945 can still be recovered through the Wayback Machine

## South America only

## Africa only

## Europe only

## Asia only

</details>

# Constituency Cards

**This has not been updated following the 2019 General Election, so consider this archived now**

**An open data experiment involving MP portraits, electoral data, population data, geodata and a few other bits and bobs. For the most recent data, go to the files folder and you'll see the most recent file version, including a constituency geofile to join it to. I've provided a custom constituency file that shows the loughs of Northern Ireland, because otherwise it just doesn't look right.**

[Click here](https://drive.google.com/drive/folders/1xPneIJtI4xWQhJ8TrxsCGHjGRcqCybKa?usp=sharing) to go straight to the maps. Read more about how I did this [on my blog](http://www.statsmapsnpix.com/2019/08/constituency-cards.html). Go to the files folder for the latest up-to-date spreadsheet. 

This is a spare time project that I'd been meaning to put together for a while, but hadn't got round to. However, with a general election potentially looming, I thought I'd try to get it done over a few evenings and weekends. My intention was to put together a set of virtual 'constituency cards' - one for each Westminster constituency - that provided some basic information on each area, its MP and the last general election (or by-election). My underlying goal was to see if it was possible to bring together multiple open data sources, including the new official MP portraits, and create some useful information out of it all. The files I link to in the [images folder](https://github.com/alasdairrae/wpc/tree/master/images) are the result. The intention is that they are used as a set of cards to be viewed on screen - that's why they're sized using a 16:9 ratio. Software? I did it all in [QGIS](https://qgis.org/en/site/).

## Read more about this 
If you want to read more about this little project, including data, software, styling and all that, then head over to [my blog post on it](http://www.statsmapsnpix.com/2019/08/constituency-cards.html), where I have explained it all in detail. But remember, I have not done this in any official capacity - it's really just an open data experiment to see how much useful information I could extract from a mix of raw data sources. If you're looking for more in-depth information on each constituency, in an interactive format, then I recommend you look at the [Constituency Dashboard tool](https://commonslibrary.parliament.uk/local-data/constituency-dashboard/) developed by the team at the House of Commons Library.

![An example](http://ajrae.staff.shef.ac.uk/img/wpc/20190816_131448.jpg)

## Sources and licencing
The MP photos were mostly sourced from the official portraits that were published by the Parlimanetary Digital Service [which you can find on Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Official_United_Kingdom_Parliamentary_photographs_2017). These photos were released under a Creative Commons licence and their existence is one of the main motivations for me doing this - I think they're great and wanted to find a project I could integrate them into. The official MP portraits, unfortunately, only cover about 90% of MPs, but I didn't want to miss anyone out so I extracted the rest from public sources, including Wikipedia and Twitter. I think having the MP portraits adds a lot to the images and helps humanise them.

The underlying electoral data comes from the [House of Commons Library](https://researchbriefings.parliament.uk/ResearchBriefing/Summary/CBP-7979) - at the bottom of the linked page - and also from  [mySociety](https://www.mysociety.org/wehelpyou/see-a-list-of-every-mp-in-parliament/) who, by the way, do amazing work more generally. Data produced by the House of Commons are also open, and available under the [Open Parliament Licence](https://www.parliament.uk/site-information/copyright-parliament/open-parliament-licence/). The underlying GIS data comes from [ONS](http://geoportal.statistics.gov.uk/) and [Ordnance Survey](https://www.ordnancesurvey.co.uk/opendatadownload/products.html). The information on distance to Parliament and area of each constituency are figures I calculated myself in QGIS. 

For the colours, these are mostly the same as the ones the BBC use. However, for Independent MPs (who I have found difficult to keep track of, sorry!), I have used a pinkish colour that others have adopted, and for the Speaker I used the blue from the [Parliamentary Digital Service blog](https://pds.blog.parliament.uk/). Thanks to Philip Brown at the University of Sheffield for helping with all this.

**Source for constituency EU Referendum data:** “Areal interpolation and the UK’s referendum on EU membership”, Chris Hanretty, Journal Of Elections, Public Opinion And Parties, Online Early Access, http://dx.doi.org/10.1080/17457289.2017.1287081 (this dataset was made available under a CC0 Public Domain licence). https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/S4DLWJ


**Alasdair Rae, 04 December 2019**


[@undertheraedar](https://twitter.com/undertheraedar) - please get in touch if you spot any errors.

ykdata
======

EMR Air Photo Library
---------------------

. | ..
---------- | -------------
Flight lines and points index | ftp://ftp.geomaticsyukon.ca/CSW/imagery/ Airphoto_Flight_Lines.zip, Airphoto_Locations.zip 
Direct access to images | http://yap.gov.yk.ca/fileshare/
Webmap to the flight line index | http://mapservices.gov.yk.ca/Skyline
Text search of metadata | http://199.247.132.58:8000/cgi-bin/gw/chameleon
email | emrlibrary@gov.yk.ca
Phone | 667-3111|

### Core Idea ###

1. Geo-reference each of the publicly available scanned photos
2. Clip collars
3. Mosiac (?) 

The result won't be _ortho_ photos, they'll still have lens distortion etc., but at least you can drop them into GIS and they'll be in the right spot. *Mosiac* is a question because I'm unsure mosiacking non-ortho's will generate a useful product.
   


### More info ###
 
> …digitization of our air photo collection is still in very initial stages. Only around 2000 digital images are currently available via SkyLine. (This might sound like a lot but there are well over 100,000 photo points…) You can tell which photo points have digital images attached because a ‘+’ sign shows up in the brown dot, and a thumbnail will appear in the Details tab of the Air Photo Location window.
> 
> The other thing to be aware of is that the library doesn’t own all of the photos indexed in SkyLine. … If you would like digital copies of these [specific] images I can scan copies for you and send them by email. The scan resolution is 600dpi. If you need other images from this roll you will need to order copies from the National Air Photo Library.
> 
> If you are interested in scanning a large number of photos we would ask that you visit the library to retrieve the photos. You can scan them here or check them out for a 24 hour loan, but we ask that you leave credit card information to secure the loan.

Customer driven scans are not automatically added to Skyline, though that may come in future.

Each 600dpi scanned image from NAPL is $33, which is prohibitively expensive when contemplating a collection. More cost effective, but still too much, to order prints at $13 ea. and scan personally. 

Local government has tried to negotiate a shared cost for scanning deal or similar but it hasn't gone anywhere; word is NAPL drastically understaffed and underfunded, so the lackluster response is not necessarily a signal of no will for the idea. 


Find all digitized photos: 

    SELECT * FROM AIRPHOTO_PT WHERE SCANNED_PHOTO_IND <> 'NULL'

 



Task #1:
Find the api call that allows you to search for all images of "cats".

API Call:
curl "https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=079d5c48316997001ca38e693556f368&tags=cat" -o flickr.json

Task #2:
Find the api call that allows you to search for all images from "Charlotte, North Carolina".

API Call:
curl "https://api.flickr.com/services/rest/?method=flickr.places.find&api_key=079d5c48316997001ca38e693556f368&query=Charlotte,+NC" -o charlotte.json

curl "https://api.flickr.com/services/rest/?method=flickr.photos.geo.getLocation&api_key=079d5c48316997001ca38e693556f368&place_id=KtHrHAVTUb1F.npO" -o charlotteNC.json

Task #3:
Get all of the comments for any photo.

API Call:
curl "https://api.flickr.com/services/rest/?method=flickr.photos.comments.getList&api_key=079d5c48316997001ca38e693556f368&photo_id=18149663983" -o comments.json

Task #4:
Search for a list of all the photos in your current latitude and longitude.

API Call:
curl "https://api.flickr.com/services/rest/?method=flickr.places.find&api_key=079d5c48316997001ca38e693556f368&query=New+York,NY+" -o currentLocation.json

curl "https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=079d5c48316997001ca38e693556f368&lat=40.714&lon=-74.007" -o currentLocation.json

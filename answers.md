Task #1: Find the api call that allows you to search for all images of "cats".

API Call: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=ENTERYOURAPIKEY&tags=cat" -o cats.json

Task #2: Find the api call that allows you to search for all images from "Charlotte, North Carolina.

API Call: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=ENTERYOURAPIKEY&lat=35.2270869&lon=-80.8431267" -o nc.json

Task #3: Get all of the comments for any photo.

API Call: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.comments.getList&api_key=ENTERYOURAPIKEY&photo_id=16393044637" -o comments.json

Task #4: Search for a list of all the photos in your current latitude and longitude.

API Call: "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=ENTERYOURAPIKEY&lat=40.7400388&lon=-73.99000168" -o latlon.json

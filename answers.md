Task #1: search for all images of cats

API Call: curl "https://api.flickr.com/services/rest/?method=flickr.photos.search&tags=cat&api_key=0b242c2e93f8f2845ec1b7405c59c99e" -o cats.json

Task #2: search for all images from "Charlotte, North Carolina"

API Call to get place id: curl "https://api.flickr.com/services/rest/?method=flickr.places.find&query=charlotte,NC&api_key=0b242c2e93f8f2845ec1b7405c59c99e" -o charlotteID.json

API Call to get charlotte photos: curl "https://api.flickr.com/services/rest/?method=flickr.photos.search&place_id=KtHrHAVTUb1F.npO&api_key=0b242c2e93f8f2845ec1b7405c59c99e" -o charlotte.json

Task #3: search for all comments in an image (id: 18149663983)

API Call: curl "https://api.flickr.com/services/rest/?method=flickr.photos.comments.getList&photo_id=18149663983&api_key=0b242c2e93f8f2845ec1b7405c59c99e" -o catcomments.json

Task #4: search for all images in NYC (lat/Long)

API Call: curl "https://api.flickr.com/services/rest/?method=flickr.photos.search&lat=40.7127&lon=74.0059&api_key=0b242c2e93f8f2845ec1b7405c59c99e" -o nyc.json

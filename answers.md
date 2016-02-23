##### Task #1: Find the api call that allows you to search for all images of "cats".
```bash
export FLICKR_API=my-api-key
```
API Call:  https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=${FLICKR_API}&tags=cat

##### Task #2: Find the api call that allows you to search for all images from "Charlotte, North Carolina.

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.search&api_key=${FLICKR_API}&tags=Charlotte+%20+North+%20+Carolina

##### Task #3: Get all of the comments for any photo.

API Call: https://api.flickr.com/services/rest/?method=flickr.photos.comments.getList&api_key=${FLICKR_API}&photo_id=18149663983

##### Task #4: Search for a list of all the photos in your current latitude and longitude.
API Call: https://api.flickr.com/services/rest/?method=flickr.flickr.photos.search&api_key=${FLICKR_API}&lat=40.7398848&lon=-73.9922705

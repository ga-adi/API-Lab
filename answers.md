Task #1: Find all cats images in flickr

API Call: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=b71dade4d2c0865bd805eab9c5a74199&tags=cats" -o task2.json

Task #2: Search all images from charlotte, nc

API Call: 

curl "https://api.flickr.com/services/rest/?&method=flickr.places.find&api_key=b71dade4d2c0865bd805eab9c5a74199&query=charlotte+north+carolina"

place id = KtHrHAVTUb1F.npO

curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=b71dade4d2c0865bd805eab9c5a74199&place_id=KtHrHAVTUb1F.npO" -o charlotte

API Call: Get comments 

Task #3: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.comments.getList&api_key=b71dade4d2c0865bd805eab9c5a74199&photo_id=18149663983" -o comments

API Call: search photos by current lat and lon

Task #4: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=b71dade4d2c0865bd805eab9c5a74199&lat=40.7&lon=74&radius=12" -o nyc1


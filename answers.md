Task #1: Search for cat pics.

API Call: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=bb1f266d4cd18f86be574d3e8e35276a&tags=cats" -o catpic2.json

Task #2: Search in charlotte, NC

API Call:curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=bb1f266d4cd18f86be574d3e8e35276a&place_id='KtHrHAVTUb1F.npO'" -o charlottepics.json

Task #3: Get comments for photo

API Call: curl "https://api.flickr.com/services/rest/?&method=flickr.photos.comments.getList&api_key=bb1f266d4cd18f86be574d3e8e35276a&photo_id=18149663983" -o comments.json

Task #4: Find pics for current location.

API Call:curl "https://api.flickr.com/services/rest/?&method=flickr.photos.search&api_key=d82927c732aa51375ffd5ff3020afb31&lat=40.7127&lon=74.0059" -o newyorkpics.json

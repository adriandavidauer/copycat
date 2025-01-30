# Copilot Test Project 

# copycat
copycat for youtube


## Resources
[on creative commons on youtube](https://www.youtube.com/watch?v=kBG-RnZU2cQ)


## How to make a call to the API
[API](https://developers.google.com/youtube/v3/docs/search/list?apix_params=%7B%22part%22%3A%5B%22id%22%5D%2C%22eventType%22%3A%22completed%22%2C%22order%22%3A%22viewCount%22%2C%22type%22%3A%5B%22video%22%5D%2C%22videoLicense%22%3A%22creativeCommon%22%2C%22videoType%22%3A%22any%22%7D#type)


## Watch out for music videos!
Music videos have different licencing. Apperently they can have CC License for the Video but other for the Sound!!!
[Example](https://www.youtube.com/watch?v=Rg4HQ1RhhYk)
### How to accomplish that?
- use [videoCategory](https://developers.google.com/youtube/v3/docs/videoCategories/list?apix_params=%7B%22part%22%3A%5B%22snippet%22%5D%2C%22id%22%3A%5B%221%22%5D%7D#usage) - just need to check all the categories uff...is there a list somewhere?
- probably need to still explicitly check music licence in the video but not using the music category rules out a lot of possible videos that can have licenced music

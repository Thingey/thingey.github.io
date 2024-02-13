# thingey.github.io

Project under development...

Goals!

Be a asset for world makers of VRChat to Easy have youtube playlist or lists they can press and watch youtube videos with their friends inside of VRChat.
This project is made to try exlude the need to tab out to browsers and copy links and get a easy updated list from multiple youtube channels and always get new videos instead of youtube's search that shows all from 1 day to 3 year old videos as result unless you go intot he challens page and look if they posted new content.

How does it work?

1. Enter your YouTube API Key in a text document and in another your Github Key and YouTube channel's ID of desire. 
2. Python code pulls out X (Default max by YouTube API: 50) recently posted videos per channel. (sounds much but goes in a flash)
3. Arrange the videos published to YouTube from all channels in date order with latest at the top (the list mixes the results from all channels)
4. Sends the compiled list set to maximum X (default set to 50 videos in total) to Gist with Github APi or desired service that suppost API with update post function (pastebin does not but "Pastes.io" should I believe )
(working on a way to make it only update towards the Girst/APi if a new video was found in order to not send an update for no changes to the play list)
5. The udon prefab is then placed at desired place in your World and you enter the link to your raw data of gist or place. (there might an additinal step here to attach video player.
6. Then essentally you upload the world and you should have simple list with buttons that loads the desired video to watch directly inside the world without the need to tab out of browser.
7. Progress:
8. Python code: 100% Done in terms from A to B (Now its just tweaking and modifying it to preform better on all ends and not do work it don't need to)
8. Udon code/prefab: 10% ish (you can read the the text inside the world but I havent figured out how to make each video a clickable link inside of unity yet, so its unusable text just showing title and URL to the video for now.

Why are you doing this?

I watch a lot of funny videos in VRChat with PC and Quest friends and It is annoying to tab out just to find new videos to watch and my Quest friends complains about they cant copy link from outside the game with their headsets, so I thought "Can I eaisly make a way to get the latest funny videos and have buttons inside of my world to just press play on to enjoy the content?"

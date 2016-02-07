# Edison Phonograph Plus
The phonograph was invented in 1877 by Thomas Edison. It's due for an update. How about we hook-up an Intel Edison to a vinyl record player and bring some WiFi to the HiFi.

Intel Project Page (but I accidently submitted it, so waiting to here if that can be undone):
https://iotroadshow.intel.com/en/teams/project/8

## Background on the Problem
The inspiration for this project came from my personal problem of wanting to wirelessly stream the audio from my record player in my living room to multiple rooms around the house and/or outside. With the release of the Chromecast Audio, one can now stream an mp3 URL to multiple rooms in sync for a cost of a Chromecast Audio ($35/piece) and some hacking.

## Goals of the Product
The initial goal would be to capture the audio output of a vinyl record player via a USB sound card hooked up to the Intel Edison, stream it to an mp3 URL, and have an Android client app to then discover the Edison-enabled record player and cast it to a Chromecast(s).

With the Edison now nearby the record player, there's a whole world of possbilities --

 - We could use the EchoNest API to send samples of the song, determine what is being played, and send that metadata to the clients/chromecasts.

 - We could connect to the Discogs API to automatically update a digital list of your collection, recommend other records, or add a new/rare/unknown record to the Discogs universe.

 - We could use the sensors to detect RPMs to monitor performance or visualize when a DJ is scratching.

- We could use sensors to detect the angle of the tonearm to determine how far into the record you are.

- We could let you a scratch-effect live from an app or capacitive touch without having to really scratch your records.

- We could make it super-simple to export samples of a track from a record in real-time using an app to start/stop the sample points and save it locally or in the cloud.

- Any much, much more...

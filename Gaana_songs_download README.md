Steps-
1. Download the songs from Mobile app. Use older versions (available in the folder). Download by including it into the respective playlists. Follow the images folder.
2. Using "ES File Explorer" app, go to "Android\data\com.gaana\files". You find nothing.
3. Then on left panel inside the App, enable "see hidden files".
4. Then, you will find ".gaana" folder which contains many downloaded files.
5. Now, move the folder to a desired location(internal-storage\DCIM\.gaana) and then transfer files to PC (E:\Songs\gaana)
6. Now, save the jar file "GaanaExtractor-2.5.jar" in "E:\Songs" and songs into "E:\Songs\gaana".
7. Now, open cmd in the location "E:\Songs" and use the following command:
	java -jar GaanaExtractor-<version>.jar "E:\Songs\gaana\" true
i.e.    `java -jar GaanaExtractor-2.5.jar "E:\Songs\gaana" true`

8. Now, all the files are converted into this location - "E:\Songs\gaana\converted"
	> NOTE: all the files downloaded through Gaana app is in '.m4a' format.
	
9. But, the transferred files are in different folders with respective movie names.
	- So, just "Add folder to library" in iTunes.
	- then select the songs and "drag and drop" into required destination folder.

## Download process
* Open Gaana in desktop and search songs one by one.
* download the songs and cut paste the songs in DCIM.gaana folder.
* TROUBLESHOOTING:
	- If the song is not getting downloaded, then just re-install the .apk and try download again. The issue will be resolved.

## Resources
* https://github.com/PathriK/GaanaExtractor [DEPRECATED]

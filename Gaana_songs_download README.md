Steps-
1. Download the songs from Mobile app.
2. Using "ES File Explorer" app, go to "Android\data\com.gaana\files". You find nothing.
3. Then on left panel inside the App, enable "see hidden files".
4. Then, you will find ".gaana" folder which contains many downloaded files.
5. Now, move the folder to a desired location(internal-storage\DCIM\.gaana) and then transfer files to PC (E:\Songs\gaana)
6. Now, save the jar file "GaanaExtractor-2.5.jar" in "E:\Songs" and songs into "E:\Songs\gaana".
7. Now, open cmd in the location "E:\Songs" and use the following command:
	java -jar GaanaExtractor-<version>.jar "E:\Songs\gaana\" true
i.e.    java -jar GaanaExtractor-2.5.jar "E:\Songs\gaana" true

8. Now, all the files are converted into this location - "E:\Songs\gaana\converted"

NOTE: all the files downloaded through Gaana app is in '.m4a' format.


## Resources
* https://github.com/PathriK/GaanaExtractor

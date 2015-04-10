# gplay-cli
Google Play Downloader via Command line, based on https://codingteam.net/project/googleplaydownloader See package Readme for python modules to install.

	./gplay-cli.py 
	usage: gplay-cli.py [-h] [-y] [-s SEARCH] [-d AppID [AppID ...]] [-u FOLDER]
	                    [-f FOLDER] [-v]

	A Google Play Store Apk downloader and manager for command line

	optional arguments:
	  -h, --help            show this help message and exit
	  -y, --yes             Say yes to all prompted questions
	  -s SEARCH, --search SEARCH
	                        Search the given string into the Google Play Store
	  -d AppID [AppID ...], --download AppID [AppID ...]
	                        Download the Apps that map given AppIDs
	  -u FOLDER, --update FOLDER
	                        Update all the APKs in the given folder
	  -f FOLDER, --folder FOLDER
	                        Where to put the downloaded Apks
	  -v, --verbose         Be verbose

If you want to use your own Google credentials, simply change `self.config` values in the `gplay-cli.py` file with your own settings. 
If you want to generate androidID, see https://github.com/nviennot/android-checkin/, otherwise you could either use the given one (default) or use one of your devices ID.
# maincopy
This script is designed to copy the main movie from a DVD. It will extract the video, audio, and subtitles (if any). It will
requantize the video stream (if needed), then put everything back together again so that everything will fit on a blank 4.7gb
blank DVD disc. It creates an ISO Image file that can be burned at your convenience. Maincopy is the primary script and maincopynosub will be run automatically only if there is no subtitle stream found in the Title that is copied. Both scripts should be put in your $BIN Directory and both should be made executable. The way I have it setup is to create a folder called "DVD" in your $HOME Directory, open the empty folder in a terminal and type: maincopy. The script will do the rest.

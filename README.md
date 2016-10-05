
Radiology
=========

TO USE THE MAIN APPLICATION:

1. To use the application Radiology, you must run App.py or use Jupyter to run App.ipynb.

2. You will be prompted to enter an artist's name of which you'd like to see similar artists for.

3. There are features that you can choose from, choose the features that best fit the profile of your artist.
	-The same set of features will be compared to the similar artists

4. Select a dataset. We have provided numerous types of datasets in the datasets/ folder.

5. Hit search and enjoy! We will only display the top 5 similar artists for a given artist with the addition of a similarity rating.


TO USE THE DATASET GATHERING APPLICATION:

1. To use the application that gathers data for use in the main application, you must run AppGather.py or use Jupyter to run AppGather.ipynb

2. You will be prompted to enter a delay (measured in seconds) per API access call to EchoNest. This is to avoid the limitations of the 20 API calls per minute that is given by EchoNest.
	-It is recommended to use more than 3 seconds per API call. You are allowed only 20 calls per minute.

3. Select a dataset to append the data to. If you want to create a new one, make sure you create an empty text file then select it using this application.

3. Hit Gather and wait!

Information about our datasets:
-small_dataset.txt contains 2,720 songs with the genres: classical, pop, rock, punk, and rap
-huge_dataset.txt contains 8,256 songs with the genres: classical, pop, rock, punk, and rap
-classical_only.txt contains 1,430 songs with the genres: classical
-empty_dataset.txt contains 0 songs with the genres: ---
-jazz_chinese_opera_light_music_punk_latin.txt contains 2,418 songs with the genres: jazz, chinese opera, light music, punk, and latin
-chinese_opera_meditation_punk_pop_rap_kpop.txt contains 1,273 songs with the genres: chinese opera, meditation, punk, pop, rap, and k-pop

Team Members:
Pei Liu - esponavy@yahoo.com
Peter Chen - peter.chen20@gmail.com
Long Trinh - kevintrinh255@gmail.com
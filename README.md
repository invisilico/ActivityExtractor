# ActivityExtractor
Android phone App Activity Data Extractor made during SRBR ChronoSchool 2020.

Extraction and Basic visualisation (raster plots) from My Activity.json file provided by https://takeout.google.com/

Full version includes data cleaning utilities and more complex options to deal with the dataset in a step by step manner. A raster plot utility is also provided to visualize the data. This lets you make full use of the data, including dataframe queries and keeping appnames (removed optionally in privacy). RAPID version is a single cell version, should you be short on time and need the files ready with optimised presets.(just time stamps in preset months, with no app names). Both notebooks need you to first folow the tutorial below and obtain the 'My Activity.json' file from Google Takeout.

Open the notebook now if you know what you're doing:

ActivityExtractor: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/invisilico/ActivityExtractor/blob/master/Activity_Extractor.ipynb)

RAPIDExtractor: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/invisilico/ActivityExtractor/blob/master/Rapid_Extractor.ipynb)

OR, follow the instructions:

To obtain Android app activity data:

Visit https://takeout.google.com/ and ensure you are signed into the same account as the primary one on your android phone. 

Under "Select data to include", first click on "Deselect all". One of the options as you scroll down will be "My Activity" under which two buttons are present. Click the second button that currently says "All activity data included" and in the menu that pops up, first select "Deselect all" and then check "Android" and say "Ok". The button should now say "1 product selected". Then click the "Multiple formats" button to the left and in the pop-up, on the Activity Records field (top right dropdown) click on the "HTML" to reveal the option for JSON. Select JSON and click "Ok".

Scroll down, click on "Next step" and in the following options set: "Send download link via mail", "Export once" and .zip or .tgz on personal preference. The last field can be left as is as the JSON file should not be too large (mine was <10MB)

The Link should soon appear in your e-mail or should you stay on the page, head to "manage exports" and an option to download will appear.

Download the compressed archive. Once Downloaded, unzip/decompress the file. From the extacted directory (folder), go to takeout > My Activity > Android > My Activity.json

Save the "My Activity.json" file in a suitable location, for your convenience. 

You're all set to go! Choose one of the notebooks linked below to continue!

ActivityExtractor: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/invisilico/ActivityExtractor/blob/master/Activity_Extractor.ipynb)

RAPIDExtractor: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/invisilico/ActivityExtractor/blob/master/Rapid_Extractor.ipynb)

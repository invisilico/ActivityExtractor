# ActivityExtractor
Android phone App Activity Data Extractor made during SRBR ChronoSchool 2020.

Extraction and Basic visualisation (raster plots) from My Activity.json file provided by https://takeout.google.com/

Open the colab if you know what you're doing:                   
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](link)

OR, follow the instructions:

To obtain Android app activity data:

Visit https://takeout.google.com/ and ensure you are signed into the same account as the primary one on your android phone. 

Under "Select data to include", first click on "Deselect all". One of the options as you scroll down will be "My Activity" under which two buttons are present. Click the second: "All activity data included" button and in the pop up menu, first select "Deselect all" and then check "Android" and say "Ok". Then click the "Multiple formats" button to the left and in the pop-up, on the Activity Records field (top right dropdown) click on the "HTML" to reveal the option for JSON. Select JSON and click "Ok". 

Scroll down, click on "Next step" and in the following options set: "Send download link via mail", "Export once" and .zip or .tgz on personal preference. The last field can be left as is as the JSON file should not be too large (mine was <10MB)

The Link should soon appear in your e-mail or should you stay on the page, head to "manage exports" and an option to download will appear.

Download the compressed archive. Once Downloaded, unzip/decompress the file. From the extacted directory (folder), go to takeout > My Activity > Android > My Activity.json

Save the "My Activity.json" file in a suitable location, for your convenience. 

You're all set to go! Head to the notebook linked below to continue!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](link)

Note: This data file will never go any further than your own google drive. The final CSV shared has limited data, and there is complete flexibility to clean the dataset within the colab notebook.

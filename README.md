Steam Product Data Importer
================================

This repository is a collection of Google Apps Scripts that you can use with Google Sheets.  They allow you to automatically import data from Steam, such as the number of wishlists your games are getting per-day, and have the raw data appear in Google Sheets, where you can then do further analysis (e.g. by looking at spikes in wishlist actions).

To use this script, when you have a Google Sheet open, select "Tools -> Script Editor", and then paste the contents of "WishlistDataImport.gs" into a new script.  Then follow the instructions in the script and set the various options to configure it.

You can schedule the import to automatically happen by using the scheduled triggers icon (it's the clock icon next to the cloud upload icon in the Google Script editor).

![A screenshot showing Steam Product Data and Google Sheets side-by-side](/preview.png?raw=true)
# Sanitizing Script for Cloud Upload

Sanitizing Script to use before uploading files to cloud storage

Note: I tested this script on MacOS 15.5 for uploads to Egnyte cloud storage. Your mileage may vary. 

##Overview

I frequently run into issues where clients provide files that break the upload process to cloud storage, with filenames like "Presentation File | For Clients | Final-Final-90%.indd, which prevents uploading. So this script replaces all prohibited characters with underscores. 

##Usage

Call this script as follows: 

/sanitize.sh /Folder/Sub Folder

# appstoreconnect_whatsnew_translate
Eliminate the pain of iOS updates with automatic translation of the What's New field for all supported languages for your app.

# What's New Section Updater

Written by: Jack A. Cole, Ph.D.
Mindware Consulting, Inc.
https://www.linkedin.com/in/jack-cole-b84b5638/

This notebook will update the "What's New" field in App Store Connect for the latest release of the app.  This is a strong pain point for apps that have many languages, as the App Store Connect UI does not allow for bulk editing of the "What's New" field.  This notebook will allow you to update the "What's New" field for all languages at once.

# Instructions

In App Store Connect, go to Users and Access/Integrations.

Create a new API key and download the key file.  You will need the key ID, issuer ID, and the key file.

Create a new app version for your app in App Store Connect.  You will need the app ID and the version ID.

Download the Jupyter Notebook above.

Enter all of the above information in the config cell.

Enter the text for the "What's New" field in the config cell.  This will be automatically translated into all languages for your app.

Run the notebook.

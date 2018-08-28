# Magento Customization Script

This repo contains the script to add a new tab named "My Information" to the product page of the Magento demo store that comes with the gsd docker image.

The instructions below assume you have docker running in your machine using the  Kitematic GUI

To have this code into your store follow the following steps:
- Clone/download the repo to any directory in your laptop
- Download the alankent/gsd Docker container using Kitematic GUI and run the container.
- Map the repo you downloaded above to the app/code volume of the container
- Refresh the magento cache and navigate to the magento demo store to view the new tab and attribute created.







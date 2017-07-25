# Spire API Postman Collection

A set of example HTTP requests for the Spire APIs using Postman. These include:

* Vessels (Beta)
* Messages

# Requirements

In order to utilize this repo you will need two things:

1. A [Spire API access token](https://spire.com/contact/developer-portal/).
2. [Postman](https://www.getpostman.com) for Mac, Windows, or Chrome.

# Setup

1. Clone or [download](https://github.com/kjbrazil/spire-api-postman-collection/archive/master.zip) this repo to your local machine.
2. Open Postman.
3. In the top left corner click "Import".
5. Drag or find both the ``Spire_API.postman_collection.json`` & ``Spire.postman_environment.json`` files and click open.
6. Both the collection and the environment variables will be imported to Postman.
7. In the top right corner, click the gear icon and select "Manage Environments".
8. Click "Spire".
9. Locate the access token sent to you by the Spire Customer Experience team.
10. Navigate back to Postman and replace ``your-api-token`` with your actual credentials.
11. Click "Update" and close the window.
12. Click the environment drop down again and select "Spire".
13. You are now ready to start making API calls!
14. Try querying all Spire vessels by clicking the 01_Vessels Beta folder > "List All Vessels" > Send.

# Support

If you encounter any issues please [email Spire Customer Experience](mailto:cx@spire.com). Please also feel free to improve upon the collection and submit pull requests. :-)
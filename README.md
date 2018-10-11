# VirusTotal-Postman-Collection
This repo contains a [Postman](https://getpostman.com) collection for interacting with the [VirusTotal Public API](https://www.virustotal.com/en/documentation/public-api/).


## Using the collection
1. Install Postman.
2. Download or clone this repository.
3. [Import](https://www.getpostman.com/docs/v6/postman/collections/data_formats#exporting-and-importing-postman-data) the "VirusTotal API (Public).postman_collection" file.
4. Find your VirusTotal API underneath your VirusTotal profile.
5. Store your VirusTotal API key in a Postman [environment variable](https://www.getpostman.com/docs/v6/postman/environments_and_globals/intro_to_environments_and_globals) called "apikey"

The Postman collection contains the following queries:
* Files
  * Scan file
  * Retrieve file scan report
  * Rescan already submitted file
* URLs
  * Send and scan URL
  * Retrieve URL scan report
  * Retrieve URL scan report (scan if does not exist)
* Domains
  * Retrieve domain report
* IPs
  * Retrieve IP address report
* Comments
  * Comment on file or URL
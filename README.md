# 2014-Congress-Web-Scrape-Tool
### Web scraping tool that was run for the 2014 election period to determine changes to Congress platform info
___
This tool scrapes the main page for each candidate and for all links on that page.  The output was useful for academic research as it allowed for sentiment analysis to be performed throughout the campaigns.

For each link and captured sub-link, the following is output to a separate worksheet:
* Candidate Name (copied from link list)
* Race (copied from link list)
* Party (copied from link list)
* Incumbent Status (copied from link list)
* Each URL that exists on the candidate's site
* The raw page text found on each link
* Character count of the text captured on each link

### Note: This is a tool which uses Excel to control Internet Explorer.  This will NOT work as-is in OSX.

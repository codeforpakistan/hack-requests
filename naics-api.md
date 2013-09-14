Request for Hack: Expand NAICS API
========

[NAICS](http://www.census.gov/eos/www/naics/) (North American Industry Classification System) is maintained by the United States Bureau of Labor Statistics to classify business types. It is used for aggregating, presenting, and analyzing data and trends in the US economy.

The classification system is hosted by the Census Bureau in Excel  and HTML formats. There is much room for improvement in making this information accessible by an API to assist with developing applications that depend on understanding or collecting information about businesses. 

The Product
--------

NAICS API is currently a Node.js server that returns NAICS data in a JSON format. Information stored on the server has been scraped or collected from files on the Census.gov web site. Most of the information for 2007 and 2012 has now been scraped thanks to the addition of a python scraper by Mike Migurski to retrieve examples and cross-references from 2012 NAICS.

* [NAICS API](https://github.com/louh/naics-api) - the API server and data we currently have
* [NAICS API documentation](http://docs.naicsapi.apiary.io/)

* [NAICS Search](https://github.com/louh/naics-search) - simple example Search interface for NAICS codes

Help Needed
--------

There are other data that can be included in the API. Not all of these are within the scope of the scraper however.

* Illustrative examples from 2007 NAICS
* Information from NAICS prior to 2007 (2002, 1997 - low priority)
* Data for converting between different NAICS codes and other systems, like SIC or NIGP

On the API side:

* The API should perform searches on all the available data and return relevant results from the requester (e.g. a business type lookup application)
* Close [existing issues](https://github.com/louh/naics-api/issues?state=open)

For more information contact [Lou Huang](mailto:lou@codeforamerica.org).

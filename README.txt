Goal of the Project
Extract English Wikipedia pageview data from APIs and plot the data in a time series visualization.

License of Source Data
https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions

API documentation
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews


Output file description
Column							Value
year							YYYY
month							MM
pagecount_all_views				num_views
pagecount_desktop_views			num_views
pagecount_mobile_views			num_views
pageview_all_views				num_views
pageview_desktop_views			num_views
pageview_mobile_views			num_views


Known issues and special considerations
Data from the Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.
The Legacy Pagecounts API provides access to desktop and mobile traffic data from December 2007 through July 2016.
The Pageviews API provides access to desktop, mobile web, and mobile app traffic data from July 2015 through last month.
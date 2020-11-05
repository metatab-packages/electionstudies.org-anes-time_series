# American National Election Studies Time Series



## Development And Updates

The ANES website is implmented in Wordpress, and the data files are stores and distributed as Wordpress media, which means that the URLS that are posted on the website have persistend URLs, but they re-direct to URLs that include the date of the upload, and if these files get updated, all of the URLs in this package wiil also need to be updated. The URLS in this package were discovered by copying the URL listed in the website and resolving the redirection with ``curl -D - <url>`` and looking at the 'Location:' header. 
## v0.0.7

- Bugfixes
- Memory management improvements

## v0.0.6

- Bugfixes

## v0.0.5

- Bugfixes

## v0.0.4

- Added constructor option `runCronAtOnce` to start cronJob immediately
- Added constructor option `onCronComplete` which is a callback function executed each time the job is complete


## v0.0.3

- Added `getSingleListingJson()` method, which returns the `JSON` representations of a single Listing.
- Added ability to tell the constructor whether to set up cron jobs or no. Don by passing `{setCron: true, ...}` option to constructor.

## v0.0.2

- Added `getXml()` method, which returns [libxmljs][] Document object to easily perform queries. 

## v0.0.1

- Setup ListHub to download and store your feed file
- Saves the `gzipped` file
- Extracts `xml` file
- Provides some handy functions to read and return the xml as string
- Setts up cron jobs to retrieve the feed on specified time
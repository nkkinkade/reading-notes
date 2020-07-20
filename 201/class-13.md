# Read: 13 - Local Storage

## Local Storage
* userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure
* Local Shared Objects allow Flash objects to store up to 100 KB of data per domain
* Web storage goes by a few names, HTML5 Storage, Local Storage, and DOM Storage
* Web storage is a way for web pages to store named key/value pairs locally, within the client web browser
* This data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you
* This data is never transmitted to the remote web server
* Modernizr can be used to detect support for HTML5 Storage
* HTML5 Storage is based on named key/value pairs
  * The named key is a string
  * The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats; however, the data is actually stored as a string
  * If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype
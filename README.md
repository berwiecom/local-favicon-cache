# Local Favicon Cache 

By Timo van Neerden

---

This script uses a [Google Service](http://www.google.com/s2/favicons?domain=google.com) to constitute a local favicon cache.

The first time a favicon for any given domain-name or URL is requested, the script asks the google-service for the favicon and stores it locally. The next time a favicon for the same domain is requested, the locally stored icon is served.

This avoids network cross-sites requests and therefore enhances user-privacy (no google-requests).

---

This script is placed under MIT-License.

This script is based upon Mitsu's [gravatar-cache script](https://suumitsu.eu/wiki/doku.php?id=php:cache_gravatar), which is basically the same script but for Gravatar icons.


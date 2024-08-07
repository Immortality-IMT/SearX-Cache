# SearX-Cache

Speed up SearX with a caching system for SearX or SearXNG.

An open source disributed database that provides a caching system for searx to speed up repeated searches.

Note: if you run a public instance, please disclose to your users that the results of their queries are being cached.

To use:

Edit some source files

Unpack the cache to the correct location: /usr/local/searxng/searxng-src/searx/
```
sudo tar -xvf cache.tar.gz -C /usr/local/searxng/searxng-src/searx/
sudo chown -R searxng:searxng /usr/local/searxng/searxng-src/searx/cache
sudo chmod -R 755 /usr/local/searxng/searxng-src/searx/cache
```
To contribute to the cache:

Run the robot and then send your cache.
Use searx and then send your cache.

More info: https://www.imtcoin.com/kb.php?page=Caching+SearXNG+Version+2

The code changes follow the latest stable version of searxng.

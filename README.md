# python-lru-cache
Python Implementation of a Least-Recently-Used Cache

This library will be responsible for cacheing objects that are json key-value pairs.

The cache's core function are:
- write
- read
- update
- delete

Each of these function pertain to the json data.

Initialization of the LRU cache is

cache = lru_cache(MAX_CACHE_SIZE)


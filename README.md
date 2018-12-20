# twofour/memcached

Memcached is an in-memory key-value store for small chunks of arbitrary data (strings, objects) from results of database calls, API calls, or page rendering.

Small image (~ 4 MB) for Memcached based on Alpine.

## Usage

    docker run -it --rm -p 11211:11211 twofour/memcached

## Environment variables

### MEMCACHED_MEMORY_LIMIT

Memory limit for ``memcached`` in MB.

Default: 64

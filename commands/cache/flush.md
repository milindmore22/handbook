# wp cache flush

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Acache-flush+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Flush the object cache.

For WordPress multisite instances using a persistent object cache,
flushing the object cache will typically flush the cache for all sites.
Beware of the performance impact when flushing the object cache in
production.

Errors if the object cache can't be flushed.

### EXAMPLES

    # Flush cache.
    $ wp cache flush
    Success: The cache was flushed.




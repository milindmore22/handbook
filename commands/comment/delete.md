# wp comment delete

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Acomment-delete+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Delete a comment.

### OPTIONS

&lt;id&gt;...
: One or more IDs of comments to delete.

[\--force]
: Skip the trash bin.

### EXAMPLES

    # Delete comment.
    $ wp comment delete 1337 --force
    Success: Deleted comment 1337.

    # Delete multiple comments.
    $ wp comment delete 1337 2341 --force
    Success: Deleted comment 1337.
    Success: Deleted comment 2341.




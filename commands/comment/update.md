# wp comment update

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Acomment-update+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Update one or more comments.

### OPTIONS

&lt;id&gt;...
: One or more IDs of comments to update.

\--&lt;field&gt;=&lt;value&gt;
: One or more fields to update. See wp_update_comment().

### EXAMPLES

    # Update comment.
    $ wp comment update 123 --comment_author='That Guy'
    Success: Updated comment 123.




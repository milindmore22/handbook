# wp cron event delete

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Acron-event-delete+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Delete the next scheduled cron event for the given hook.

### OPTIONS

&lt;hook&gt;
: The hook name.

### EXAMPLES

    # Delete the next scheduled cron event
    $ wp cron event delete cron_test
    Success: Deleted 2 instances of the cron event 'cron_test'.




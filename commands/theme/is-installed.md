# wp theme is-installed

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Atheme-is-installed+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Check if the theme is installed.

Returns exit code 0 when installed, 1 when uninstalled.

### OPTIONS

&lt;theme&gt;
: The theme to check.

### EXAMPLES

    # Check whether theme is installed; exit status 0 if installed, otherwise 1
    $ wp theme is-installed hello
    $ echo $?
    1




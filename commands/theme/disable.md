# wp theme disable

<small>Quick links: <a href="https://github.com/issues?q=is%3Aopen+label%3Acommand%3Atheme-disable+sort%3Aupdated-desc+org%3Awp-cli">Github issues</a></small>

Disable a theme on a WordPress multisite install.

Removes ability for a theme to be activated from the dashboard of a site
on a WordPress multisite install.

### OPTIONS

&lt;theme&gt;
: The theme to disable.

[\--network]
: If set, the theme is disabled on the network level. Note that
individual sites may still have this theme enabled if it was
enabled for them independently.

### EXAMPLES

    # Disable theme
    $ wp theme disable twentysixteen
    Success: Disabled the 'Twenty Sixteen' theme.

    # Disable theme in network level
    $ wp theme disable twentysixteen --network
    Success: Network disabled the 'Twenty Sixteen' theme.



